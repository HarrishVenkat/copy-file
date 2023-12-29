# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file
### Step 2: 
 Write some lines in that file.
### Step 3: 
Create a python file.

### Step 4:  
Write a code to copy the content of the file to a new file
### Step 5: 
Run the program
### Step 6: 
Display the output.
## PROGRAM:
```
Developed by:Harrish Venkat V
Register No.:23013973

def copy(filename,newfile):
with open(filename,'r') as fp:
with open(newfile,'w') as fp1:
data1=fp.read()
fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)

```

### OUTPUT:
![image](https://github.com/HarrishVenkat/copy-file/assets/144979588/7f8d8991-6716-471e-b35d-4b04d001b1fb)

![image](https://github.com/HarrishVenkat/copy-file/assets/144979588/92935f7b-d742-45c6-b2e1-edea6267063a)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
