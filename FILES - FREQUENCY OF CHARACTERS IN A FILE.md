# Exp.No:4d
## FILES - Calculating the Area of a Circle Using a Class and Method in Python

### AIM  
To write a Python program that uses a class method to compute the area of a circle based on the radius entered by the user.

### ALGORITHM

```
1.Import the math module to use the constant π.
2.Define a class cse with a method mech that calculates area using the formula π × r².
3.Accept a floating-point radius from the user.
4.Create an object of the class cse.
5.Call the mech method with the radius to compute and print the area of the circle.
```

### PROGRAM

```
import math
class cse:
    def mech(self,radius):
        area=math.pi*radius*radius
        print(f"Area of circle: {area:.2f}")
r=float(input())
obj=cse()
obj.mech(r)
```


### OUTPUT

<img width="1202" height="327" alt="image" src="https://github.com/user-attachments/assets/065e29f0-3c6b-45fa-8976-24fd0ae66572" />

### RESULT
The program successfully takes the radius as input, creates a class object, and displays the area of the circle using the class method.
