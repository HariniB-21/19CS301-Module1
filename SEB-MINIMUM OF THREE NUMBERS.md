# Experiment No: 5 – SEB-Maximum of Three Numbers

## AIM  
To write a Python program to find the maximum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare `num1`, `num2`, and `num3` to find the largest number:  
   - If `num1` is greater than or equal to both `num2` and `num3`, then `num1` is the maximum.  
   - Else, if `num2` is greater than or equal to both `num1` and `num3`, then `num2` is the maximum.  
   - Otherwise, `num3` is the maximum.  
4. Print the maximum value along with the input numbers in the format:  
   `"The maximum of num1, num2, num3 is max_num."`  
5. Terminate the program.

## PROGRAM
```python
# Reg.No-212222020008
# Name-Harini B
# Write your code here

a = int(input())
b = int(input())
c = int(input())
d = [a,b,c]
e = max(d)
print("The maximum of {}, {}, {} is {}".format(a,b,c,e))


## OUTPUT
![Screenshot 2025-05-03 144452](https://github.com/user-attachments/assets/00d9c959-fbe7-4090-aa44-3ac288294003)

## RESULT
   Thus the Python program to find the maximum between three integer numbers using a conditional expression (Ternary operator) was executed successfully.
