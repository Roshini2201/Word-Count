# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Declare number of words as 0.

### Step 2: 
Open the txt file for reading

### Step 3: 
Create a range function for the file.

### Step 4:  
Then next, split the words by space.

### Step 5: 
Count the number of words

### Step 6: 
End the program by printing the output.

## PROGRAM:
```
# Program to find the word count
# Developed by: ROSHINI.S
# register number: 212223240142
num=0
with open("/content/story.txt","r") as f1:
  for i in f1:
    word=i.split()
    num+=len(word)
print("The number of words in the file is ",num)
```
### OUTPUT:

![Screenshot 2024-05-08 175849](https://github.com/Roshini2201/Word-Count/assets/154105318/6fa28eea-60d0-46fd-9297-53f724d27dcf)

## RESULT:
Thus the program is written to find the word count from a text.
