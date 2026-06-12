# For Loop Demonstration in C++

A simple C++ program demonstrating the use of a `for` loop to print text along with incrementing numbers.

This project is beginner-friendly and helps understand loop execution, increment operations, and output formatting in C++.

---

## 📌 Features

* Uses a `for` loop
* Demonstrates loop incrementing by `5`
* Prints text with numeric values
* Displays the final value of the loop variable after loop termination

---

## 🛠️ Technologies Used

* C++
* Standard Input/Output (`iostream`)

---

## 📂 Program Logic

The program:

1. Runs a loop starting from `1`
2. Increments the value by `5` after each iteration
3. Prints:

   * `"Rishab"` followed by the current value of `i`
4. Prints the final value of `i` after the loop ends

---

## 📸 Screenshot

<img width="1438" height="325" alt="Screenshot 2026-06-12 075956" src="https://github.com/user-attachments/assets/00518738-ded3-4c64-a85a-0c3f3a8c2d1e" />

Example folder structure:

```txt id="jlwm41"
project-folder/
│
├── main.cpp
├── README.md
└── screenshots/
    └── output.png
```

---

## 💻 Source Code

```cpp id="wy1zqd"
#include<iostream>
using namespace std;

int main() {

    int i;

    cin >> i;

    for (i = 1; i <= 25; i = i + 5) {
        cout << "Rishab" << i << endl;
    }

    cout << i << endl;

    return 0;
}
```

---

## ▶️ How to Run

1. Compile the program:

```bash id="r2s63o"
g++ main.cpp -o main
```

2. Run the executable:

```bash id="2k73ur"
./main
```

---

## 📸 Example Output

```txt id="s6q6g5"
Rishab1
Rishab6
Rishab11
Rishab16
Rishab21
26
```

---

## 📖 Learning Concepts

This project helps beginners understand:

* `for` loops in C++
* Loop conditions
* Increment operations
* Variable scope and updates
* Console output formatting

---

## ⚠️ Note

Remove the extra semicolon after the `#include` line for cleaner syntax:

```cpp id="q4ecr7"
#include<iostream>
```

Instead of:

```cpp id="h65m53"
#include<iostream>;
```

---

## 👨‍💻 Author

Developed as a beginner-friendly C++ practice project for learning loops and iteration.
