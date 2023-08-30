
```jupyter
import re

text ='''



'''

def remove_text_within_parentheses(text):
    # This regular expression pattern matches text within parentheses
    pattern = r'\(.*?\)'
    
    # The re.sub function replaces any matches with an empty string
    cleaned_text = re.sub(pattern, '', text)
    
    return cleaned_text

# Test the function
cleaned_text = remove_text_within_parentheses(text)
cleaned_text = cleaned_text.replace('[', '[[').replace(']',']]')

print(cleaned_text)
```