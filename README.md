# Loops
# 🔁 Looping Statements in C++

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

## 📘 Theory

### 🔁 What is a Loop?
- Repeats a block of code multiple times.
- Saves time and avoids manual repetition.

### 🔹 Types of Loops in C++
- `for` loop
- `while` loop

---

### ✅ For Loop

Best when the number of repetitions is **known**.

```cpp
for (initialization; condition; update) {
    // code to repeat
}
✅ While Loop
Used when repetitions are unknown.

cpp
Copy
Edit
while (condition) {
    // code to repeat
}
📊 Difference Between For and While Loop
Feature	for Loop	while Loop
Use Case	Known repetition count	Unknown repetition count
Initialization	Inside loop header	Before loop
Condition Check	At start of each iteration	At start of each iteration
Update Step	Inside loop header	Inside loop body
Readability	Compact	More flexible for complex cases

💻 Programs and Outputs
1️⃣ Print Even Numbers from 0 to 10 (Using for loop)

for (int i = 0; i <= 10; i += 2) {
    cout << i << endl;
}
2️⃣ Print "SIT" 5 Times (Using for loop)

for (int i = 1; i <= 5; i++) {
    cout << "SIT" << endl;
}
3️⃣ Password Verification (Using while loop)

#include <iostream>
#include <string>
using namespace std;

int main() {
    string password, input;
    int attempts = 3;

    cout << "Set your password: ";
    cin >> password;

    cout << "\n---- PASSWORD VERIFICATION ----" << endl;

    while (attempts > 0) {
        cout << "Re-enter your password: ";
        cin >> input;

        if (input == password) {
            cout << "\nPassword verification successful!\n";
            break;
        } else {
            attempts--;
            cout << "You have " << attempts << " chances left\n";
        }
    }

    return 0;
}
4️⃣ Reverse a Number (Using while loop)

int num = 9073363;
int reversed = 0;

while (num != 0) {
    int digit = num % 10;
    reversed = reversed * 10 + digit;
    num /= 10;
}
cout << "Reversed number: " << reversed;
🔢 Pattern Printing
⭐ Right-Angled Triangle

*
**
***
****
*****
⭐ Inverted Right-Angled Triangle

*****
****
***
**
*
⭐ Mirrored Right-Angled Triangle
    *
   **
  ***
 ****
*****
⭐ Equilateral Triangle

    * 
   * * 
  * * * 
 * * * * 
* * * * * 
⭐ Inverted Equilateral Triangle

* * * * * 
 * * * * 
  * * * 
   * * 
    * 
⭐ Equilateral Triangle (Continuous Stars)
    *
   ***
  *****
 *******
*********
💎 Diamond Pattern

    *
   * *
  * * *
 * * * *
* * * * * 
 * * * * 
  * * * 
   * * 
    * 
⌛ Hourglass Pattern

 * * * * *
  * * * *
   * * *
    * *
     *
    * *
   * * *
  * * * *
 * * * * *
🔢 Number Patterns
🔹 Number Triangle

1
2 3
4 5 6
7 8 9 10
11 12 13 14 15
🔹 Number Pyramid

1
2 2
3 3 3
4 4 4 4
5 5 5 5 5
🔹 Mirrored Number Triangle

    1
   23
  345
 4567
56789
🔠 Alphabet Patterns
🔤 Alphabet Pyramid (Continuous)

A
BC
DEF
GHIJ
KLMNO
🔤 Alphabet Pyramid (Same Letter per Row)

A
BB
CCC
DDDD
EEEEE
🔷 Half Diamond Pattern

*
**
***
****
*****
****
***
**
*
🔷 Half Diamond (Mirrored)

    *
   **
  ***
 ****
*****
 ****
  ***
   **
    *
