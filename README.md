# 1. Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
a=int(input())
z=bin(a)
print(z)
```
## Output
![image](https://github.com/user-attachments/assets/7405381c-6750-4f69-b32d-cf55396e8655)

## Result
Thus, the python program was executed successfully

# 2. Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program

Add code Here
def result(a,b):
        return a%b
try:
    a=int(input())
    b=int(input())    
    
    if b==0:
        print("a is not allowed to divide by b")
    else:
        modulo=result(a,b)
        print("modulo is",modulo)
except value:        
           print("please enter the correct value")
## Output
![image](https://github.com/user-attachments/assets/6154b4c0-d1b3-41cc-9c1b-b346b34d96bf)

## Result
Thus, the python program was executed successfully

# 3. Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
Add code here
```
a=int(input())
b=int(input())
c=int(input())
f=a+b+c
print(f)
```
## Output
![image](https://github.com/user-attachments/assets/33f53250-0661-4037-9871-8dcc32832f33)

## Result
Thus, the python program was executed successfully

# 4. Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
Add Code Here
a=int(input())
for i in range(a):
    
    for j in range(a-i-1):
        print(end=" ")
    for m in range(i+1):          
             ncr=1
             if(i>0):
                ncr=1
                for k in range(1,m+1):
                     c=(i-k+1)/k
                     ncr=ncr*c
             print(int(ncr), end=" ")
    print("")
## Sample Output
![Screenshot 2025-04-29 113959](https://github.com/user-attachments/assets/17390b90-cac6-4e6a-8dc8-01cb1085fa2e)
## Result
Thus, the python program was executed successfully

## 5.Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
Add code Here
```
num=int(input())
rev=0
temp=num

while temp>0:
    rem=temp%10
    rev=rev*10+rem
    temp//=10
    
if rev==num:
        print(f"The given number {num} is a Palindrome")
else:
        print(f"The given number {num} is not a palindrome")
```
## Output
![438599393-545c0656-ce02-45fd-9eaa-49b335d6826c](https://github.com/user-attachments/assets/b9987620-397d-4a01-9100-6307f3d3d0af)

## Result
Thus, the python program was executed successfully



