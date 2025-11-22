# Exp.No:4c 
## EXCEPTION HANDLING-File Creation, Reading, and Merging Using Python File Handling

### AIM  
To write Python functions to create a file, read a file, and merge the contents of two files into a new output file using proper file-handling techniques.
### ALGORITHM
```
1.Open a file in write mode and write the given content to create a new file.
2.Open the first input file and read all its text.
3.Open the second input file and read its text.
4.Combine the text from both files into one string.
5.Open the output file in write mode and write the merged content into it.
6.Open any file in read mode to read its full content and return it.
```
### PROGRAM

```
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)
def merge_files(file1_path, file2_path, output_file_path):
    with open(file1_path,'r') as file1:
        with open(file2_path,'r') as file2:
            content1=file1.read()
            content2=file2.read()
            new=content1+content2
    with open(output_file_path,'w') as file:
        file.write(new)
def read_file(file_path):
    with open(file_path, 'r') as file:
        return file.read()
```

### OUTPUT
<img width="1197" height="602" alt="image" src="https://github.com/user-attachments/assets/4ad2036b-884e-4bbd-8ac9-1ce7884c0102" />


### RESULT
The program successfully creates files, reads data from them, and merges the contents of two files into a new output file. It demonstrates proper use of file handling functions such as reading, writing, and combining file data.
