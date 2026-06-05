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
