```jupyter
import re


text = '''


'''

def add_greater_than(text):
    lines = text.split('\n')
    formatted_lines = ['>' + re.sub(' +', ' ', line) for line in lines]
    result = '\n'.join(formatted_lines)
    return result

    
formatted_text = add_greater_than(text)
print(formatted_text)



```
