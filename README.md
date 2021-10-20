# CMPINF0010

## Our Team
- Jacob Emmerson
- Kareem Mohsen
- Will Smithgall


## Our Program
---
The program takes input from the user, getting their name and age. After, it will use that information and greet the user.

## Installation and Use
---
- To install this, all you need to do is download the python file attached to this repository
- To use this, you simply need to run the program and follow the prompts on your screen from there
---
For usage in JupyterLab:
- Open a new JupyterLab terminal 
- In the terminal, run
```text
git clone https://github.com/jacobemmerson/CMPINF0010
```

## Code
---
```python
name = input("What is your name?") #User input for the name 
age = int(input("What is your age: ")) #User input for the age

#This will greet the user, saying hello to them and telling them their age
print("Hello {}, you are {} years old").format(name, age)
```
