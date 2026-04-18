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
n=int(input())
for i in range(n):
    print(" "*(n-i),end="")
    for j in range(i+1):
        f=1
        for k in range(1,j+1):
            f=f*(i-k+1)//k
        print(f,end=" ")
    print()
```
## Sample Output
<img width="372" height="295" alt="image" src="https://github.com/user-attachments/assets/58f807dc-b1b3-4fb8-8e2e-d7645d3d9c10" />

## Result
Thus the program that generates Pascal's Triangle using numbers.
The number of rows is accepted from the user has been executed successfully.
