# Exp.No:4b 
## DICTIONARY - Exception Handling and Number Validation in Python
### AIM  
To write a Python program that checks whether the user-entered value is an even or odd number and handles invalid (non-numeric) inputs using try–except.

### ALGORITHM
```
1.Start the program.
2.Use a try block and read an input from the user.
3.Convert the input into an integer using int(x).
4.If conversion succeeds:
  Check whether the number is even using b % 2 == 0.
  If true, print "You entered even number".
  Else, print "An odd number".
5.If an error occurs during conversion (non-numeric input), the except ValueError block runs and displays "Enter only number".
6.End the program.
```
### PROGRAM

```
try:
    x=input()
    b=int(x)
    if b%2==0:
        print("You entered even number")
    else:
        print("An odd number")
except ValueError:
    print("Enter only number")
```

### OUTPUT
<img width="1192" height="361" alt="image" src="https://github.com/user-attachments/assets/e96f0a42-1d70-41ba-a8a5-fb7345dd4352" />

### RESULT
The program successfully checks if the input is even or odd. If the user enters something other than a number, the program handles the error gracefully and displays a helpful message.
