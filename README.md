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
