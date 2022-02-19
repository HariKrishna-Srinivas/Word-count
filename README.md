# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1: Decare a variable count equal to 0.

Step 2: Open the required text file in read mode as text.(any name can be used).

Step 3: Look until variable i in file text.

Step 4: Declare variable word = i.split().

Step 5: Process count+=len(word) End loop.

Step 6: Print the value of count,which has the number of words in the file.

## PROGRAM:
~~~
#Developed by:- M.Hari krishna
#Reference Number:- 21002044

count =0
with open('recordTest','r') as test:
    for i in test:
        word = i.split()
        count+=len(word)
print('The number of words in the file',test.name,'are :',count)

### OUTPUT:
~~~
<img width="740" alt="at" src="https://user-images.githubusercontent.com/94882905/154804043-f90cdeaa-bf35-490f-9821-4727b2fe514e.png">
<img width="728" alt="at1" src="https://user-images.githubusercontent.com/94882905/154804058-d32e0596-658e-4795-9e54-4e1036100d0b.png">





## RESULT:
Thus the program is written to find the word count from a text.
