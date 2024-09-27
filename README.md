# swapping_variables
## AIM:
To write a python program for swapping of two values
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Input the first integer n (the first number to swap).
### Step 2: 
Input the second integer b (the second number to swap).
### Step 3: 
Create a temporary variable called temp.
### Step 4:  
Store the value of n into temp (this saves the first number for later).
### Step 5: 
Assign the value in temp to b (now b gets the original value of n).
### Step 6: 
Output the swapped values of n and b (show the result to the user).
End the program

## PROGRAM:
 n=int(input("enter the first number:"))

 b=int(input("enter the second number:))
 
 temp=0
 
 temp=n
 
 n=b
 
 b=temp
 
 print("Swapped values are:",n,b)
 

## RESULT:
Now the variables are swapped succesfully.
