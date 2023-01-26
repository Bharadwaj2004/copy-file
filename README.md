# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.
### Step 2: 
Read the file and store in a variable.
### Step 3: 
Now create a new file in which we want to paste the content using write access mode.
### Step 4:  
Use write function to copy the read file that has been stored in the variable.
### Step 5: 
The content in the original file will be copied in the new file.
### Step 6: 
End the program.
## PROGRAM:
```python
# Developed By: b.venkata Bharadwaj
# Reference number: 22003979
with open("copy.txt", "r") as firstfile:
    with open("text.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
```
### OUTPUT:
![WhatsApp Image 2023-01-26 at 2 52 33 PM](https://user-images.githubusercontent.com/119560345/214800679-ec15aac7-0abf-479e-b43b-a7fbb88c8f21.jpeg)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
