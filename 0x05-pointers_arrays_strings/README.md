Pointers, Arrays, and Strings - C Programming

Table of Contents
Description
Resources
Learning Objectives
Requirements
Tasks
Quiz questions
Description
This project focuses on the concepts of pointers, arrays, and strings in the C programming language. It includes a series of tasks that cover various aspects of these topics.

Resources
To successfully complete this project, it is recommended to read or watch the following resources:

C - Arrays
C - Pointers
C - Strings
Memory Layout
Learning Objectives
By the end of this project, you should be able to explain the following concepts without using external resources:

Pointers and how to use them
Arrays and how to use them
Differences between pointers and arrays
Manipulating strings in C
Scope of variables
Requirements
Allowed editors: vi, vim, emacs
All files will be compiled on Ubuntu 20.04 LTS using gcc with the following flags:
-Wall -Werror -Wextra -pedantic -std=gnu89
All files should end with a new line
A README.md file at the root of the project folder is mandatory
Code should follow the Betty style, which will be checked using betty-style.pl and betty-doc.pl
Do not use global variables
Each file should contain no more than 5 functions
Standard library functions like printf, puts, etc. are forbidden
You are allowed to use the provided _putchar function
The prototypes of all functions and the _putchar function should be included in the main.h header file
Do not forget to push the main.h header file
Tasks
The project consists of several tasks. For each task, there is a specific requirement and an example demonstrating the expected behavior of the implemented code. The code files for each task can be found in the corresponding file within the 0x05-pointers_arrays_strings directory of the alx-low_level_programming GitHub repository.

98 Battery st.

Write a function that takes a pointer to an int as a parameter and updates the value it points to 98.
Prototype: void reset_to_98(int *n);
Don't swap horses in crossing a stream

Write a function that swaps the values of two integers.
Prototype: void swap_int(int *a, int *b);
This report, by its very length, defends itself against the risk of being read

Write a function that returns the length of a string.
Prototype: int _strlen(char *s);
I do not fear computers. I fear the lack of them

Write a function that prints a string, followed by a new line, to stdout.
Prototype: void _puts(char *str);
I can only go one way. I've not got a reverse gear

Write a function that prints a string in reverse, followed by a new line.
Prototype: void print_rev(char *s);

