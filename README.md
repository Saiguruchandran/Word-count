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
## DEVELOPED BY: SAI GURUCHANDRAN
## REFERENCE NUMBER: 23014037
num_words =0
file1 = open("nature.txt", "r")
with open('nature.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
### OUTPUT:
![WhatsApp Image 2024-01-02 at 23 19 28_fd488971](https://github.com/Saiguruchandran/Word-count/assets/144870946/1c730483-db7b-40a2-9f33-016faf0e9c4a)



## RESULT:
Thus the program is written to find the word count from a text.
