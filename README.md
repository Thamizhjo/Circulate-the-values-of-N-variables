# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
get the Function definition
### Step 2: 
Get the value from the user for the number of rotation
### Step 3: 
Using the slicing concept rotate the list
### Step 4:
Elements from the start up to index n-1 are moved to the end of the new list
### Step 5:
print("After circulating the values are:", result)
### Step 6: 
End program
## Program:
```
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```

## Output:
![output](/python%202.png)

## Result:
To circulate the n variables using function concept
