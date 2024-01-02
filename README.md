# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import numpy as np

### Step 2: 
 enter the input value

### Step 3: 
write python program for getting the word count from the contents of the file using command line arguments

### Step 4:  
run the program

### Step 5: 
get the output

### Step 6: 
completed successfully

## PROGRAM:
```
Developed by: JESU SMARTIA A
Register no: 212223110016

import sys
count= 0
with open(sys.argv[1],'r') as file:
    for line in file:
        word=line.split()
        count+=len(word)
        
print("word count in file = ",count)
```    
### OUTPUT:



## RESULT:
Thus the program is written to find the word count from a text.
