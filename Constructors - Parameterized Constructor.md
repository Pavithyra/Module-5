# Exp.No:21  
## Constructors - Parameterized Constructor

---

### AIM  
To write a Python code to create a class for a person with a parameterized constructor, which will take the `name` and `userid` of the person as parameters and print the `userid` of the person.

---

### ALGORITHM

1. Begin the program.  
2. Define a `person` class.  
3. The `person` class should have a parameterized `__init__` method that accepts two parameters: `name` and `userid`.  
4. Inside the `__init__` method, assign the `name` to `self.name` and the `userid` to `self.userid`.  
5. Print the `self.userid`.  
6. Prompt the user to enter their `name` (string) and `userid`.  
7. Create an instance `s1` of the `person` class by passing the entered `name` and `userid` to the constructor.  
8. Terminate the program.

---

### PROGRAM

```
class person:
    def __init__(self,id,name):
         self.id=id
         self.name=name
    def display(self):
        print("Hello my id is :",id)
        print("My name is :",name)
id=int(input())
name=input()
c=person(name,id)
c.display()
```

### OUTPUT

<img width="822" height="208" alt="image" src="https://github.com/user-attachments/assets/8b3f87c8-f1ea-44e8-996a-15b4b60d0f22" />


### RESULT

Thus a python program to create a class for a person with a parameterized constructorhas been successfully implemented.
