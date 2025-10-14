# Exp.No:23  
## Multiple Inheritance

---

### AIM  
To write a Python program to get the name, attendance, and ID of a student and check if they are eligible for the next module using multiple inheritance. If attendance > 80, the student is eligible; otherwise, not eligible.

---

### ALGORITHM

1. Define the `Student` class.
2. Inside the `Student` class, define the `__init__` method (constructor). The `__init__` method accepts two parameters: `name` and `student_id`.
    - Inside the `__init__` method: Assign the value of `name` to `self.name` and `student_id` to `self.student_id`.
3. Define the `get_student_info` method inside the `Student` class:
    - This method should return a string formatted with `self.name` and `self.student_id`.
4. Define the `Attendance` class, which inherits from the `Student` class.
5. Inside the `Attendance` class, define the `__init__` method (constructor).
    - The `__init__` method accepts three parameters: `name`, `student_id`, and `attendance`.
    - Inside the `__init__` method: Call the parent class constructor `super().__init__(name, student_id)` to initialize `name` and `student_id`. Assign the value of `attendance` to `self.attendance`.
6. Define the `check_eligibility` method inside the `Attendance` class:
    - If `self.attendance` is greater than 80, return a formatted string indicating the student is eligible for the module exam.
    - Otherwise, return a formatted string indicating the student is not eligible for the module exam.
7. Prompt the user to enter the `name` (as a string), `student_id` (as an integer), and `attendance` (as an integer).
8. Create an instance `student` of the `Attendance` class, passing the entered `name`, `student_id`, and `attendance` to the constructor.
9. Call the `check_eligibility` method on the `student` object and print the result.
10. Terminate the program.

---

### PROGRAM

```
Reg No-212222060174
Name-Pavithra.S
class value():
    def __init__(self,name,no,a,b,c,d):
        self.name=name
        self.no=no
        self.a=a
        self.b=b
        self.c=c
        self.d=d
    def display(self):
        print("Name: ",self.name,"Rollno: ",self.no,"Total Marks out of 400: ",self.a+self.b+self.c+self.d)
name=input()
no=int(input())
a=int(input())
b=int(input())
c=int(input())
d=int(input())
s=value(name,no,a,b,c,d)
s.display()

```

### OUTPUT

<img width="1177" height="334" alt="image" src="https://github.com/user-attachments/assets/5b8db1a8-9caa-4e01-8111-f90445c60776" />

### RESULT

Thus the program that demonstrates to get the name,mark and id of the student has been implemented and executed successfully.


