# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the first file in read mode
### Step 2: 
 Open the second file in append mode
### Step 3: 
Every word in first file is copied to second file using write()
### Step 4:  
close the first file
### Step 5: 
close the second file
## PROGRAM:
```
python program for copying the contents from one file to another file.
Developed by:b.barathraj
RegisterNumber: 22008848
f1=open("sample1.txt","r")
f2=open("sample2.txt","a")
for line in f1:
    f2.write(line)
f1.close()
f2.close()
```
### OUTPUT:
![5c text](https://user-images.githubusercontent.com/121490575/215137762-c798c729-d1c9-44ea-bc47-e48df528ae3d.png)
![5c otpt](https://user-images.githubusercontent.com/121490575/215137854-e4044a17-ae96-4f61-ae7f-1679dcc9a2ac.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
