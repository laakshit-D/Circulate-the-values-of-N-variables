# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program
### Step 2: 
Get the input from the user 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the number of rotation
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: Laakshit D
#RegisterNumber: 22000680
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![output](/image/Screenshot%20from%202022-12-24%2014-46-45.png)

## Result:
Thus the program is successfully executed
