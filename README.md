# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
 Open then required file by using thefunction"with"
### Step 2: 
 Using split function to split the words.
### Step 3: 
Finding the length of the words by using len() function.
### Step 4:  
Calling the function and printing the number of words.

## PROGRAM:
```
#Developed by: Vasundra sri R
#Register No: 212222230168
n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
for line in f:
words=line.split()
wordslen+=len(words)
print("Number of wordds:",wordslen)
```
### OUTPUT:
![Screenshot 2023-06-01 114324](https://github.com/vasundrasriravi/Word-count/assets/119393983/08062f57-c033-4a5f-bec0-adf42b7e7a99)



## RESULT:
Thus the program is written to find the word count from a text.
