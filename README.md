# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.

### Step 2:
Give a new file name to create a copy of a file content.

### Step 3:
Read the file and close the file.

### Step 4:
Now write the content in the new file.

### Step 5:
When done print"File copied successfully".

### Step 6:
End of the program

## PROGRAM:
```
#Developed by: kabilan T
#Register Number: 212222230059

with open("text1.txt", 'r') as fp:
    msg=fp.read()
with open("copy.txt", 'w') as fp1:
    fp1.write(msg)
```

### OUTPUT:

![Screenshot 2024-05-11 173641](https://github.com/Aravindan2006/Copy-File/assets/151760062/8949552f-4ae6-4105-8e01-4a95d3ae5f4a)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
