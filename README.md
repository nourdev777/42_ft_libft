# 42_ft_libft 📚

## 🌟 About the Project
`42_ft_libft` is my custom C library, built from scratch during the **42 Abu Dhabi Common Core**. I recreated essential C standard functions and added unique utilities to create a solid foundation for my future 42 projects.

## 🛠️ Features

### Part 1: Standard C Functions
Recoded libc classics with the `ft_` prefix:

- **String Tools**: `ft_strlen`, `ft_strcpy`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strstr`  
- **Memory Tools**: `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`  
- **Char Checks**: `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`  
- **Conversions**: `ft_toupper`, `ft_tolower`, `ft_atoi`  
- **Allocation**: `ft_calloc`, `ft_strdup`  

### Part 2: Extra Utilities
Custom tools for more power:

- `ft_substr` — Extracts a substring.  
- `ft_strjoin` — Concatenates two strings.  
- `ft_strtrim` — Trims characters from both ends.  
- `ft_split` — Splits a string by a delimiter.  
- `ft_itoa` — Converts an integer to a string.  
- `ft_strmapi` — Applies a function to each character.  
- `ft_striteri` — Modifies a string in place.  
- `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd` — Outputs to a file descriptor.  

### Bonus: Linked Lists
Extra list manipulation functions:

- `ft_lstnew`, `ft_lstadd_front`, `ft_lstadd_back` — Create and add nodes.  
- `ft_lstsize`, `ft_lstlast` — Get list stats.  
- `ft_lstdelone`, `ft_lstclear` — Free nodes.  
- `ft_lstiter`, `ft_lstmap` — Iterate and transform lists.  

*(Over 40 functions total, including bonuses!)*

## 🚀 How to Use

1. **Clone the repo:**  
   ```bash
   git clone https://github.com/nourdev777/42_ft_libft.git
   ```

2. **Compile the library:**  
   ```bash
   make
   ```
   - For bonus functions:  
     ```bash
     make bonus
     ```
   - To clean up compiled files:  
     ```bash
     make fclean
     ```

3. **Include it in your project:**  
   ```c
   #include "libft.h"
   ```

## 💡 What I Learned

- Writing clean C code with no memory leaks.  
- Mastering memory management with `malloc` and `free`.  
- Building a `Makefile` to streamline compilation.  
- Understanding the inner workings of standard functions.  

## 📜 Original Task
See the full assignment [here]([https://github.com/nourdev777/42_ft_libft/libft_assignment.pdf](https://github.com/nourdev777/42_ft_libft/blob/master/libft_assignment.pdf)).

---

Built with passion at **42 Abu Dhabi**! ☕🚀

