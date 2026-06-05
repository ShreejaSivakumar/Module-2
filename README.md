# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
a = 16
print(bin(a))
```


<img width="167" height="76" alt="Screenshot 2026-06-05 183553" src="https://github.com/user-attachments/assets/edc0aa10-5d8c-4a25-a7b7-a813e06346ab" />

## Output

<img width="117" height="27" alt="Screenshot 2026-06-05 183557" src="https://github.com/user-attachments/assets/02202862-31f3-4a6e-9d0f-9e9463b55a97" />

## Result
Thus To write a Python program to convert the number 16 into its binary representation using built-in Python functions. Hence the code has been executed successfully.
------------------------------------------------------------------------------------------
# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def result(a, b):
    print(a % b)

a = int(input())
b = int(input())
result(a, b)
```
<img width="328" height="140" alt="Screenshot 2026-06-05 183736" src="https://github.com/user-attachments/assets/81272a6e-3ca0-4196-8f19-ed3f53106074" />


## Output
<img width="256" height="96" alt="Screenshot 2026-06-05 183742" src="https://github.com/user-attachments/assets/80b33925-b0b3-416a-ae6f-2a9dfcafbdf3" />

## Result
Thus To write a Python program that defines a function which accepts two values and returns their modulo using the % operator. Hence the code has been executed successfully
-----------------------------------------------------------------------------------------
# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
a = int(input())
b = int(input())

f = lambda a, b: a + b

print(f(a, b))
```
<img width="312" height="97" alt="Screenshot 2026-06-05 183910" src="https://github.com/user-attachments/assets/965fb490-c726-4bbf-8d6b-e88323149b35" />

## Output
<img width="248" height="105" alt="Screenshot 2026-06-05 183913" src="https://github.com/user-attachments/assets/05dcf2f2-8691-454e-a0b5-3c83e860229d" />

## Result

Thus To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum. Hence the code has been executed successfully.

-----------------------------------------------------------------------------------------------
# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

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
```
def factorial(n): 
    result = 1 
    for i in range(2, n+1): 
        result *= i 
    return result
def combination(n, k): 
    return factorial(n) // (factorial(k) * factorial(n - k))
rows = int(input("Enter the number of rows: "))
for i in range(rows): 
    print(' ' * (rows - i - 1), end='')
    for j in range(i + 1):
        print(combination(i, j), end=' ')
    print()
```
<img width="387" height="210" alt="Screenshot 2026-06-05 184207" src="https://github.com/user-attachments/assets/6277e9ab-e94b-40a7-ba7c-aa373855b0a7" />


## Sample Output
<img width="257" height="148" alt="Screenshot 2026-06-05 184211" src="https://github.com/user-attachments/assets/f5c2ca2a-3292-4021-9476-f39179663d69" />

## Result
Thus To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user. Hence the code has been executed successfully.
------------------------------------------------------------------------------------

## Loops in Python: Palindrome Number Checker

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
```
num = int(input("Enter a number: ")) 
temp = num 
rev = 0

while temp > 0: 
    rev = (10 * rev) + temp % 10 
    temp = temp // 10

if rev == num: 
    print("The number is a palindrome.") 
else: 
    print("The number is not a palindrome.")
```
<img width="330" height="233" alt="Screenshot 2026-06-05 184338" src="https://github.com/user-attachments/assets/995f0298-307b-4416-b236-df01d61b8545" />


## Output
<img width="246" height="82" alt="Screenshot 2026-06-05 184343" src="https://github.com/user-attachments/assets/95d4e839-fa8d-4aa6-a33f-7c9f1e4fc58d" />

## Result
Thus To write a Python program that checks whether a given number is a palindrome using loops. Hence the code has been executed successfully.

