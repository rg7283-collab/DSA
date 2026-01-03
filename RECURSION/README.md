# 🔹 Recursion – DSA in C

This folder contains **fundamental recursion problems** implemented in **C language**.  
These problems help in understanding **recursive thinking**, **base cases**, and  
**problem decomposition**, which are essential for **DSA**, **interviews**, and  
**Advanced Programming Practice (APP)** coursework.

---

## 📌 List of Problems Covered

### 1️⃣ Factorial of a Number Using Recursion
**Problem:**  
Compute the factorial of a given number using recursion.

**Approach:**  
- Base case: `0! = 1`  
- Recursive case: `n × factorial(n − 1)`

**Time Complexity:** O(n)  
**Space Complexity:** O(n)

---

### 2️⃣ Fibonacci Series Using Recursion
**Problem:**  
Generate the Fibonacci series up to a given number of terms using recursion.

**Approach:**  
- Base cases: `F(0) = 0`, `F(1) = 1`  
- Recursive case: `F(n) = F(n − 1) + F(n − 2)`

**Time Complexity:** O(2ⁿ)  
**Space Complexity:** O(n)

> ⚠️ Note: Recursive Fibonacci is used for learning recursion and is not optimized.

---

### 3️⃣ Power of a Number
**Problem:**  
Calculate the power of a number using recursion.

**Approach:**  
- Base case: exponent `0` returns `1`  
- Recursive case: `x × power(x, n − 1)`

**Time Complexity:** O(n)  
**Space Complexity:** O(n)

---

### 4️⃣ Sum of Digits Using Recursion
**Problem:**  
Find the sum of digits of a given number recursively.

**Approach:**  
- Base case: when number becomes `0`  
- Recursive case: last digit + recursive call

**Time Complexity:** O(d)  
**Space Complexity:** O(d)  
(`d` = number of digits)

---

### 5️⃣ Generate All Subsets (Subsequences)
**Problem:**  
Generate all possible subsets (subsequences) of a given string or array.

**Approach:**  
- Use include/exclude recursion  
- Print subsequence at base condition  

**Time Complexity:** O(2ⁿ)  
**Space Complexity:** O(n)

---

## 🛠️ Language Used
- **C Programming Language**

---

## 📁 Recommended Folder Structure
