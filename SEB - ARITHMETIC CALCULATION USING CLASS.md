# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM  
To write a Python program to perform addition and division operations using a class. The class should be named `Saveetha`, and the function names should be `setvalues` (to set `a` and `b` values), `add`, and `div`. The program should handle the following cases:  
- `choice 1` → Perform addition  
- `choice 2` → Perform division  
- `choice 0` → Exit  
- For other choices, print 'Invalid choice'

---

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

---

### PROGRAM

```
class cse:
def mul(self,a,b):
self.a=a
self.b=b
print("Result: ",a*b)
def div(self,a,b):
self.a=a
self.b=b
print("Result: ",a//b)

z=cse()
a=int(input())
b=int(input())
q=False
while q==False:
x=int(input())
if x==1:
z.mul(a,b)
elif x==2:
z.div(a,b)
elif x==0:
print("Exiting!")
q=True
break;
else:
print("Invalid choice")
q=True
break;


```

### OUTPUT
![image](https://github.com/user-attachments/assets/1a4d292e-d649-4270-8acc-11169ffe9ef4)

### RESULT
Thus the Python program to perform addition and division operations using a class. The class should be named Saveetha, and the function names should be setvalues (to set a and b values), add, and div is successfully implemented and executed.
