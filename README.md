# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create source file, the file you want to copy.

### Step 2: 
Now, create destination file, the file where you want to paste your copied file.
 
### Step 3: 
Open source file and read it. Store contents in a variable

### Step 4:  
Open destination file and write contents into this file. 

### Step 5: 
Manually open destination file to view the copied contents.

### Step 6: 
End program.

## PROGRAM:
```
#Program to copy file into another file
#Developed by: Cynthia Mehul J
#Register Number: 23009725

with open("source.txt","r") as f1:
    data=f1.read()
with open("destination.txt","w") as f2:
    f2.write(data)
```

### OUTPUT:
![label](/SourceFile.jpg)

![label](/Program.jpg)

![label](/DestinationFile.jpg)

## RESULT:
Thus the program is written to copy the contents from one file to another file.