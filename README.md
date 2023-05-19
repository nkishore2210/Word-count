# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
```
Program to count the words in a file
Developed by: N.Kishore
Register number: 212222240049

fname=input("Enter the file name:")
num_words=0
with open(fname,"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print("Number of words:",num_words)
```
### OUTPUT:

![Screenshot 2023-05-19 105002](https://github.com/nkishore2210/Word-count/assets/118707090/d88dc61d-b950-4f6b-939b-b5f84e3f8eec)

## RESULT:
Thus the program is written to find the word count from a text.
