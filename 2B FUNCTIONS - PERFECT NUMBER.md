# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

---

### ALGORITHM

1. Begin the program.
2. Read an integer input from the user and store it in n.
3. Initialize sum1 to 0 to store the sum of factors of n.
4. Use a for loop to iterate from 1 to n-1. If i is a factor of n (i.e., n % i == 0), add i to sum1.
5. After the loop, check if sum1 equals n. If true, print "The number is a Perfect number!". Otherwise, print "The number is not a Perfect number!".
6. Terminate the program.

---

### PROGRAM
```
#Reg.No: 212223090030
#Name: Vijayalakshmi M P
n=int(input())
sum1=0
for i in range(1, n):
    if(n % i == 0):
        sum1 = sum1 + i
if(sum1 == n):
    print("The number is a Perfect number!")
else:
    print("The number is not a Perfect number!")


```
### OUTPUT
<img width="1109" height="268" alt="image" src="https://github.com/user-attachments/assets/c2d882f2-aae9-42bd-87aa-f3b66dfd1df3" />

### RESULT
Thus a Python program to check if a number is a Perfect number using the concept of functions was executed and implemented successfully.


