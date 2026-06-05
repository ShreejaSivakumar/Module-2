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
