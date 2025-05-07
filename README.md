# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define a function named circulate that takes no arguments.
### Step 2: 
Inside the function, use input to get a string representation of a list from the user and evaluate it to get the actual list.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the circulated list l with the message "After circulating the values are:"

## Program:
```
# Developed by: M.Krithika Lakshmi
# Register no: 212224230134

def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:] + l[:n]
    print("After circulating the values are:",l)

```
## Output:

![Screenshot 2025-05-07 151906](https://github.com/user-attachments/assets/9cacf188-f2a5-428f-a15e-cded668693d3)

## Result:
Hence,the values are circulated successfully.
