<h1 align ="center"> Printf Project </h1><br>

<p align="center">
	<a href="https://holbertonschool.com">
		<img alt="holbie" title="holbie" src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/228/printf.png" width="350">
	</a>
</p>
<p align="center">
Made as a project for Holberton School
</p>

## Authors

* [Juan David Marin](https://twitter.com/Teslothorcha)
* [Julian David Gaitan](https://twitter.com/JulianDavidG07)

## Table of Contents

- [Introduction](#introduction)
- [Description](#description)
- [Features](#features)
- [Built With](#built-with)
- [Acknowledgments](#acknowledgments)

## Introduction

The C library function int printf(const char *format, ...) sends formatted output to stdout.
A custom made printf function built in C using only the write, malloc, free, va_start, va_copy, va__arg, and va_end non custom functions.

## Description

The custom printf function is called using \_printf() and will take in a format string.

int \_printf(const char \*format, ...);

## Features

* %c : with a char argument, prints that char

* %s : with a string argument, prints that string

* %d : with an integer argument, prints that integer

* %i : with an integer argument, prints that integer

* %% : will print out just one of the percentage signs

* %r : with a string argument, prints the reversed string

* %R : with a string argument, prints the rot13 encoded version of string

* %p : with a pointer address argument, prints the address in hexadecimal with preceding 0x

* %S : with a string argument, prints any unprintable characters as \x and the 2 digit hexadecimal representation of the character

* %u : with an integer argument, prints the unsigned integer

* %o : with an integer argument, prints the octal notation

* %x : with an integer argument, prints the hexadecimal notation with lowercase letters

* %X : with an integer argument, prints the hexadecimal notation with uppercase letters

* %b : with an integer argument, prints the binary conversion of that integer

### Files

---
File|Description
---|---
e | contains function for printing an address
h | header file with all prototypes, libraries, and struct that used to identify correct function
m | man page for custom printf function
p | functions for printing chars, integers, and strings using %c, %s, %d, %i
s | file with functions used by strings.c to print different types of strings
s | contains functions for printing strings in rot13, reverse, or with unprinted characters represented as hexadecimal
u | file with functions for printing unsigned integer recieving conversions (unsigned, octal, hexadecimal upper and lower case)
u | file with helper functions for conversion functions

## Built With

* [C](https://en.wikipedia.org/wiki/C_(programming_language))
* [Emacs](https://www.gnu.org/software/emacs/)
* [Vagrant](https://www.vagrantup.com/)
* [Ubuntu](https://www.ubuntu.com/)
* [GCC 4.8.4 Compiler](https://gcc.gnu.org/)

## Acknowledgments

* [Holberton School](https://www.holbertonschool.com/)
* [C library function - printf()](https://www.tutorialspoint.com/c_standard_library/c_function_printf.htm)
* [The C Programming Language](https://www.dipmat.univpm.it/~demeio/public/the_c_programming_language_2.pdf) by Brian Kernighan

