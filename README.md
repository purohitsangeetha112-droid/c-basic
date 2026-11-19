# C Programming – Learning Journey

<p align="center">
  <img src="https://img.shields.io/badge/Language-C-blue.svg" alt="C Language">
  <img src="https://img.shields.io/badge/Level-Beginner-green.svg" alt="Beginner">
  <img src="https://img.shields.io/badge/Status-Active%20Learning-orange.svg" alt="Active Learning">
</p>

## About This Repository

Welcome to my **C Programming Learning Repository**!

This repository documents my journey of learning C programming from the fundamentals. It includes theoretical concepts, practical coding exercises, problem-solving activities, and sample outputs.

The main objective of this repository is to develop strong programming fundamentals, improve logical thinking, and gain hands-on coding experience.

Each topic is organised with explanations, examples, source code, and outputs to make the learning process structured and easy to follow.

---

# Table of Contents

1. [Introduction to C Programming](#1-introduction-to-c-programming)
2. [Features of C](#2-features-of-c)
3. [Structure of a C Program](#3-structure-of-a-c-program)
4. [Variables and Constants](#4-variables-and-constants)
5. [Data Types](#5-data-types)
6. [Operators](#6-operators)
7. [Input and Output](#7-input-and-output)
8. [Conditional Statements](#8-conditional-statements)
9. [Looping Statements](#9-looping-statements)
10. [Pattern Programming](#10-pattern-programming)
11. [Arrays](#11-arrays)
12. [Practical Programs](#12-practical-programs)
13. [Repository Structure](#13-repository-structure)
14. [Learning Progress](#14-learning-progress)
15. [Skills Developed](#15-skills-developed)
16. [Future Learning Goals](#16-future-learning-goals)
17. [Author](#17-author)

---

## 1. Introduction to C Programming

C is a general-purpose, procedural programming language developed by Dennis Ritchie at Bell Laboratories.

It is widely used in system programming, operating systems, embedded systems, and application development.

**What I learned:**
- History and introduction to C.
- Importance of programming languages.
- Compilation and execution.
- Basic programming concepts.

## 2. Features of C

C is popular because of its simplicity, efficiency, portability, and structured programming approach.

**Important features:**
- Simple and efficient.
- Portable.
- Structured programming.
- Fast execution.
- Rich set of operators.
- Supports low-level memory operations.

## 3. Structure of a C Program

A C program follows a standard structure that helps the compiler understand and execute instructions.

**Example:**

```c
#include <stdio.h>

int main()
{
    printf("Hello World");

    return 0;
}
```

**Concepts learned:**
- Header files.
- `main()` function.
- Statements.
- Curly braces.
- Semicolons.
- Return statement.

## 4. Variables and Constants

A variable is a named memory location used to store data that can change during program execution.

A constant is a fixed value that cannot be modified during program execution.

**Concepts learned:**
- Variable declaration.
- Variable initialization.
- Naming conventions.
- Assigning values.
- Constants using `const`.

## 5. Data Types

Data types define the type of information a variable can store.

| Data Type | Description | Example |
|---|---|---|
| `int` | Stores integer values | `int age = 20;` |
| `float` | Stores decimal values | `float price = 25.5;` |
| `double` | Stores higher-precision decimal values | `double value = 45.678;` |
| `char` | Stores a single character | `char grade = 'A';` |

**Concepts learned:**
- Basic data types.
- Declaration of variables.
- Assigning values.
- Understanding data storage.

## 6. Operators

Operators are symbols used to perform operations on variables and values.

### Types of Operators

**1. Arithmetic Operators**

Used for mathematical calculations.

`+` Addition | `-` Subtraction | `*` Multiplication | `/` Division | `%` Modulus

**2. Relational Operators**

Used to compare two values.

`==` | `!=` | `>` | `<` | `>=` | `<=`

**3. Logical Operators**

Used to combine conditions.

`&&` Logical AND | `||` Logical OR | `!` Logical NOT

**4. Assignment Operators**

Used to assign or update values.

`=` | `+=` | `-=` | `*=` | `/=`

**5. Increment and Decrement Operators**

Used to increase or decrease a variable by one.

`++` Increment | `--` Decrement

## 7. Input and Output

Input and output functions allow users to interact with a C program.

| Function | Purpose |
|---|---|
| `printf()` | Displays output |
| `scanf()` | Accepts input |

**Example:**

```c
#include <stdio.h>

int main()
{
    int age;

    printf("Enter your age: ");
    scanf("%d", &age);

    printf("Your age is %d", age);

    return 0;
}
```

## 8. Conditional Statements

Conditional statements allow a program to make decisions based on specified conditions.

**Topics covered:**
- `if` statement.
- `if-else` statement.
- Nested `if`.
- `else-if` ladder.
- `switch` statement.

**Example applications:**
- Checking even or odd numbers.
- Finding the largest number.
- Checking positive or negative values.
- Grade calculation.

## 9. Looping Statements

Loops are used to execute a block of code repeatedly until a particular condition is satisfied.

**Types of loops:**
- `for` loop.
- `while` loop.
- `do-while` loop.
- Nested loops.

**Loop control statements:**
- `break`.
- `continue`.

## 10. Pattern Programming

Pattern programming involves arranging numbers, symbols, or characters using loops.

It helps develop logical thinking and a better understanding of nested loops.

**Patterns practiced:**
- Square star pattern.
- Right-angled triangle.
- Inverted triangle.
- Number triangle.
- Pyramid pattern.
- Diamond pattern.

**Example:**

```c
#include <stdio.h>

int main()
{
    int row, col;

    for(row = 0; row < 5; row++)
    {
        for(col = 0; col <= row; col++)
        {
            printf("* ");
        }

        printf("\n");
    }

    return 0;
}
```

**Output:**

```text
*
* *
* * *
* * * *
* * * * *
```

## 11. Arrays

An array is a collection of elements of the same data type stored in consecutive memory locations.

**Concepts covered:**
- Array declaration.
- Array initialization.
- Accessing array elements.
- One-dimensional arrays.
- Basic array operations.

**Example:**

```c
#include <stdio.h>

int main()
{
    int arr[5] = {10, 20, 30, 40, 50};

    for(int i = 0; i < 5; i++)
    {
        printf("%d ", arr[i]);
    }

    return 0;
}
```

**Output:**

```text
10 20 30 40 50
```

## 12. Practical Programs

This repository includes hands-on coding exercises to apply the concepts learned.

**Practice programs include:**

- Hello World.
- Addition of two numbers.
- Arithmetic operations.
- Even or odd number.
- Positive or negative number.
- Largest of two numbers.
- Largest of three numbers.
- Multiplication table.
- Factorial.
- Sum of natural numbers.
- Star patterns.
- Number patterns.
- Basic array programs.

Each program is maintained with its source code and sample output.

## 13. Repository Structure

```text
C-Learning-Journey/
│
├── README.md
│
├── Day-01/
│   ├── README.md
│   ├── hello_world.c
│   ├── variables.c
│   ├── datatypes.c
│   ├── operators.c
│   └── basic_programs.c
│
├── Day-02/
│   └── README.md
│
├── Patterns/
│   ├── square_pattern.c
│   ├── triangle_pattern.c
│   └── number_pattern.c
│
└── Arrays/
    ├── array_input.c
    └── array_output.c
```

*The folder structure will expand as new topics and exercises are added.*

## 14. Learning Progress

| No. | Topic | Progress |
|---|---|---|
| 01 | Introduction to C | Completed |
| 02 | Structure of C Program | Completed |
| 03 | Variables and Constants | Learning |
| 04 | Data Types | Learning |
| 05 | Operators | Learning |
| 06 | Input and Output | Learning |
| 07 | Conditional Statements | Upcoming |
| 08 | Looping Statements | Upcoming |
| 09 | Pattern Programming | Upcoming |
| 10 | Arrays | Upcoming |

*Progress labels should be updated as each topic is completed.*

## 15. Skills Developed

Through this learning journey, I aim to develop:

- Programming fundamentals.
- Logical thinking.
- Problem-solving skills.
- Understanding of programming syntax.
- Basic algorithmic thinking.
- Debugging and error identification.
- Practical coding experience.

## 16. Future Learning Goals

My next goals are to:

- Strengthen C programming fundamentals.
- Solve more logical programming problems.
- Practise advanced pattern problems.
- Explore two-dimensional arrays.
- Learn basic string operations.
- Build small projects using C.

## 17. Author

**GitHub Profile:** [purohitsangeetha112-droid](https://github.com/purohitsangeetha112-droid)

**Learning Focus:** C Programming | Problem Solving | Programming Fundamentals

---

<p align="center">
  <b>Learning one concept at a time. Improving one program at a time.</b>
</p>
