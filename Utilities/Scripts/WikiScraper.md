r"C:\Vaults\Pathfindero
r"H:\Altri computer\Il mio computer\Pathfindero

```jupyter
import mimetypes  
import time  
from bs4 import BeautifulSoup  
import requests  
import os  
import re  
from urllib.parse import urljoin  
from collections import defaultdict
import shutil

########################################################## SETTINGS ########################################################

output_dir = r"H:\Altri computer\Il mio computer\Pathfindero\Utilities\Media\Immagini\Script"  # OUTPUT FOLDER FOR THE IMAGES  
base_folder = r"H:\Altri computer\Il mio computer\Pathfindero\World"                             # OUTPUT FOLDER FOR THE NOTE
url = "https://pathfinderwiki.com/wiki/Wolfpoint"                                                 # INSERT LINK TO SCRAPE


########################################################### FUNCTIONS ########################################################

def get_destination_folder(text, base_folder, file_name):
    if "Academy" in file_name or "University" in file_name or "College" in file_name:
        print("Matched with 'University/Academy'")
        return os.path.join(base_folder, "Geography/City Buildings")
    elif "Tavern" in file_name or "Inn" in file_name:
        print("Matched with 'Tavern/Inn'")
        return os.path.join(base_folder, "Geography/City Buildings")
    elif "Bay" in file_name or "Cape" in file_name or "Gulf" in file_name:
        print("Matched with 'Bay/Cape'")
        return os.path.join(base_folder, "Geography/Oceans")
    elif "Tower" in file_name or "Keep" in file_name or "Castle" in file_name or "Citadel" in file_name or "Bastion" in file_name or "Fort" in file_name or "Spire" in file_name:
        print("Matched with 'Tower/Keep/Castle/Citadel/Bastion/Fort/Spire'")
        return os.path.join(base_folder, "Geography", "Castles & Fortresses")
    elif "Cathedral" in file_name or "Temple" in file_name or "Monastery" in file_name:
        print("Matched with 'Cathedral/Temple/Monastery'")
        return os.path.join(base_folder, "Geography", "Cathedrals & Temples")
    elif "Desert" in file_name or "Oasis" in file_name:
        print("Matched with 'Desert/Oasis'")
        return os.path.join(base_folder, "Geography", "Deserts & Oasis")
    elif "District" in file_name or "Harbor" in file_name or "(district)" in file_name:
        print("Matched with 'District'")
        return os.path.join(base_folder, "Geography", "Districts")
    elif "Wood" in file_name or "Forest" in file_name:
        print("Matched with 'Wood/Forest'")
        return os.path.join(base_folder, "Geography", "Forests")
    elif "Island" in file_name or "Isle" in file_name or "Peninsula" in file_name:
        print("Matched with 'Island/Isle'")
        return os.path.join(base_folder, "Geography", "Islands")
    elif "Mountain" in file_name or "Cliff" in file_name or "Hill" in file_name or "Peak" in file_name or "Mount" in file_name:
        print("Matched with 'Mountain/Cliff/Hill/Peak")
        return os.path.join(base_folder, "Geography", "Mountains & Hills")
    elif "Lake" in file_name or "River" in file_name or "Canal" in file_name:
        print("Matched with 'Lake/River/Canal'")
        return os.path.join(base_folder, "Geography", "Rivers & Lakes")
    elif "Road" in file_name or "Avenue" in file_name:
        print("Matched with 'Road/Avenue'")
        return os.path.join(base_folder, "Geography", "Roads & Avenues")
    elif "Plain" in file_name or "Valley" in file_name or "Field" in file_name:
        print("Matched with 'Plain/Valley/Field'")
        return os.path.join(base_folder, "Geography", "Plains & Valleys")
    elif "Pass" in file_name:
        print("Matched with 'Pass'")
        return os.path.join(base_folder, "Geography", "Mountains & Hills")
    elif "Labyrinth" in file_name or "Maze" in file_name:
        print("Matched with 'Labyrinth/Maze'")
        return os.path.join(base_folder, "Geography", "Dungeons")
    elif "Mine" in file_name or "Cave" in file_name:
        print("Matched with 'Mine'")
        return os.path.join(base_folder, "Geography", "Caves & Mines")
    elif "(spell)" in file_name:
        return os.path.join(base_folder, "Spells")
    elif "(human ethnicity)" in file_name:
        return os.path.join(base_folder, "Culture", "Ethnicities")
    elif "(adventure path)" in file_name:
        return os.path.join(base_folder, "Trash")
    elif "Order of" in file_name or "Cult" in file_name:
        return os.path.join(base_folder, "Organizations")
    if "Capital:" in text:
        if "Nation" in text:
            print("Matched with 'Nation:' and 'Capital:'")
            return os.path.join(base_folder, "Geography", "Regions")
        else:
            print("Matched with 'Capital:'")
            return os.path.join(base_folder, "Geography", "Nations")
    elif "Nation:" in text or "Population:" in text or "Demographics:" in text:
        print("Matched with 'Nation:'")
        return os.path.join(base_folder, "Geography", "Cities")
    elif "Domains:" in text or "Domains (1E)" in text or "Worshipers" in text:
        print("Matched with 'Domains, Domains (1E) or Worshipers:'")
        return os.path.join(base_folder, "Religion", "Deities")
    elif "Race/Species:" in text or "Gender:" in text:
        print("Matched with 'Race/Species:'")
        return os.path.join(base_folder, "NPCs")
    elif "Headquarters:" in text:
        print("Matched with 'Headquarters:'")
        return os.path.join(base_folder, "Organizations")
    elif "Publisher:" in text:
        print("Matched with 'Publisher:'")
        return os.path.join(base_folder, "Books")
    elif "CR:" in text or "Level:" in text:
        print("Matched with 'CR:'"), True
        return os.path.join(base_folder, "Creatures")
    elif "Homepage:" in text or "Position:" in text:
        print("Matched with 'Homepage:' or 'Position:'")
        return os.path.join(base_folder, "Real ppl")
    elif "Captain(s):" in text or "Type: Starship" in text:
        print("Matched with 'Captain(s):'")
        return os.path.join(base_folder, "Ships")
    elif "Sphere:" in text or "Gravity:" in text or "Type: Planet" in text:
        print("Matched with 'Sphere:'")
        return os.path.join(base_folder, "Geography", "Planes & Planets")
    elif "Type: Wondrous item" in text:
        print("Matched with 'Type: Wondrous item'")
        return os.path.join(base_folder, "Wondrous Items")
    elif "Type: Major artifact" in text:
        return os.path.join(base_folder, "Items", "Artifacts", "Major Artifacts")
    elif "Type: Minor artifact" in text:
        return os.path.join(base_folder, "Items", "Artifacts", "Minor Artifacts")
    else:
        print("No match found")
        return base_folder
def move_notes(file_path, base_folder):
    with open(file_path, 'r', encoding='utf-8') as file:
        content = file.read()
    first_delimiter_index = content.find('---')
    second_delimiter_index = content.find('---', first_delimiter_index + 1)
    if first_delimiter_index != -1 and second_delimiter_index != -1:
        header = content[first_delimiter_index + 3:second_delimiter_index]
        print(f'Header: {header}')  # Debugging print statement
        file_name = os.path.basename(file_path)
        print(file_name)
        # destination_folder, call_level_folderizer = get_destination_folder(header, base_folder, file_name)
        destination_folder = get_destination_folder(header, base_folder, file_name)
        if not os.path.exists(destination_folder):
            os.makedirs(destination_folder)
        destination_file_path = os.path.join(destination_folder, file_name)
        if os.path.exists(destination_file_path):
            print(f'Overwriting existing file: {destination_file_path}')  # Debugging print statement
            if file_path != destination_file_path:
                os.remove(file_path)
                print(f'Removed source file: {file_path}')  # Debugging print statement
        else:
            shutil.move(file_path, destination_file_path)
            print(f'Moved file: {file_path} to {destination_file_path}')  # Debugging print statement
    else:
        print(f'Could not find two "---" delimiters in {file_path}')
        header = ''
        file_name = os.path.basename(file_path)
        print(file_name)
        destination_folder = get_destination_folder(header, base_folder, file_name)
        destination_file_path = os.path.join(destination_folder, file_name)
        if os.path.exists(destination_file_path):
            print(f'Overwriting existing file: {destination_file_path}')  # Debugging print statement
            if file_path != destination_file_path:
                os.remove(file_path)
                print(f'Removed source file: {file_path}')  # Debugging print statement
        else:
            shutil.move(file_path, destination_file_path)
            print(f'Moved file: {file_path} to {destination_file_path}')  # Debugging print statement
def level_folderizer(file_path, base_folder):
        with open(file_path, 'r', encoding='utf-8') as file:
            content = file.read()
        # Extract the front matter
        front_matter_pattern = re.compile(r'^---\n(.*?)^---', re.MULTILINE | re.DOTALL)
        match = front_matter_pattern.search(content)
        if match:
            front_matter = match.group(1)
            level = None
            # Check if the front matter contains a "Level" key
            level_pattern = re.compile(r'^Level:\s+(\d+)', re.MULTILINE)
            level_match = level_pattern.search(front_matter)
            if level_match:
                level = int(level_match.group(1))
            else:
                # If not, check if the front matter contains a "cr" key
                cr_pattern = re.compile(r'^CR:\s+(\d+)', re.MULTILINE)
                cr_match = cr_pattern.search(front_matter)
                if cr_match:
                    level = int(cr_match.group(1))
            if level is not None:
                folder_name = f"Level {level}"
                folder_path = os.path.join(base_folder, folder_name)
                # Create the folder if it doesn't exist
                if not os.path.exists(folder_path):
                    os.makedirs(folder_path)
                # Move the note to the folder
                new_path = os.path.join(folder_path, os.path.basename(file_path))
                os.rename(file_path, new_path)
                print(f'Moved {file_path} to {new_path}')
def process_all_files_in_base_folder(base_folder):
    for root, _, files in os.walk(base_folder):
        for file in files:
            if file.endswith('.md'):
                file_path = os.path.join(root, file)
                print(f'Processing file: {file_path}')  # Debugging print statement
                move_notes(file_path, base_folder)
                # time.sleep(0.2)
def process_files_in_base_folder(base_folder):
    for file in os.listdir(base_folder):
        file_path = os.path.join(base_folder, file)
        if os.path.isfile(file_path) and file.endswith('.md'):
            print(f'Processing file: {file_path}')  # Debugging print statement
            move_notes(file_path, base_folder)
def move_notes_with_keyword(base_folder, keyword, target_folder):
    files = os.listdir(base_folder)
    for file in files:
        if file.endswith('.md') and keyword in file:
            file_path = os.path.join(base_folder, file)
            print(f'Processing file: {file_path}')  # Debugging print statement
            destination_folder = os.path.join(base_folder, target_folder)
            if not os.path.exists(destination_folder):
                os.makedirs(destination_folder)
            destination_file_path = os.path.join(destination_folder, file)
            print(f'Destination file path: {destination_file_path}')  # Debugging print statement
            shutil.move(file_path, destination_file_path)
            print(f'Moved file: {file_path} to {destination_file_path}')  # Debugging print statement 
def save_image(url, base_url, output_dir):
    print(f"Downloading image from {url}...")
    response = requests.get(url)
    soup = BeautifulSoup(response.content, 'html.parser')
    original_file_div = soup.find('div', {'class': 'fullMedia'})
    if not original_file_div:
        print(f"Error: Could not find 'Original file' div on {url}")
        return None
    original_file_p = original_file_div.find('p')
    if not original_file_p:
        print(f"Error: Could not find 'Original file' link on {url}")
        return None
    relative_image_url = original_file_p.find('a').get('href')
    image_url = base_url + relative_image_url
    response = requests.get(image_url, stream=True)
    content_type = response.headers.get('content-type')
    if not content_type:
        print(f"Error: Could not get content type for {image_url}")
        return None
    ext = mimetypes.guess_extension(content_type)
    if not ext:
        print(f"Error: Could not guess file extension for {image_url}")
        return None
    filename = image_url.split('/')[-1].split('.')[0] + ext
    filepath = os.path.join(output_dir, filename)
    if os.path.exists(filepath):
        print(f"Image already exists at {filepath}. Skipping download...")
        return filepath
    try:
        with open(filepath, 'wb') as f:
            for chunk in response.iter_content(chunk_size=8192):
                if chunk:
                    f.write(chunk)
        return filepath
    except Exception as e:
        print(f"Error downloading image: {e}")
        return None
def image_processor(base_url, soup, processed_images, output_dir):
    for a in soup.find_all('a'):
        if 'href' not in a.attrs:
            continue
        link_text = a.get_text()
        link_url = urljoin(base_url, a['href'])
        image_page_url = "https://pathfinderwiki.com" + a['href']
        if "redlink" not in link_url:
            if link_url.endswith((".jpg", ".jpeg", ".png", ".gif", ".svg", ".webp", ".bmp", ".tiff", ".tif", ".jfif")):
                if image_page_url not in processed_images:
                    processed_images.append(image_page_url)
                    image_path = save_image(image_page_url, base_url, output_dir)
                    filename = image_path.split('\\')[-1]
                    if image_path:
                        a.replace_with(f"![[{filename}|right+hmed]] \n")
                else:
                    # Remove the duplicate image link
                    a.decompose()
            else:
                # Modified line to handle link_text different from link itself
                link_title = a['href'].replace('/wiki/', '')
                link_title_clean = re.sub(r'[^\w\s\-]', '', link_title).replace('_', ' ').replace('27', "'")
                link_text_clean = re.sub(r'[^\w\s\-]', '', link_text).replace('_', ' ').replace('27', "'")
                if link_text_clean != link_title_clean:
                    a.replace_with(f"[[{link_title_clean}|{link_text_clean}]]")
                else:
                    a.replace_with(f"[[{link_text_clean}]]")
        else:
            a.replace_with(link_text) 
def YAML_Creator(soup, base_url, processed_images, output_dir):
    # Store infobox tables
    table_right = soup.find_all('div', {'class': 'infobox'})
    yaml_output = "---\n"  # start of yaml output
    image_path = None  # Variable to store the image path
    # Process infobox key-value pairs
    for table in table_right:
        divs = table.find_all('div')
        for i in range(len(divs) - 1):
            if 'class' in divs[i].attrs and 'key' in divs[i]['class']:
                key = divs[i].text.strip()
                if key != 'Source':  # ignore 'Source' key
                    value = divs[i+1].text.strip()
                    if divs[i+1].find('table'):  # Check if the div contains a table
                        value_table = divs[i+1].find('table')
                        table_cells = value_table.find_all('td')
                        values = [cell.text for cell in table_cells if 'background-color: #9fc7fe' in cell['style']]
                        value = ', '.join(values)
                    yaml_output += f"{key}: {value}\n"
            elif divs[i+1].find('img'):  # Check if the div contains an image
                img = divs[i+1].find('img')
                image_url = urljoin(base_url, img['src'])
                # Check if the image has been downloaded
                filename = os.path.basename(image_url)
                if filename not in processed_images:
                    # Download the image
                    image_path = os.path.join(output_dir, filename)
                    with open(image_path, 'wb') as f:
                        response = requests.get(image_url, stream=True)
                        if response.ok:
                            response.raw.decode_content = True
                            shutil.copyfileobj(response.raw, f)
                            print(f"Image successfully downloaded: {filename}")
                        else:
                            print(f"Image could not be downloaded: {filename}")
                            image_path = None
    yaml_output += "---"  # end of yaml output
    return yaml_output, image_path  # Return the image path along with the yaml output
def YAML_Fixer(content):
    delimiter_pattern = r'---([\s\S]*?)---'
    extracted_content = re.findall(delimiter_pattern, content)
    ignore_keys = ['Cleric Alignments (1E)', 'Cleric Alignments (2E)']
    formatted_sections = []
    for section in extracted_content:
        formatted_section = []
        lines = section.split('\n')
        for line in lines:
            if ':' in line:
                key, value = line.split(':', 1)
                if key.strip() in ignore_keys:
                    formatted_key = ''.join(
                        word.capitalize() if word.lower() != "cr" else word.upper() for word in re.split(r'\s|/|\\|\(|\)', key) if word)
                    formatted_section.append(formatted_key + ': ' + value.strip())
                    continue
                formatted_values = []
                # Split values by ',', '/', '\', and two uppercase letters
                value_parts = re.split(r',\s*|/|\s*\\|\s*(?<=\w)(?=[A-Z])', value.strip())
                for part in value_parts:
                    if part and ':' not in part:  # Skip values that contain ":"
                        if 'CR:' in part:
                            formatted_part = part.replace('CR:', 'CR:').strip()
                        else:
                            formatted_part = part.strip().capitalize()
                        formatted_values.append(formatted_part)
                # Format the key name and remove '/' and '\'
                formatted_key = ''.join(
                    word.capitalize() if word.lower() != "cr" else word.upper()
                    for word in re.split(r'\s|/|\\|\(|\)', key)
                    if word)
                # Format values as per your requirement
                formatted_value = ', '.join(formatted_values) if formatted_values else ''
                formatted_section.append(f'{formatted_key}: {formatted_value}')
            else:
                formatted_section.append(line)
        formatted_sections.append('\n'.join(formatted_section))
    for idx, section in enumerate(extracted_content):
        content = content.replace(section, formatted_sections[idx])
    return content
def Infobox_Adder(content, image_path=None):
    # Check if there are at least two '---' delimiters
    if content.count('---') < 2:
        return
    parts = content.split('---')
    input_text = parts[1].strip()
    lines = input_text.split('\n')
    data = {}
    current_key = None
    for line in lines:
        if line.startswith('-'):
            if isinstance(data[current_key], str):
                data[current_key] = [data[current_key]]
            data[current_key].append(line.strip('-').strip())
        else:
            key, value = line.split(':', 1)
            current_key = key.strip()
            if current_key not in data:
                data[current_key] = value.strip() if not line.endswith(':') else []
    formatted_text = '> [!infobox]+\n'
    formatted_text += '> #  `= this.file.name`\n'
    if image_path:
        filename = image_path.split("\\")[-1]  # Get the image file name
        formatted_text += f'> ![[{filename}]]\n'
    else:
        formatted_text += '> ![[image.png|cover hsmall]]\n'
    formatted_text += '> ##### Stats\n'
    formatted_text += '> Type | Stat |\n'
    formatted_text += '> :---:|:---:|\n'
    for key, value in data.items():
        formatted_text += f'> **{key}** | `= this.{key}` |\n'
    result = parts[0] + '---\n' + parts[1] + '\n---\n\n' + formatted_text + '\n' + '---'.join(parts[2:])
    return result
#############################################################################

def decomposer(soup):
    # Remove specified elements
    table_right = soup.find_all('div', {'class': 'infobox'})
    if table_right:
        for table in table_right:
            table.decompose()

    references_header = soup.find('span', {'id': 'References'})
    if references_header:
        references_section = references_header.parent
        if references_section:
            references_section.decompose()

    external_links_header = soup.find('span', {'id': 'External_links'})
    if external_links_header:
        external_links_section = external_links_header.parent
        if external_links_section:
            external_links_section.decompose()

    references_links = soup.find('div', {'id': 'articleReferences'})
    if references_links:
        references_links.decompose()

    table_bottom = soup.find_all('table', {'class': 'navbox hlist'})
    if table_bottom:
        for table in table_bottom:
            table.decompose()

    div_bottom = soup.find_all('div', {'class': 'navbox'})
    if div_bottom:
        for table in div_bottom:
            table.decompose()

    print_footer = soup.find_all('div', {'class': 'printfooter'})
    if print_footer:
        for prints in print_footer:
            prints.decompose()

    toc = soup.find('div', {'id': 'toc'})
    if toc:
        toc.decompose()

    sup = soup.find_all('sup')
    if sup:
        for s in sup:
            s.decompose()

    for p in soup.find_all('p'):
        if p.text.startswith('For additional resources'):
            p.decompose()
def convert_to_markdown(html_content):
    soup = BeautifulSoup(html_content, 'html.parser')
    base_url = 'https://pathfinderwiki.com'
    processed_images = []
    yaml, image_path = YAML_Creator(soup, base_url, processed_images, output_dir)
    yaml = YAML_Fixer(yaml)
    decomposer(soup) # Tolgo tutti gli elementi che non voglio processare
    image_processor(base_url, soup, processed_images, output_dir) # Processo le immagini nella pagina TRANNE QUELLA NEL BOX
    for b in soup.find_all('b'):
        b.replace_with(f"**{b.get_text()}**")
    for i in soup.find_all('i'):
        i.replace_with(f"*{i.get_text()}*")
    for h1 in soup.find_all('h2'):
        h1.replace_with(f"\n## {h1.get_text()}\n")
    for h2 in soup.find_all('h2'):
        h2.replace_with(f"\n## {h2.get_text()}\n")
    for h3 in soup.find_all('h3'):
        h3.replace_with(f"\n### {h3.get_text()}\n")
    for h4 in soup.find_all('h4'):
        h4.replace_with(f"\n#### {h4.get_text()}\n")
    for h5 in soup.find_all('h5'):
        h5.replace_with(f"\n##### {h5.get_text()}\n")
    for ul in soup.find_all('ul'):
        new_ul = '\n'.join([f"> - {li.get_text()}" for li in ul.find_all('li')])
        ul.replace_with(new_ul)
    # Find the div with the specified class and the dl within it
    div_col = soup.find('div', class_='div-col columns column-width')
    dl = div_col.find('dl') if div_col else None
    # If the dl element is found, create the table
    if dl:
        # Initialize the table header and rows
        table_header = "| Term | Definition |\n|------|------------|\n"
        table_rows = []
        # Loop through dt and dd elements, creating rows for the table
        for dt, dd in zip(dl.find_all('dt'), dl.find_all('dd')):
            dt_text = dt.get_text().strip()
            dd_text = dd.get_text().strip()
            table_rows.append(f"| {dt_text} | {dd_text} |")
        # Combine the header and rows to create the Markdown table
        markdown_table = table_header + '\n'.join(table_rows)
        # Replace the dl element with the Markdown table
        dl.replace_with(markdown_table)
    # Let's get the text
    for p in soup.find_all('p'):
        p.replace_with(f"> {p.get_text()}")
    markdown_text = soup.get_text().strip()
    def fix_mixed_formatting(match):
        return match.group(1) + "***"
    markdown_text = re.sub(r'(^\*{3}[^*]+)\*$', fix_mixed_formatting, markdown_text, flags=re.MULTILINE)
    markdown_text = yaml + markdown_text
    markdown_text = Infobox_Adder(markdown_text, image_path)
    return markdown_text
def save_markdown(content, title, folder=output_dir):
    os.makedirs(folder, exist_ok=True)
    filename = f"{title.replace('/', '_').replace('_', ' ')}.md"
    filepath = os.path.join(folder, filename)
    if os.path.exists(filepath):
        print(f"File '{filename}' already exists. Skipping.")
        return
    with open(filepath, "w", encoding="utf-8") as f:
        f.write(content)
    print(f"Note saved to '{filepath}'.")
def sanitize_filename(title):
    invalid_chars = '\/:*?"<>|'
    for char in invalid_chars:
        title = title.replace(char, ' ')
    title = title.replace('_', ' ')
    return title
# Get a list of all existing file names already existing
existing_files = set()
for root, dirs, files in os.walk(base_folder):
    for file in files:
        if os.path.isfile(os.path.join(root, file)):
            existing_files.add(file.lower())
try:
    response = requests.get(url)
    if response.status_code != 200:
        print(f"Error: Status code {response.status_code} for {url}")
    else:
        soup = BeautifulSoup(response.content, "html.parser")
        content = soup.find('div', {'id': 'mw-content-text'})
        content_html = str(content)
        page_title = soup.find("h1").get_text()
        sanitized_title = sanitize_filename(page_title)
        file_name = f"{sanitized_title}.md"
        if file_name.lower() in existing_files:
            print(f"File '{file_name}' already exists. Skipping '{url}'")
        else:
            content_markdown = convert_to_markdown(content_html)
            save_markdown(content_markdown, sanitized_title, folder=base_folder)
            # Move the note to the correct destination folder
            note_path = os.path.join(base_folder, sanitized_title + ".md")
            move_notes(note_path, base_folder)
except Exception as e:
    print(f"Error processing {url}: {e}")

```