# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the first file in read mode,
### Step 2: 
Open the second file in append mode.
### Step 3: 
Every word in first file is copied to second file using write().
### Step 4:  
close the first file.
### Step 5: 
close the second file.

## PROGRAM:
```
python program for copying the contents from one file to another file.
Developed by: LINGESWARAN K
RegisterNumber: 212222110022

f1=open("sample1.txt","r")
f2=open("sample2.txt","a")
for line in f1:
    f2.write(line)
f1.close()
f2.close()
```
### OUTPUT:
![image](https://github.com/Lingeswaran04/copy-file/assets/119103865/8d934c63-c607-4c97-b08b-fed2193f065a)

![image](https://github.com/Lingeswaran04/copy-file/assets/119103865/4a5cb0b3-8eae-4ac2-b83a-56108517479a)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
