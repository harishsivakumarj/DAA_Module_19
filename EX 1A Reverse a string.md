# EX 1A Reverse a String
## DATE:15/04/2025
## AIM:
Write a python program to implement linear search on the given tuple of float values.

## Algorithm
Read integer n and create an empty list tup.
Input n float numbers and append them to tup.
Read the float number x to search in tup.
Check each element in tup; if x is found, set a flag.
Print "Tuple: x found" if flag is set, otherwise print "Tuple: x not found".

## Program:
```
/*
Program to implement Reverse a String
Developed by: S Harish
Register Number: 212223040062
n = int(input())
tup = []
for i in range(n):
    tup.append(float(input()))
x=float(input())
f=0
for i in tup:
    if(i==x):
        f=1
        break
if f==1:
    print(f"Tuple: {x} found")
else:
    print(f"Tuple: {x} not found")
*/
```

## Output:

<img width="1131" height="688" alt="image" src="https://github.com/user-attachments/assets/feee05ee-5d42-4ea9-bbe2-83e91e1f2d74" />


## Result:
The program successfully reverses the input string using recursion. When the user provides an input string, the output displays the reversed version of the string
