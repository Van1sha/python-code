class Employee:
    def __init__(self,name,salary):
        self.name=name
        self.salary=salary
    def displayEmployee(self):
        return f"name:{self.name} , salary:{self.salary}"
name=input("name: ")
salary=input("salary: ")
Emp_1=Employee(name,salary)
Emp_1.displayEmployee()
