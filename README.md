# Libft — 42 Project

The first project at 42 school. A custom **C library** that re-implements standard libc functions plus additional utility functions. This library is used as a foundation for all future 42 C projects.

## Functions

### Part 1 — Libc functions
`ft_isalpha` `ft_isdigit` `ft_isalnum` `ft_isascii` `ft_isprint` `ft_strlen` `ft_memset` `ft_bzero` `ft_memcpy` `ft_memmove` `ft_strlcpy` `ft_strlcat` `ft_toupper` `ft_tolower` `ft_strchr` `ft_strrchr` `ft_strncmp` `ft_memchr` `ft_memcmp` `ft_strnstr` `ft_atoi` `ft_calloc` `ft_strdup`

### Part 2 — Additional functions
`ft_substr` `ft_strjoin` `ft_strtrim` `ft_split` `ft_itoa` `ft_strmapi` `ft_striteri` `ft_putchar_fd` `ft_putstr_fd` `ft_putendl_fd` `ft_putnbr_fd`

### Bonus — Linked list functions
`ft_lstnew` `ft_lstadd_front` `ft_lstsize` `ft_lstlast` `ft_lstadd_back` `ft_lstdelone` `ft_lstclear` `ft_lstiter` `ft_lstmap`

## Tech Stack

- **C**
- **Makefile**

## How to Build

```bash
make
make bonus    # include linked list functions
```

This creates `libft.a` — link it to your projects with `-L. -lft`.

## Author

**Houssame El Bandoudi** — [GitHub](https://github.com/HOUSSAMEELBANDOUDI) | 42 Student (hel-band)
