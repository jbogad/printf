# Ft_printf - Custom Printf Implementation ✍️

Welcome to my custom implementation of the C `printf` function!

## Table of Contents
- [What is ft_printf?](#what-is-ft-printf)
- [Supported Specifiers](#supported-specifiers)

## What is ft_printf?

`ft_printf` is a reimplementation of the standard C library `printf` function, developed as part of the 42 Madrid curriculum. This project recreates the handling of formatted strings and various data types using specifiers like `%d`, `%s`, `%c`, and more. It tests the use of variable arguments (`va_list`) and output management in C, replicating the core functionalities of `printf`.

## Supported Specifiers

List of specifiers implemented in my `ft_printf`:

| Specifier | Description                                    |
|-----------|------------------------------------------------|
| `%c`      | Prints a single character.                     |
| `%s`      | Prints a string of characters.                 |
| `%d`      | Prints a signed decimal integer.               |
| `%i`      | Prints a signed decimal integer (same as %d).  |
| `%u`      | Prints an unsigned integer.                    |
| `%x`      | Prints an integer in hexadecimal (lowercase).  |
| `%X`      | Prints an integer in hexadecimal (uppercase).  |
| `%p`      | Prints a pointer in hexadecimal format.        |
| `%%`      | Prints a percent symbol.                       |
