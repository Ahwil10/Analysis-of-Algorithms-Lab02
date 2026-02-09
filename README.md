# Analysis of Algorithms - Lab 02

[cite_start]This repository contains the solutions for Lab 02 of the Analysis of Algorithms course at **Yachay Tech University**. [cite: 3, 4] [cite_start]It includes mathematical proofs for recurrences and C++ implementations for the Fibonacci sequence. [cite: 5, 18]

## 1. Recurrence Solutions
[cite_start]The PDF file included in this repository contains the step-by-step hand-written solutions and induction proofs for the following recurrences: [cite: 5, 6, 26]
* [cite_start]**1.1:** $T(n) = 3T(n/2) + n$ [cite: 7]
* [cite_start]**1.2:** $T(n) = 3T(n-1) + 4T(n-2)$ [cite: 8, 12]
* [cite_start]**1.3:** $T(n) = 5T(n-1) - 6T(n-2)$ [cite: 9, 12]
* [cite_start]**1.4:** $x(n) = 2x(n-1) + 4x(n-2)$ [cite: 10, 12]

## 2. Fibonacci Sequence Implementation
[cite_start]The Fibonacci sequence is generated using the recurrence $T(n) = T(n-2) + T(n-1)$. [cite: 18, 22]

### 2.1 Iterative Approach
[cite_start]The iterative solution uses a loop to calculate terms, ensuring $O(n)$ time complexity and $O(1)$ space complexity. [cite: 23]

### 2.2 Recursive Approach
[cite_start]The recursive solution follows the mathematical definition directly, though it has an exponential time complexity $O(2^n)$. [cite: 24]

## How to Run
To compile and run the programs on **Linux (Fedora)**, use `g++`:

```bash
# Compile the program
g++ -o fibonacci main.cpp

# Run the program
./fibonacci
