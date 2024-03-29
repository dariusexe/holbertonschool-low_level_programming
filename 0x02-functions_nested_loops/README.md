# 0x02-functions_nested_loops

This project show tasks about functions and nested loops.

## Objectives 🚀

Learn about:
* What are nested loops and how to use them
* What is a function and how do you use functions
* What is the difference between a declaration and a definition of a function
* What is a prototype
* Scope of variables
* What are the gcc flags -Wall -Werror -pedantic -Wextra
* What are header files and how to to use them with #include

## Requeriments 📋

Ubuntu 14.04 LTS.
GCC 4.8.4 using the flags -Wall -Werror -Wextra and -pedantic.
Prototypes of all functions and the prototype of the function _putchar are included in header file called holberton.h

## Exercises ⚙️

### [0._putchar](https://github.com/dfbq91/holbertonschool-low_level_programming/blob/master/0x02-functions_nested_loops/0-holberton.c)

Write a program that prints Holberton, followed by a new line.
``
* The program should return 0

### [1-alphabet.c](https://github.com/dfbq91/holbertonschool-low_level_programming/blob/master/0x02-functions_nested_loops/1-alphabet.c)

Write a function that prints the alphabet, in lowercase, followed by a new line.
* Prototype: void print_alphabet(void);
* You can only use _putchar twice in your code

### [2-print_alphabet_x10.c](https://github.com/dfbq91/holbertonschool-low_level_programming/blob/master/0x02-functions_nested_loops/1-alphabet.c)

Write a function that prints 10 times the alphabet, in lowercase, followed by a new line.
* Prototype: void print_alphabet_x10(void);
* You can only use _putchar twice in your code

### [3-islower.c](https://github.com/dfbq91/holbertonschool-low_level_programming/blob/master/0x02-functions_nested_loops/3-islower.c)

Write a function that checks for lowercase character.
* Prototype: int _islower(int c);
* Returns 1 if c is lowercase
* Returns 0 otherwise

### [4-isalpha.c](https://github.com/dfbq91/holbertonschool-low_level_programming/blob/master/0x02-functions_nested_loops/4-isalpha.c)

Write a function that checks for alphabetic character.
* Prototype: int _isalpha(int c);
* Returns 1 if c is a letter, lowercase or uppercase
* Returns 0 otherwise

### [5-sign.c](https://github.com/dfbq91/holbertonschool-low_level_programming/blob/master/0x02-functions_nested_loops/5-main.c)

Write a function that prints the sign of a number.
* Prototype: int print_sign(int n);
* Returns 1 and prints + if n is greater than zero
* Returns 0 and prints 0 if n is zero
* Returns -1 and prints - if n is less than zero

### [6-abs](https://github.com/dfbq91/holbertonschool-low_level_programming/blob/master/0x02-functions_nested_loops/6-abs.c)

Write a function that computes the absolute value of an integer.
* Prototype: int _abs(int);

### [7-print_last_digit.c](https://github.com/dfbq91/holbertonschool-low_level_programming/blob/master/0x02-functions_nested_loops/7-print_last_digit.c)

Write a function that prints the last digit of a number.
* Prototype: int print_last_digit(int);
* Returns the value of the last digit

### [8-24_hours.c](https://github.com/dfbq91/holbertonschool-low_level_programming/blob/master/0x02-functions_nested_loops/8-24_hours.c)

Write a function that prints every minute of the day of Jack Bauer, starting from 00:00 to 23:59.
* Prototype: void jack_bauer(void);

### [9-times_table.c](https://github.com/dfbq91/holbertonschool-low_level_programming/blob/master/0x02-functions_nested_loops/9-times_table.c)

Write a function that prints the 9 times table, starting with 0.
* Prototype: void times_table(void)

### [10-add.c](https://github.com/dfbq91/holbertonschool-low_level_programming/blob/master/0x02-functions_nested_loops/10-add.c)

Write a function that adds two integers and returns the result.
* Prototype: int add(int, int);

### [11-print_98.c](https://github.com/dfbq91/holbertonschool-low_level_programming/blob/master/0x02-functions_nested_loops/11-print_to_98.c)

Write a function that prints all natural numbers from n to 98, followed by a new line.
* Prototype: void print_to_98(int n);
* Numbers must be separated by a comma, followed by a space
* Numbers should be printed in order
* The first printed number should be the number passed to your function
* The last printed number should be 98
* You are allowed to use the standard library

### [101-natural.c](https://github.com/dfbq91/holbertonschool-low_level_programming/blob/master/0x02-functions_nested_loops/101-natural.c)

If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23. Write a program that computes and prints the sum of all the multiples of 3 or 5 below 1024 (excluded), followed by a new line.
* You are allowed to use the standard library
