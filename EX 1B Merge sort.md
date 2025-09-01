# EX 1B Merge Sort
## DATE:
## AIM:
Write a Python Program to print factorial of a number recursively.


## Algorithm
Read an integer num from the user.
If num < 0, print "Invalid input! Please enter a positive number."
If num == 0, print "Factorial of number 0 is 1".
Otherwise, call recursive_factorial(num) to calculate the factorial recursively.
Print "Factorial of number num = result".

## Program:
```
/*
Program to implement Merge Sort
Developed by: S Harish
Register Number:212223040062
def recursive_factorial(n):
  if n==0:
      return 1
  else:
      return n*recursive_factorial(n-1)
 
num = int(input())
if num < 0:
  print("Invalid input ! Please enter a positive number.")
elif num == 0:
  print("Factorial of number 0 is 1")
else:
  print("Factorial of number", num, "=", recursive_factorial(num))
*/
```

## Output:

<img width="998" height="301" alt="image" src="https://github.com/user-attachments/assets/1a9c53d4-9841-4cc9-abb2-3d6d75c867cd" />


## Result:
The program successfully sorts the first half of the given array using merge sort. where only the first half is sorted, and the second half remains unchanged.
