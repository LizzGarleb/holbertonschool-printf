![_printf banner](https://user-images.githubusercontent.com/96942307/201234320-27b3afa1-900a-49ee-920d-7605688034c1.png)

## Table of Content
:computer: _printf.c: This is the main code, of our custom function, it's a replica of the printf function.

:computer: function_declaration.c: Contains all the functions that are call in our _printf.c file.

:computer: main.h: It's the header file, contains the prototype to our functions.

:computer: man_3_printf: This file contains the man page for the function _printf.

## Description

The function _printf main focus is to print an output according to a certain format. Different ways to print an output is with the use of a format specifier.

### What is format specifier?

A format specifier in c are used to take input and print the output of a type. The symbol we use in every format specifier is %. The specifier tells the compiler about the type of data that most be given or input and the type of data that most be printed on the screen.

| Format Specifier | Used for...                                                   |
|------------------|---------------------------------------------------------------|
| %%               | Write a function that returns the sum of all its parameters.  |
| %i, %d           | Write a function that prints numbers, followed by a new line. |
| %s               | Write a function that prints strings, followed by a new line. |
| %c               | Write a function that prints anything.                        |

### Usage Example
```
Example for char:           Example for string:                Example for digit:             Example for interger:
Input: _printf("%c", H);    Input: _printf("%s", "hello");     Input: _printf("%d", 13);      Input: _printf("%i", 45);
Output: H                   Output: hello                      Output: 13                     Output: 45
```
### Return Value
Upon successful return, these functions return the number of character printed (excluding the null byte used to end output to string). If an output error is encountered, a negative value is returned.

## Technology

The language we use for the creation of _printf() is the C language. This low level language allow us to create and control function from scratch and define its output. We are currently in our foundation trimester of C language and we are testing our knowledge by building the _print() from scratch.

### Compilation
All the files that were used are compiled using:
`gcc -Wall -Werror -Wextra -pedantic -std=gnu89 -Wno-format *.c`

## Challenges
The challenges we faced are the following:

* Finding the edge cases. This was done by purposely breaking the function and finding a solution.
* The creation of the function to print intergers.
* Trying to create a function with the little information that was given to us. 

Solving these challenges helped us to develop critical thinking and emphasize collaboration.

## Reference
This function work similar to ![printf(3)](https://man7.org/linux/man-pages/man3/printf.3.html). 

## Developers
### Lizbeth Garcia & Guillermo Rosario
Hi, Im Lizbeth Garcia on of the developer behind this project. To connect with me professionaly and explore more about my work, I invite you to visit my LinkedIn profile ([Lizbeth Garcia](https://www.linkedin.com/in/lizbeth-garcia-53657a22a?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B0ioxuQ4BQy2Z%2Fclq%2BYgMvQ%3D%3D) ). There, you can find articles, and professional experiences. For more casual discussion and tech insight, feel free to follow me on Twitter ([@GarlebLizz](https://twitter.com/GarlebLizz)) or Instagram ([@CodewithLizz](https://www.instagram.com/codewithlizz/)). I look foward to connecting with you!

Hey, Im Guillemro Rosario one of the developer behind this project. You can find me on LinkedIn ([Guillermo Rosario](https://www.linkedin.com/in/guillermo-rosario-torres-085195133?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BNvRmi8XQRLGEKejp6cXQ8Q%3D%3D))
