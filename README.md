# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Decleare number of words is 0
### Step 2: 
open it with txt file 
### Step 3: 
Give range for i
### Step 4:  
Then nxt split the words
### Step 5: 
count the number of words
### Step 6: 
Giving print statement for getting output
## PROGRAM:
```
#Program to find the Word Count
#Developed by : JANANI S
#Register Number : 23013409
num=0
with open("file1.txt","r") as f1:
  for i in f1:
    word=i.split()
    num += len(word)
print("The number of words are in the file is ",num)
```
### OUTPUT:
![image](https://github.com/SJananisenthilkumar/Word-count/assets/144871139/c264de03-4cfb-4f6e-a77a-411b46c10c68)

## RESULT:
Thus the program is written to find the word count from a text.
