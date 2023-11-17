# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get two values from the user
### Step 2: 
assign the value of second variable to a temporary variable.
### Step 3: 
define the formula Get the value from the user for the number of rotation
### Step 4: 
print the result Using the slicing concept rotate the list
### Step 5: 
finally print the result
## Program:
```
#Program to circulate N values.
#Developed by: GIFTSON RAJARATHINAM N
#RegisterNumber:212222233002
def circulate():
    a=eval(input())
    n=int(input())
    a=a[n: ]+a[ :n]
    print('After circulating the values are:',a)
```
## Output:
![image](https://github.com/gifty003/Circulate-the-values-of-N-variables/assets/145822352/c9ae8631-7827-4214-8db0-81811f3b8f34)

## Result:
Thus circulating the values of n  variables is successfully executed.
