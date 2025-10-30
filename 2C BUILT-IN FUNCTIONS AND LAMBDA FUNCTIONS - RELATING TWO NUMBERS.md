# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM  
To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

---

### ALGORITHM

1. Begin the program.  
2. Use `eval()` to get two numbers (`num1` and `num2`) from the user.  
3. Define a lambda function `max` that takes two arguments `x` and `y`.  
4. The lambda function compares the numbers and prints:
   - If `x > y`, then it prints: "`num2` is smaller than `num1`".
   - Otherwise, it prints: "`num1` is smaller than `num2`".
5. Call the lambda function by passing `num1` and `num2` as arguments.  
6. Terminate the program.

---

### PROGRAM
```
#Reg.No:212223060086
#Name:Harish kumar P

i=int(input())
j=int(input())

f = lambda a, b: a*b

print(f(i, j))

```

### OUTPUT
![Screenshot 2025-04-27 141552](https://github.com/user-attachments/assets/aee43018-ee24-4820-bc5c-1197b7d1fba5)

### RESULT
a function which takes two arguments: a and b and returns the multiplication of them: a*b. Assign it to a variable named: f. using python has been implemented successfully.
