# Libft - Your Very First Own Library

## 🎯 Project Overview

**Libft** is the foundational project of the 42 curriculum where you create your first C library from scratch. This project teaches you to reimplement standard C library functions and build additional utility functions that will become essential tools for all your future C projects.

> **Summary:** This project involves coding a C library that will include numerous general purpose functions for your programs.

## 📚 What You'll Build

### Part 1: Libc Functions Recreation
Reimplement essential standard C library functions with `ft_` prefix:

**Character Classification:**
- `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`

**String Manipulation:**
- `ft_strlen`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strnstr`

**Memory Operations:**
- `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`

**Character Conversion:**
- `ft_toupper`, `ft_tolower`, `ft_atoi`

**Memory Allocation:**
- `ft_calloc`, `ft_strdup`

### Part 2: Additional Utility Functions

**String Operations:**
- `ft_substr` - Extract substring from string
- `ft_strjoin` - Concatenate two strings
- `ft_strtrim` - Remove characters from start/end of string
- `ft_split` - Split string into array using delimiter
- `ft_itoa` - Convert integer to string
- `ft_strmapi` - Apply function to each character with index
- `ft_striteri` - Apply function to each character (in-place)

**File Descriptor Output:**
- `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

## 🏆 Bonus Part: Linked List Implementation

Create a complete linked list management system:

**List Structure:**
```c
typedef struct s_list
{
    void *content;
    struct s_list *next;
} t_list;
```

**List Functions:**
- `ft_lstnew` - Create new list node
- `ft_lstadd_front` - Add node to list beginning
- `ft_lstsize` - Count nodes in list
- `ft_lstlast` - Get last node
- `ft_lstadd_back` - Add node to list end
- `ft_lstdelone` - Delete single node
- `ft_lstclear` - Clear entire list
- `ft_lstiter` - Iterate through list
- `ft_lstmap` - Create new transformed list

## 🛠️ Technical Requirements

### Build System
- **Makefile** with standard rules: `all`, `clean`, `fclean`, `re`, `bonus`
- **Static library** output: `libft.a`
- **Compilation flags**: `-Wall -Wextra -Werror`
- **Use `ar` command** (libtool forbidden)

### Code Standards
- **No global variables**
- **Helper functions** must be `static`
- **All files at repository root**
- **Strict norm compliance**

## 🎯 Learning Objectives

### Core C Programming
- **Memory Management**: Proper use of `malloc`, `free`, `calloc`
- **String Manipulation**: Deep understanding of string operations
- **Pointer Arithmetic**: Efficient memory and string handling
- **Error Handling**: Robust function implementations

### System Programming
- **File Descriptors**: Output to different file descriptors
- **Library Creation**: Building reusable static libraries
- **Makefile Mastery**: Automated build processes

### Data Structures
- **Linked Lists**: Dynamic data structure implementation
- **Generic Programming**: `void *` pointers for flexible data storage

## 💡 Why This Project Matters

### Foundation for Future Projects
Libft becomes your personal toolkit used across all 42 C projects. You'll constantly expand and improve it throughout your curriculum.

### Deep Language Understanding
By recreating standard functions, you gain intimate knowledge of how C works at a fundamental level, rather than just using libraries as black boxes.

### Professional Development
- **Code Organization**: Learn to structure reusable code
- **Debugging Skills**: Understand common C pitfalls
- **Performance Awareness**: Write efficient low-level code
