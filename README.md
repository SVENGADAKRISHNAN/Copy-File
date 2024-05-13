# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Load the CSV into a DataFrame.

### Step 2: 
 Print the number of contents to be displayed using df.head().


### Step 3: 
The number of rows returned is defined in Pandas option settings.

### Step 4:  
Check your system's maximum column with the pd.options.display.max_column statement.

### Step 5: 
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
`````
#Program for copying the contents from one file to another file
#Developed by: S.VENGADA KRISHNAN
#Register Number: 212223110061
with open ("File1.txt",'r') as fp:
    msg1=fp.read()
with open ("copy.txt",'w') as fp1:
    fp1.write(msg1)
```````

### OUTPUT:

![image](https://github.com/SVENGADAKRISHNAN/Copy-File/assets/147473084/c5886a32-15ef-4f6c-b84f-e4795b73691b)
![image](https://github.com/SVENGADAKRISHNAN/Copy-File/assets/147473084/0a1a07fb-106c-460b-92ea-b039281eba4f)
![image](https://github.com/SVENGADAKRISHNAN/Copy-File/assets/147473084/186fc9df-9cf8-4ac5-93d9-126a0f2a1993)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
