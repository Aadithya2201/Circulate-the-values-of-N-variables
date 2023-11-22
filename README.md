# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a user defined function
### Step 2: 
Get the variables from user to enter inside the list
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
After rotating the variables , store the rotated variables in a seperate list
### Step 6: 
At last , print the list of rotated variables 
## Program:
```
#Program to circulate N values.
#Developed by: Aadithya
#RegisterNumber:23006361
def circulate():
    list1=eval(input())
    a=int(input())
    l2=[]
    for i in range(a,len(list1)):
        l2.append(list1[i])
    for i in range(a):
        l2.append(list1[i])
    print("After circulating the values are:",l2)
```

## Output:
![Screenshot 2023-11-22 135003](https://github.com/Aadithya2201/Circulate-the-values-of-N-variables/assets/145917810/312befdf-b131-4eb0-b420-dfe380b5b0ba)



## Result:
Thus,the program to circulate the n variables using function concept successfully executed.
