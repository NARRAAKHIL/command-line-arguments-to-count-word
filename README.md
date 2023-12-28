# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.
### Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
### Step 3:
Read the file using read() method.
### Step 4:
Use split() method to split the file content into words.
### Step 5:
Use len() to find the total words.
### Step 6:
Run the program to determine the number of words in the file created.

## PROGRAM:
```
'''
Developed by :narra akhil
Registered number : 23003406
'''
import sys
file= open(sys.argv[1])
data=file.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:

![image](https://github.com/NARRAAKHIL/command-line-arguments-to-count-word/assets/144979843/fe307bbb-2610-4203-b5fb-d7fe21243e5f)
![image](https://github.com/NARRAAKHIL/command-line-arguments-to-count-word/assets/144979843/4d1817de-d158-4d88-b4b8-c15beaaabd00)
![image](https://github.com/NARRAAKHIL/command-line-arguments-to-count-word/assets/144979843/cca36462-b300-48a6-b791-dd8781ad9333)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
