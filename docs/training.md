# Overview
## Resources
 - Software
    - GNU C Compiler (GCC) on Linux
    - Doxygen
 - Books
    - [C Training](./The%20C%20Programming%20Language%20(Kernighan%20Ritchie).pdf)
## Prerequisites
 - None

## Timelines
| | | |
| :---: | :---: | :---: | 
| 1 | Introduction to C | 0.5 |
| 2 | Good Programming Practices | 0.5 |
| 3 | Compilation techniques and Makefile Basics | 0.5 |
| 4 | Data Types, Operators & Expressions | 0.5 |
| 5 | Control Flow | 1 |
| 6 | Functions | 1 |
| 7 | Pointers & Arrays | 2 |
| 8 | Structures | 1 |
| 9 | Formatted Inputs & Outputs | 1 |
| 10 | Training Assignments | 3 |
| | | |

# Introduction to C
## Objective
Get an overview of different components of C Programming.
## Task
 - Go through Chapter 1 of K&R C Book
## Assignment
 - Complete exercise 1, 6 & 11 from K&R C Book.

# Good Programming Practices
## Objective
To get an overview of different coding standards available. To understand it better, one will have to start with a “Hello world” program as mentioned in a URL of section 2.2. It is necessary to know these standards as all trainees will have to follow in training assignments.
## Tasks
 - Go through Linux coding guidelines from [Linux kernel coding style¶
](https://www.kernel.org/doc/html/latest/process/coding-style.html)
 - Doxygen tool & its usage
## Assignment
None at this stage. There is one assignment for doxygen along-with final training assignments.

# Compilation techniques and Makefile Basics
## Objective
To get an overview of different linux commands for compilation of c source code and convert it into an executable. The other objective of this step is to get an overview on “how to create and use a makefile to compile c source code
## Tasks
- Go through [GNU Compiler HowTo](https://www.wikihow.com/Compile-a-C-Program-Using-the-GNU-Compiler-(GCC)) to understand a whole process of implementation, compilation & execution of famous “Hello World” C program.
- Go through [How to write a Makefile](./docs/How%20to%20write%20a%20Makefile.md) to learn Makefile basics. One can also explore more to learn advanced makefile generation techniques.
# Assignment
In all assignments, one will have to make sure that there are no compilation errors / warnings. In some assignments, one can compile a program using makefile

# Data Types, Operators & Expressions
## Objective
Get detailed idea about Data Types, Operators & Expressions in C.
## Task
Go through Chapter 2 of K&R C Book.
## Assignment
Complete exercise 4, 5 & 6 from K&R C Book.

# Control Flow
## Objective
Get detailed idea about various instruments to control program flow.
## Task
Go through Chapter 3 of K&R C Book
## Assignment
Complete exercise 1 to 6 from K&R C Book.

# Functions
## Objective
Get detailed idea about Functions in C.
## Task
Go through Chapter 4 of K&R C Book.
## Assignment
Complete exercise 4, 5, 11 & 12 from K&R C Book.

# Pointers & Arrays
## Objective
Get detailed idea about Pointers & Arrays in C.
## Task
Go through Chapter 5 of K&R C Book.
## Assignment
Complete exercise 1, 3, 4, 7, 8, 10 & 13 K&R C Book.

# Structures
## Objective
Get detailed idea about structures in C.
## Task
Go through Chapter 6 of K&R C Book.
## Assignment
Complete exercise 1 from K&R C Book.

# Formatted Inputs & Outputs
## Objective
Get an idea of formatted inputs (scanf) & outputs (printf) in C.
## Task
Go through Sections 7.2 & 7.4 of Chapter 7 from K&R C Book.
## Assignment
Complete exercise 3 & 5 from K&R C Book.

# Training Assignments
## Assignment
Your mentor will define an abstract datatype (e.g. Linklist / Tree) and will also provide a list of APIs (Functions) to be implemented.

## Other Notes
 - One needs to develop a static library for the datatype given to him
 - A proper menu-driven test application is to be developed to test all features (all APIs) of the library
 - There has to be a clean interface between test application an library. There must not be any shared global variables (no externs) in this test application or in library
 - The library commenting must be doxygen compliant. One needs to generate html document for this library

# Appendix A
Make sure you know all of these...
 - Data Types
    - Standard Data Types
    - Structures & Unions, Bit-fields
    - Arrays
    - Local, Global, Static, Volatile & Register variables
    - Life span and scope of a variable
    - Location of the variable (stack, heap, global etc…)
 - Operators
    - Arithmetic, Logical, Bit wise, Relational
    - Operator precedence
 - Control Flow & Loops
    - If-Else
    - Switch
    - While & do-while
    - For
    - Break
    - Continue
    - Goto & labels
 - Pointers
    - Basic Concept
    - Pointers & Arrays
    - Pointer to Pointer
    - Multidimensional Arrays & Pointers
    - Function Pointers
    - Structure Pointers
 - Functions
    - Basic Concept
    - Passing by value & address
    - Inline functions
    - Recursion
 - Pre-processors
    - Define
    - Typedef
    - Include
    - If & ifdef
 - Others
    - Header Files
    - Libraries
    - Error Handling
    - Coding Guidelines
        - MISRA C
        - Handling run-time allocation failures
        - Where extern variables should be placed?
        - Where should variables be placed? .h or .c files
        - Where should structures be declared
        - Where should structures be instantiated
        - Naming convention
        - Commenting styles, function headers and file history
