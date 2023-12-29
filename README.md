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
Read the file and store in a variable
### Step 3: 
Now create a new file in which we want to paste the content using write access mode
### Step 4:  
Use write function to copy the read file that has been stored in the variable.
### Step 5: 
the content in the original file will be copied in the new file
### Step 6: 
End the program
## PROGRAM:
``````
python
To write a program for copying the contents from one file to another file.
Developed by:GAYATHRI.K 
RegisterNumber:23013439

with open("f45.txt","r") as fp:
    x = fp.read()
with open("f44.txt","w") as fp1:
    fp1.write(x)
``````    

### OUTPUT:
![WhatsApp Image 2023-12-29 at 21 49 11_1f670b13](https://github.com/GAYATHRI-K06/copy-file/assets/145742742/a927047d-28a5-4634-83c6-69ad148c665d)
![WhatsApp Image 2023-12-29 at 21 50 52_2d0c3734](https://github.com/GAYATHRI-K06/copy-file/assets/145742742/663422e8-e8a2-4b4e-a792-ab0215309a5f)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
