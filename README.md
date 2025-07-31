# Loops
# 🔁 Looping in C++

## 🎯 Aim
To understand and implement looping statements in C++ using:
- `for` loop  
- `while` loop

---

## 📌 Objectives
- Use loops to repeat a block of code.
- Practice using `for` and `while` loops in different situations.
- Understand loop structure, conditions, and counters.
- Solve simple problems using loops.

---

## 🧠 Theory

### 🔁 What is a Loop?
A loop is a control structure used to repeat a block of code multiple times until a specific condition is met. It helps in avoiding manual repetition of code and enhances efficiency.

### 🔹 Types of Loops in C++
- **For Loop** – Best suited when the number of iterations is known.
- **While Loop** – Used when the number of iterations is unknown or condition-based.

---

## 📊 Difference Between For and While Loop

| Feature           | For Loop                  | While Loop                   |
|------------------|---------------------------|------------------------------|
| Use Case         | Known repetition count     | Unknown repetition count     |
| Initialization   | Inside loop header         | Before loop starts           |
| Condition Check  | At start of each iteration | At start of each iteration   |
| Update Step      | Inside loop header         | Inside loop body             |
| Readability      | More compact               | More flexible for conditions |



## 🔄 Algorithms

### 🔢 Even Numbers from 0 to 10
- Start from 0.
- Increment by 2.
- Print each value until 10.

### 🔐 Password Verification
- Ask the user to set a password.
- Provide 3 attempts to re-enter the password correctly.
- On success, print a message and exit loop.
- On failure, reduce attempts and retry.

### 🔃 Reverse a Number
- Take a number.
- Extract digits one by one from the end.
- Construct the reversed number by multiplying and adding.
- Repeat until the original number becomes 0.

---

## 🖼️ Pattern Types (Loop-Based)

### 🌟 Star Patterns

- Right-Angled Triangle
- Inverted Right-Angled Triangle
- Mirrored Right-Angled Triangle
- Equilateral Triangle
- Inverted Equilateral Triangle
- Continuous Star Triangle
- Diamond Pattern
- Hourglass Pattern

### 🔢 Number Patterns

- Number Triangle (increasing sequence)
- Number Pyramid (same number per row)
- Mirrored Number Triangle (right aligned)
  

## 📐 Pattern Algorithms

### ⭐ 1. Right-Angled Triangle Star Pattern

**Algorithm:**
1. Start a loop from `i = 1` to `n` (rows).
2. For each row `i`, start a nested loop from `j = 1` to `i`.
3. Print a star (`*`) inside the inner loop.
4. After the inner loop ends, go to the next line.
5. Repeat until all rows are printed.

---

### 🔢 2. Number Triangle Pattern
**Algorithm:**
1. Initialize a counter variable to `1`.
2. Start a loop from `i = 1` to `n` (rows).
3. For each row `i`, run a nested loop from `j = 1` to `i`.
4. In the inner loop:
   - Print the current counter value.
   - Increment the counter by 1.
5. Move to the next line after inner loop ends.
6. Repeat for all rows.

---

## ✅ Conclusion
Looping is a powerful concept in programming that lets us repeat tasks with ease. By mastering `for` and `while` loops, we can solve mathematical problems, validate user inputs, and generate beautiful output patterns in C++.


