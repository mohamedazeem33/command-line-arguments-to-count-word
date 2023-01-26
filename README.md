# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import the sys module

### Step 2: 
pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
 
### Step 3: 
read the file using read() method.

### Step 4:  
use split() method to split the file content into words

### Step 5: 
use len() to find the total words.

### Step 6: 
Run the program to determine the number of words in the file created. 

## PROGRAM:
```python
#program for getting the word count from the contents of a file using command line arguments
#developed by : MOHAMED AZEEM N
#reference no : 22007405

import sys
count=0
with open(sys.argv[1],'r') as file:
    for line in file:
        word= line.split()
        count += len(word)
print("program is developed: MOHAMED AZEEM N")
print("word count in file = ",count)
```

### OUTPUT:

![python exp 5b](https://user-images.githubusercontent.com/121040764/214796528-579b1063-a0e8-42c9-976c-a75a0fb2a4ef.jpg)

![python exp 5b 2nd photo](https://user-images.githubusercontent.com/121040764/214796751-218be8f3-6ac8-4bfb-982c-9d550cacfe4c.jpg)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
