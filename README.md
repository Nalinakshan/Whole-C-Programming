# 📘 C Programming Fundamentals: The All-in-One Sandbox

## 🚀 Overview

Welcome to **ZeroOfC**! This repository contains a single, comprehensive C source file (`main.c`) designed as a complete reference guide for learning the C programming language. 

It acts as a "living textbook," covering everything from basic "Hello World" outputs to complex concepts like pointers, structures, bitwise operations, and file handling.

**Author:** Nalinakshan  
**Language:** C (Standard C99/C11)

---

## ⚠️ Important Usage Instructions

**Please Read Before Running:**
To prevent execution conflicts (such as multiple infinite loops or conflicting input requests), **several sections of the code are commented out.**

The code is structured sequentially. To test a specific feature (e.g., the Number Guessing Game or String Functions), you must:

1.  Open the source file.
2.  **Uncomment** the specific block you wish to run.
3.  **Comment out** other interactive blocks to avoid clutter in the terminal.

---

## 📚 Topics Covered

This file is organized into distinct sections using separator lines (`//-----`). Below is a list of concepts implemented in this sandbox:

### 🔹 Basics & Data Types
* **Boilerplate:** Standard headers and `main` function structure.
* **Variables:** Initialization, declaration, and constants.
* **Data Types:** `int`, `float`, `char`, `double`, `bool`, and modifiers (`unsigned`, `long`, `short`).
* **Format Specifiers:** Controlling precision and alignment (e.g., `%.2f`, `%-10s`).

### 🔹 Operators & Math
* **Arithmetic:** `+`, `-`, `*`, `/`, `%`, `++`, `--`.
* **Assignment:** `+=`, `-=`, etc.
* **Logic:** `&&` (AND), `||` (OR), `!` (NOT).
* **Bitwise Operators:** `&`, `|`, `^`, `<<`, `>>` (Binary level manipulation).
* **Math Functions:** `sqrt()`, `pow()` (via `math.h`).

### 🔹 Control Flow
* **Conditional Statements:** `if`, `else if`, `else`.
* **Switch Cases:** Menu-driven logic (used in the Calculator mini-project).
* **Ternary Operator:** Short-hand `if/else`.

### 🔹 Loops
* **For Loops:** Standard iteration.
* **While / Do-While:** Input validation and repeated execution.
* **Nested Loops:** Creating patterns and grids.
* **Flow Control:** `break` and `continue`.

### 🔹 Arrays & Strings
* **1D & 2D Arrays:** Iterating through lists and matrices.
* **String Manipulation:** Custom logic vs. `<string.h>` functions (`strcpy`, `strlen`, etc.).
* **Sorting Algorithms:** Implementation of **Bubble Sort** for both integers and characters.

### 🔹 Advanced Concepts
* **Pointers:** Memory addresses, dereferencing, and pass-by-reference.
* **Memory Management:** Understanding `sizeof()` and memory addresses (`%p`).
* **Structs:** Defining `Students`, `User`, and `players`.
* **Typedefs & Enums:** Creating custom types and readable constants.
* **Random Numbers:** generating pseudo-random integers using `time(0)`.

### 🔹 File Handling (Commented Section)
* **I/O Operations:** Writing (`w`), Appending (`a`), and Reading (`r`) text files.
* **File Deletion:** Using `remove()`.

---

## 🛠️ Mini-Projects Included
Inside the code, you will find logic for several mini-projects:
1.  **Hypotenuse Calculator** (Math logic)
2.  **Circle Area Calculator** (Geometry)
3.  **Temperature Converter** (Celsius <-> Fahrenheit)
4.  **Basic Calculator** (Switch-case implementation)
5.  **Number Guessing Game** (Random number logic)

---

## 💻 How to Compile and Run

Ensure you have a C compiler installed (like GCC).

**1. Compile the code:**
```bash
gcc main.c -o output
