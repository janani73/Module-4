# Exp.No:4e 
## SEB - Using Lambda Function to Perform an Arithmetic Expression in Python



### AIM  
To write a Python program that takes three numbers as input and evaluates an expression using a lambda function.

### ALGORITHM

```
1.Start the program.
2.Accept the first number from the user and convert it to an integer; store it in variable x.
3.Accept the second number from the user, convert it to an integer, and store it in y.
4.Accept the third number from the user, convert it to an integer, and store it in z.
5.Define a lambda function f that takes three parameters and computes the expression:
  divide the first number by 10,
  divide the second number by 2,
  multiply the result with the third number,
  then add both parts.
6.Call the lambda function f(x, y, z) to evaluate the expression.
7.Display the final calculated result to the user.
8.End the program.
```

### PROGRAM

```
x=int(input())
y=int(input())
z=int(input())
f=lambda x,y,z:(x / 10) + (y / 2) * z
print(f(x,y,z))
```

### OUTPUT

<img width="1201" height="440" alt="image" src="https://github.com/user-attachments/assets/a9ff53db-5623-4fc3-b02e-39d05758cd9d" />

### RESULT
The program successfully takes three numbers, processes them using a lambda function, and displays the final calculated output.
