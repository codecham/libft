# Project Title

First project of the 42 curriculum. Implementation of a standard C function library and some additional ones.

## Contents

**Standard C function** (_See the official manuals_):

• isalpha
• isdigit
• isalnum
• isascii
• isprint
• strlen
• memset
• bzero
• memcpy
• memmove
• strlcpy
• strlcat
• toupper
• tolower
• strchr
• strrchr
• strncmp
• memchr
• memcmp
• strnstr
• atoi
• calloc
• strdup


**Additionnal functions**:

• ft_substr
```
Allocates and returns a substring
from the string ’s’.
The substring begins at index ’start’ and is of
maximum size ’len’.
```

• ft_strjoin
```
Allocates and returns a new
string, which is the result of the concatenation
of ’s1’ and ’s2’.
```

• ft_strtrim
```
Allocates and returns a copy of
’s1’ with the characters specified in ’set’ removed
from the beginning and the end of the string.
```

• ft_split
```
Allocates and returns an array
of strings obtained by splitting ’s’ using the
character ’c’ as a delimiter.
```

• ft_itoa
```
Allocates and returns a string
representing the integer received as an argument.
```

• ft_strmapi
```
Applies the function ’f’ to each character of the
string ’s’, and passing its index as first argument
to create a new string resulting
from successive applications of ’f’
```

• ft_striteri
```
Applies the function ’f’ on each character of
the string passed as argument, passing its index
as first argument. Each character is passed by
address to ’f’ to be modified if necessary.
```

• ft_putchar_fd
```
Outputs the character ’c’ to the given file
descriptor.
```

• ft_putendl_fd
```
Outputs the string ’s’ to the given file descriptor
followed by a newline.
```

• ft_putnbr_fd
```
Outputs the integer ’n’ to the given file
descriptor.
```

### Installing

```
git clone https://github.com/codecham/libft_42 libft
cd libft
make
```
Makefile create a libft.a file that you can add to a C project folder.

### Makefile

- make
```
Build the project
```

- make clean
```
Remove object files
```

- make fclean
```
Remove object and .a file
```

- make re
```
Clean and rebuild the project
```