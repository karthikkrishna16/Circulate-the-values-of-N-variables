# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: Get the two values from the user
### Step 2: In circular swapping, the value of the first variable is assigned to the second variable
### Step 3: Get the value from the user for the number of rotation
### Step 4: Using the slicing concept rotate the list
Using the slicing concept rotate the list

### Step 5: Print both the values it would be circulated 
### Step 6: End the program

## Program:
#Program to circulate N values.
#Developed by:KARTHIK KRISHNA
#RegisterNumber:23014165
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n: ]+l[ :n]
    print("After circulating the values are:",l)
## Output:![Screenshot 2023-11-23 134837](https://github.com/karthikkrishna16/Circulate-the-values-of-N-variables/assets/148514663/0a73ebec-679a-4bd2-9e25-dad01981347a)
## Result:Thus the Circulation of the values of N variables are successfully executed
