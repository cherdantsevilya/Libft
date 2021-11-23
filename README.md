<h1 align="center">
  L  I  B  F  T
</h1>

___

## :memo: **About**

_This project is your very first project as a student at 42. You will need to recode a few functions of the C standard library as well as some other utility functions that you will use during your whole cursus_.

### *Objectives*  
> + Unix logic

### *Skills*
> + Imperative programming
> + Rigor
> + Algorithms & AI

For detailed information, refer to the [**subject of this project**](https://github.com/CherdantsevIlya/libft/blob/master/en.subject.pdf).

___

## 🧩 **Lib functions**

### <stdlib.h>

FUNCTION NAME | DESCRIPTION |
:-----------: | :-----------:
| ft_abs | computes the absolute value of the integer argument |
| ft_atoi | converts the initial portion of the string to int |
| ft_calloc | allocates memory for an array of size bytes each and returns a pointer to the allocated memory |
| ft_itoa | constructs a string representation of an integer |

### <strings.h>

FUNCTION NAME | DESCRIPTION |
:-----------: | :-----------:
| ft_bzero | erases the data in the n bytes of the memory starting at the location pointed to by s, by writing zeros |
| ft_atoi | converts the initial portion of the string to int |

### <ctype.h>

FUNCTION NAME | DESCRIPTION |
:-----------: | :-----------:
| ft_isalnum | checks whether the argument passed is an alphanumeric character (alphabet or number) or not |
| ft_isalpha | checks whether a character is an alphabet or not |
| ft_isascii  | checks whether c is a 7-bit unsigned char value that fits into the ASCII character set |
| ft_isdigit | checks whether a character is numeric character (0-9) or not |
| ft_isprint |  checks whether a character is a printable character or not |
| ft_isascii  | checks whether c is a 7-bit unsigned char value that fits into the ASCII character set |
| ft_tolower | converts the letter c to lower case, if possible |
| ft_toupper | converts the letter c to upper case, if possible | 

### <string.h>

FUNCTION NAME | DESCRIPTION |
:-----------: | :-----------:
| ft_memccpy | returns a pointer to the next character in dest after c, or NULL if c was not found in the first n characters of src |
| ft_memchr | scans the initial n bytes of the memory area pointed to by s for the first instance of c. Both c and the bytes of the memory area pointed to by s are interpreted as unsigned char |
| ft_memcmp | compares the first n bytes (each interpreted as unsigned char) of the memory areas s1 and s2 |
| ft_memcpy | copies n bytes from memory area src to memory area dest. The memory areas must not overlap |
| ft_memmove | copies n bytes from memory area src to memory area dest. The memory areas may overlap |
| ft_memset | function fills the first n bytes of the memory area pointed to by s with the constant byte c |
| ft_strcat | appends the src string to the dest string, overwriting the terminating null byte ('\0') at the end of dest, and then adds a terminating null byte |
| ft_strchr | returns a pointer to the last occurrence of the character c in the string s |
| ft_strcpy | copies the string pointed to by src, including the terminating null byte ('\0'), to the buffer pointed to by dest |
| ft_strdup | returns a pointer to a new string which is a duplicate of the string s |
| ft_strlcat | appends the NUL-terminated string src to the end of dst. It will append at most size - strlen(dst) - 1 bytes, NUL-terminating the result |
| ft_strlcpy | copies up to size - 1 characters from the NUL-terminated string src to dst, NUL-terminating the result |
| ft_strlen | calculates the length of the string s, excluding the terminating null byte | 
| ft_strncmp | compares the first (at most) n bytes of s1 and s2 |
| ft_strncpy | at most n bytes of src are copied |
| ft_strnstr | locates the first occurrence of the null-termi-nated null-terminated nated string s2 in the string s1, where not more than n characters are searched |
| ft_strrchr | returns a pointer to the last occurrence of the character c in the string s |

### non-library functions

FUNCTION NAME | DESCRIPTION |
:-----------: | :-----------:
| ft_putchar_fd | output a character to given file |
| ft_putendl_fd | output string to given file with newline |
| ft_putnbr_fd  | output integer to given file |
| ft_putstr_fd | output string to given file |
| ft_split | split string, with specified character as delimiter, into an array of strings |
| ft_isascii  | checks whether c is a 7-bit unsigned char value that fits into the ASCII character set |
| ft_strjoin | concatenate two strings into a new string (with malloc) |
| ft_strmapi | create new string from modifying string with specified function |
| ft_strtrim | trim beginning and end of string with the specified characters |
| ft_substr | extract substring from string |

___

## 🧨 **Tests**



