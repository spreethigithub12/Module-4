# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS

### AIM  
To write a Python program to perform addition and division operations using a class. The class should be named `Saveetha`, and the function names should be `setvalues` (to set `a` and `b` values), `add`, and `div`. The program should handle the following cases:  
- `choice 1` → Perform addition  
- `choice 2` → Perform division  
- `choice 0` → Exit  
- For other choices, print 'Invalid choice'

### ALGORITHM

1. Begin the program.  
2. Create a class `Saveetha`.  
3. Define the following methods inside the `Saveetha` class:  
   - `__init__(self)`: Initializes `a` and `b` to zero.  
   - `setvalues(self, a, b)`: Sets the values of `a` and `b`.  
   - `add(self)`: Performs the addition operation.  
   - `div(self)`: Performs the division operation. If `b` is zero, returns an error message for division by zero.  
4. Create a `main()` function.  
5. Take input from the user for the values of `a` and `b` using `setvalues(a, b)` method.  
6. Use a `while True` loop to repeatedly ask the user for a choice:  
   - If the choice is 1, call the `add()` method and print the result.  
   - If the choice is 2, call the `div()` method and print the result. Handle division by zero.  
   - If the choice is 0, print "Exiting!" and exit the loop.  
   - If the choice is not 1, 2, or 0, print "Invalid choice".  
7. Terminate the program.
8. 
### PROGRAM

```

Reg.No: 212222060182
Name: Preethika S

class cse:
    def __init__(self, a, b):
        self.a=a
        self.b=b
    def mod(self):
        return self.a%self.b
    def div(self):
        return self.a//self.b

a=int(input())
b=int(input())
obj=cse(a, b)
obj.mod()
obj.div()
choice=1
while choice!=0:
    choice=int(input())
    if choice==1:
        print("Result: ", obj.mod())
    elif choice==2:
        print("Result: ", obj.div())
    else:
        print("Exiting!")

print()

```

### OUTPUT
<img width="543" height="338" alt="image" src="https://github.com/user-attachments/assets/d89e1576-3b94-4f3d-abf6-41cdeb5cb0c1" />

### RESULT
Thus the Python program to perform addition and division operations using a class was implemented and executed successfully.
