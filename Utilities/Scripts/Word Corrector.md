## All files in a folder and subfolders

```jupyter
import os
import re

def search_and_replace_in_file(file_path, search_text, replace_text):  
    with open(file_path, 'r', encoding='utf-8') as file:  
        content = file.read()  
  
    updated_content = re.sub(re.escape(search_text), replace_text, content)  
  
    if content != updated_content:  
        with open(file_path, 'w', encoding='utf-8') as file:  
            file.write(updated_content)  


def process_files_in_directory(directory, search_text, replace_text):  
    for root, dirs, files in os.walk(directory):  
        for file in files:  
            if file.endswith('.md'):  
                file_path = os.path.join(root, file)  
                search_and_replace_in_file(file_path, search_text, replace_text)  

############################################################################

obsidian_vault_directory = "H:\\Altri computer\\Il mio computer\\Pathfindero\\World\\Geography\\Cathedrals & Temples"                                       
search_text = 'tag: #🕍'  
replace_text = 'tag: 🕍'  
process_files_in_directory(obsidian_vault_directory, search_text, replace_text)   
print('Done')   

```

## Single file

```jupyter
import os 
import re

def search_and_replace_in_file(file_path, search_text, replace_text):  
    with open(file_path, 'r', encoding='utf-8') as file:  
        content = file.read()  
  
    updated_content = re.sub(re.escape(search_text), replace_text, content)  
  
    if content != updated_content:  
        with open(file_path, 'w', encoding='utf-8') as file:  
            file.write(updated_content)  
  
def process_single_file(file_path, search_text, replace_text):  
    if file_path.endswith('.md'):  
        search_and_replace_in_file(file_path, search_text, replace_text)

############################################################################

if __name__ == '__main__':  
    obsidian_vault_directory = "C:\\Vaults\\Life"                                         
    search_text = '**Laminar**'  
    replace_text = '**[[Laminar]]**'  
    process_single_file(obsidian_note_path, search_text, replace_text)                  

```

