Python3

#Comments

Data Types: 
    Numbers: int, float
    Strings
    Boolean
    List
    Tuple
    Dictionary
    Set

File I/O: 
    #1: 
        x = open("my_file.txt", "w")
        x.write("Hello world")
        x.close()
    #2: 
        with open("file.txt", "w") as x: 
            x.write("Hello world")

If, Elif, else

Functions: 
    def function()->Type: 
        return #Optional
        pass
    Tuple unpacking
    def func(): 
        return (a, b)
    a, b = func()

For loops: 
    #1: 
        for i in range(n)
    #2: 
        for item in items

Lambda: 

OOP: 
class Dog(): 
    def __init__(self, variable): 
        self.varirable = variable
        pass

#Can modify __len__, __str__, etc

try: 
    pass
except #Error code: 
    pass

Python Decorator

Python Generator

Modules: 
    Collections