# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the input as file name from the user.
### Step 2: 
assign number of words = 0 
### Step 3: 
open file and read it.
### Step 4:  
split the words separately by using split(
### Step 5: 
calculate the sum of the words in file.
### Step 6: 
Print the number of words.
## PROGRAM:
```
fname=input("enter the file name:")
num_words=0
with open(fname,'r') as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print("Number of words:",num_words) 
```

### OUTPUT:
![ex 5a](https://github.com/Safeeq-Fazil/Word-count/assets/118680361/68936d60-a57a-4931-a30a-64b7b7644dfd)



## RESULT:
Thus the program is written to find the word count from a text.
