# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
create a function to circulate the variables
### Step 2: 
initialize a list from the user using eval
### Step 3: 
Get the value from the user for the number of rotation 
### Step 4: 
using the slicing concept rotate the list
### Step 5: 
we do this initializing a variable 1 and adding the values before index and after the index in the list
### Step 6: 
print the value of 1
## Program:
###Program to circulate N values.
####Developed by: B.KRISHNAKANTH
###RegisterNumber:23006762
```python
def circulate():
    l=list(eval(input()))
    n=int(input())
    l1=l[n:]+l[:n]
    print("After circulating the values are:",l1)
```


## Output:![Screenshot 2023-10-24 160640](https://github.com/Krishnakanth23006762/Circulate-the-values-of-N-variables/assets/138849446/51afaa77-ff7f-4f6a-863b-672ff7c6d2e0)


## Result: 
The python program for Circulate-the-values-of-N-variables is execueted successful.
