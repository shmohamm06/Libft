# Libft

## Overview
Libft is a custom C library that reimplements standard C library functions. This project serves as the foundation for all subsequent projects in the 42 curriculum, providing essential utility functions for string manipulation, memory management, linked list operations, and more.

## Features
- **String Functions**: Complete string manipulation library (strlen, strcpy, strdup, etc.)
- **Memory Functions**: Memory allocation and manipulation (malloc, memcpy, memset, etc.)
- **Character Functions**: Character classification and conversion (isalpha, isdigit, tolower, etc.)
- **Conversion Functions**: String to number conversion (atoi, itoa)
- **Linked List Functions**: Complete linked list implementation with bonus functions
- **File Descriptor Functions**: Output functions for different file descriptors

## Project Structure
```
Libft/
├── libft.h          # Header file with all function declarations
├── Makefile         # Build configuration
├── ft_*.c          # Implementation files for each function
└── .git/           # Git repository
```

## Functions Implemented

### Mandatory Functions
- **Memory**: `ft_memset`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`, `ft_bzero`, `ft_calloc`
- **String**: `ft_strlen`, `ft_strlcpy`, `ft_strlcat`, `ft_strchr`, `ft_strrchr`, `ft_strnstr`, `ft_strncmp`, `ft_strdup`
- **String Manipulation**: `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`, `ft_strmapi`, `ft_striteri`
- **Character**: `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`, `ft_toupper`, `ft_tolower`
- **Conversion**: `ft_atoi`, `ft_itoa`
- **Output**: `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

### Bonus Functions (Linked Lists)
- `ft_lstnew`, `ft_lstadd_front`, `ft_lstsize`, `ft_lstlast`
- `ft_lstadd_back`, `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`



## Usage
After building, the library creates `libft.a` which can be linked with other projects:
```bash
gcc -o my_program my_program.c -L. -lft
```

## Requirements
- GCC compiler
- Make utility
- Standard C libraries

## Notes
- All functions follow the 42 coding style (norminette)
- Functions are designed to be memory-safe and handle edge cases
- The library serves as a dependency for many other 42 projects
- Functions are optimized for performance and readability

## Author
shmohamm - 42 Abu Dhabi
