# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

---

### ALGORITHM

1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(n)` with the following steps:  
    - Initialize a variable `factor_sum` to 0.  
    - Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.  
    - If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.

---

### PROGRAM
```

x=int(input())
y=int(input())
if(x<y):
    print(x,"is smaller than",y)
else:
    print(y,"is smaller than",x)

```
### OUTPUT
<img width="959" height="273" alt="image" src="https://github.com/user-attachments/assets/ff55e767-49c7-40b3-90d6-ef4cb32a00f0" />

### RESULT
Thus a a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function was executed successfully.
