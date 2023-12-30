# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:
### Step 1:
Mount your colab with your drive

### Step 2:
Open your text file in python code runner.

### Step 3:
Read the file and split the words separately using split().

### Step 4:
Count the number of words in text file using for() loop.

### Step 5:
End the program
## PROGRAM:
```python
#Program to for getting the word count from a text.
#Developed by:ARAVIND KUMAR SS
#Register Number:23004721
from google.colab import drive
drive.mount('/content/drive')

f=open('/content/aravind.txt','r')
b=f.read()
d=0
c=b.split(' ')
for i in c:
  d=d+1
print('The number of words:',d)
```
### OUTPUT:
![5a 1](https://github.com/aravindkumar23004721/Word-count/assets/148962674/6036765b-2a6a-4696-ac1d-21f0c3957631)
![5a 2](https://github.com/aravindkumar23004721/Word-count/assets/148962674/9280808b-0fc2-45a2-86f6-eac929ee9265)





## RESULT:
Thus the program is written to find the word count from a text.
