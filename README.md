# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys 
### Step 2: 
 open the file using sys function
### Step 3: 
create a variaable as a 
### Step 4:  
read the file and store it in variable
### Step 5: 
print the variable and call the file in the terminal
### Step 6: 
end the program
## PROGRAM:
```
'''Program to count the words using command line arrgument.
Developed by:SUNIL KUMAR T
RegisterNumber: 23001650
'''
import sys
f=open(sys.argv[1],"r")
a=f.read().split()
print(len(a))
```
### OUTPUT:
![output](/Screenshot%202023-07-26%20140806.png)
![output](/Screenshot%202023-07-26%20140953.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
