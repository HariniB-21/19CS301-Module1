# 19CS301-Module1
### Register No - 212222020008
### Name - Harini B

# ExNo: 1.1 - Python Basics - Printing Multiline String
### AIM: To Create a python program to print the string in multiline.

### ALGORITHM  
STEP1: Define a string to be printed in a single line.
STEP2: Define a string that will be split into multiple lines with indentation on the second line.
STEP3: Use the `print()` function to display the strings.
STEP4: Terminate the program.

### PROGRAM
```
a=("I am a string literal\n... has more than one\n... line\n....placed inside triple single quotes")
b=("I am a string literal\n... has more than one\n... line\n....placed inside triple double quotes")
print(a)
print(b)
```
### Output
![image](https://github.com/user-attachments/assets/f18a737f-bfa8-453d-b2dd-128683f0ff65)

### RESULT:Thus the python program to print the string in multiline was executed successfully.

# ExNo: 1.2 - Data Types – Printing Integer Literals
### AIM: To write a Python program to print the following integer literals: 12.

### ALGORITHM  
STEP1: Begin the program.  
STEP2: Initialize the integer literals 12  
STEP3: Use the `print()` function to display the numbers 12 
STEP4: Terminate the program.

### PROGRAM
```python
# Reg.No-212222020008
# Name-Harini B
# Write your code here

a = 12
print(a)

```
### OUTPUT
![image](https://github.com/user-attachments/assets/e73fd9ec-ea9c-4b1d-b54e-38c0f09e9973)

### RESULT: Thus the Python program to print the following integer literals: 12 was executed sucessfully.

# ExNo: 1.3 -Varibles and Expressions, Operators - python program for bitwise shift operators on the user given integers
### AIM: To Write a python program for bitwise shift operators on the user given integers

### ALGORITHM
STEP1: Start
STEP2: Input an integer a
STEP3: Input an integer b
STEP4: Perform right shift operation:
STEP5: Calculate a >> b (shift bits of a to the right by b positions)
STEP6: Print the result
STEP7: Perform left shift operation:
STEP8: calculate a << b (shift bits of a to the left by b positions)
STEP9: Print the result
STEP10: End

### PROGRAM
```python
# Reg.No-212222020008
#Name-Harini B
#Write your code here
a=int(input())
b=int(input())
print(a>>b)
print(a<<b)
```
### OUTPUT
![image](https://github.com/user-attachments/assets/3d5930ff-dd06-4143-bd9a-d88521937c4e)

### RESULT: Thus a python program for bitwise shift operators on the user given integers was executed successfully.

# ExNo: 1.4 – Conditional Statements- divisible by 11 0r not
### AIM: To Write a Python program to read a number and check whether the number is divisible by 11 or not using  if else

### ALGORITHM  
STEP1:  Algorithm to Check if a Number is Divisible by 11
STEP2: Start
STEP3: Input a number a from the user.
STEP4: Set b = 11.
STEP5: Check if a % b == 0 (i.e., check if the remainder when a is divided by 11 is zero).
STEP6: If True, then:
STEP7: Print "a is divisible by 11".
STEP8: Else:
STEP9: Print "a is NOT divisible by 11".
STEP10: End

### PROGRAM
```python
# Reg.No-212222020008
# Name-Harini B
# Write your code here

a=int(input())
b=11
if a%b==0:
    print(a,"is divisible by 11")
else:
    print(a,"is NOT divisible by 11")
   
```
### OUTPUT
![image](https://github.com/user-attachments/assets/40fd119a-0628-461b-9cc9-9778a5b3a7e6)

### RESULT: Thus the Python program to read a number and check whether the number is divisible by 11 or not using  if else was implemented and executed successfully

# ExNo: 1.5 – SEB-Maximum of Three Numbers
### AIM: To write a Python program to find the maximum between three integer numbers using a conditional expression (Ternary operator).

### ALGORITHM  
STEP1: Begin the program.  
STEP2: Read the three numbers: `num1`, `num2`, and `num3` from the user.  
STEP3: Compare `num1`, `num2`, and `num3` to find the largest number:  
   - If `num1` is greater than or equal to both `num2` and `num3`, then `num1` is the maximum.  
   - Else, if `num2` is greater than or equal to both `num1` and `num3`, then `num2` is the maximum.  
   - Otherwise, `num3` is the maximum.
STEP4: Print the maximum value along with the input numbers in the format:  
   `"The maximum of num1, num2, num3 is max_num."`
STEP5: Terminate the program.

### PROGRAM
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
```
### OUTPUT
![image](https://github.com/user-attachments/assets/dcb513c0-adfc-40dc-ae0e-90a8f9d45f49)

### RESULT: Thus the Python program to find the maximum between three integer numbers using a conditional expression (Ternary operator) was executed successfully.
