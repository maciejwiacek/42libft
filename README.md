# Libft - Custom C Standard Library
Libft is a custom implementation of many functions from the C Standard Library. The projects aims to replicate essential standard functions from common libraries.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Gained Knowledge](#gained-knowledge)

## Overview
The project serves as a foundation for future projects at 42, requiring an in-depth understanding of basic C programming and memory management. It also includes additional utility functions such as a custom printf and get_next_line.

## Features
- Reimplementation of core C library functions
  - Memory functions (memset, memcpy, malloc, etc.)
  - String manipulation (strcpy, strlen, strdup, etc.)
  - Character checks and transformation (isalpha, isdigit, tolower, etc.)
  - Linked list manipulation (ft_lstnew, ft_lstadd_front, etc.)
- A custom implementation of the printf function.
- A function that reads a line from a file descriptor, handling buffers and ensuring efficient file reading.

## Usage
1. Clone the repository
```bash
https://github.com/maciejwiacek/42libft.git && cd 42libft
```
2. Compile the library
```bash
make
```
3. Include the header file in your code
```bash
#include "libft.h"
```
4. Link the compiled library when compiling your project
```bash
gcc -Wall -Wextra -Werror -o program program.c -L. -lft
```

## Gained Knowledge:
- Reinforce C programming skills by implementing core and advanced functions from scratch.
- Deeper understanding of common C functions.
- Gain deeper insight into memory management, file reading and formatted output.
- Build a versatile library that can be used in multiple C projects.
