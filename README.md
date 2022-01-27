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
~~~
## DEVELOPED BY: R.Vijay
## REFERENCE NUMBER: 21500269
num_words =0
file1 = open("text.txt", "r")
print(file1.read())

with open('text.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
~~~

### OUTPUT:
![output]()



## RESULT:
Thus the program is written to find the word count from a text.
