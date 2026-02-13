# libft

![C](https://img.shields.io/badge/language-C-blue?style=flat-square)

Static C library developed as part of the 42 (Codam) curriculum.


The project consists of reimplementing standard C library functions and extending them with additional utilities, including a linked list API.

---

## 📚 Overview

This repository contains:

- Reimplementation of standard libc functions  
- Additional string and memory utilities  
- A linked list implementation (bonus part)  
- A Makefile that builds a static library (`libft.a`)  

All functions are written in C and follow 42 project constraints.

---

## 🧠 Implemented Functions

### Memory Functions
- `ft_memset`
- `ft_bzero`
- `ft_memcpy`
- `ft_memmove`
- `ft_memchr`
- `ft_memcmp`
- `ft_calloc`

### String Functions
- `ft_strlen`
- `ft_strdup`
- `ft_strlcpy`
- `ft_strlcat`
- `ft_strchr`
- `ft_strrchr`
- `ft_strncmp`
- `ft_strnstr`
- `ft_strjoin`
- `ft_strtrim`
- `ft_substr`
- `ft_split`
- `ft_strmapi`
- `ft_striteri`

### Character Checks & Conversions
- `ft_isalpha`
- `ft_isdigit`
- `ft_isalnum`
- `ft_isascii`
- `ft_isprint`
- `ft_toupper`
- `ft_tolower`

### Output Functions
- `ft_putchar_fd`
- `ft_putstr_fd`
- `ft_putendl_fd`
- `ft_putnbr_fd`

### Conversions
- `ft_atoi`
- `ft_itoa`

---

## 🔗 Bonus — Linked List API

- `ft_lstnew`
- `ft_lstadd_front`
- `ft_lstadd_back`
- `ft_lstsize`
- `ft_lstlast`
- `ft_lstdelone`
- `ft_lstclear`
- `ft_lstiter`
- `ft_lstmap`

---

## 🛠 Build

Compile the static library:

```bash
make
```

This generates:

```
libft.a
```

Clean object files:

```bash
make clean
```

Remove object files and library:

```bash
make fclean
```

Rebuild:

```bash
make re
```

---

## 📦 Usage

Include the header in your project:

```c
#include "libft.h"
```

Compile with:

```bash
gcc main.c -L. -lft
```

---

## 🎯 Project Focus

- Pointer manipulation  
- Manual memory management  
- String processing  
- Linked list implementation  
- Writing modular and reusable C code  
