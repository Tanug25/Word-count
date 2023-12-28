# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it inn text mood.
### Step 2: 
 Read the text using read() function.
### Step 3: 
Split the text using space separator.We assume that words in a sentence are seperated by a space character.
### Step 4:  
The length of the split list should equal the numbers of words in the text file.
### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
End the program.
## PROGRAM:
Developed by:Tanushree A
Registered number:23004953

def wordcount(filename):
    count=0
    with open(filename,"r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
     print("Total number of word:",count)
     filename=input("Enter Filename:")
     wordcount(filename)
  
### OUTPUT:

![word count op 1](https://github.com/Tanug25/Word-count/assets/138849166/4466e488-90a0-4865-b768-879b2218074f)
![word count op2](https://github.com/Tanug25/Word-count/assets/138849166/4cefc633-58de-4459-96fb-d965696cf835)


## RESULT:

Thus the program is written to find the word count from a text.
