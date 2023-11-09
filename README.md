# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open then required file by using the function"with"

Step 2:
Using split function to split the words.

### Step 3:
Finding the length of the words by using len() function.

### Step 4:
Calling the function and printing the number of words.
## PROGRAM:
```
n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
    for line in f:
        words=line.split()
        wordslen+=len(words)
print("Number of words:",wordslen)
```
### Input:

![Screenshot 2023-11-09 211349](https://github.com/sanjay5656/Word-count/assets/115128955/ebc2deff-537b-4063-ace0-e142a41277df)

### OUTPUT:

![Screenshot 2023-11-09 211422](https://github.com/sanjay5656/Word-count/assets/115128955/b623ad67-38a8-4f1b-8f90-69d053010704)

## RESULT:
Thus the program is written to find the word count from a text.
