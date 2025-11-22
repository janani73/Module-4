# Exp.No:4a
## CLASS AND OBJECTS - Measuring Memory Size of Dictionaries Using getsizeof() in Python
### AIM  
Measuring Memory Size of Dictionaries Using getsizeof() in Python
### ALGORITHM
```
1.Start the program.
2.Import the getsizeof function from the sys module.
3.Create three dictionaries:
  dic1 with key–value pairs of characters and numbers.
  dic2 with key–value pairs of string keys and names.
  dic3 with numeric keys and animal names.
4.Use getsizeof(dictionary_name) to find the memory size of each dictionary in bytes.
5.Print the size of each dictionary using formatted output.
6.End the program.
```
### PROGRAM

```
from sys import getsizeof
dic1 = {"A": 1, "B": 2, "C": 3}
dic2 = {"Geek1": "Raju", "Geek2": "Nikhil", "Geek3": "Deepanshu"}
dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}
print(f"Size of dic1: {getsizeof(dic1)}bytes")
print(f"Size of dic2: {getsizeof(dic2)}bytes")
print(f"Size of dic3: {getsizeof(dic3)}bytes")
```

### OUTPUT

<img width="1202" height="325" alt="image" src="https://github.com/user-attachments/assets/2893df41-70e8-49d2-8e38-947c0e76491b" />


### RESULT
The program successfully calculates and displays the memory size (in bytes) occupied by dic1, dic2, and dic3. The output shows that the size varies based on the number of items and the type of data stored.
