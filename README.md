# ft_printf

This is a project from the 42 school (42 Madrid) in which a custom version of the printf function from the standard C library is implemented.

## Description

The goal of the project is to recreate the behavior of printf by handling multiple format specifiers and ensuring the correct printing of data.

## Functionalities

The `ft_printf` function supports the following specifiers:

%c → Character
%s → String of characters
%p → Pointer in hexadecimal format
%d → Signed decimal integer
%i → Signed decimal integer
%u → Unsigned decimal integer
%x → Hexadecimal number (lowercase)
%X → Hexadecimal number (uppercase)
%% → Prints the percent symbol
Usage in this format

## Use

```c
#include "ft_printf.h"

int main(void) {
    ft_printf("Hello, %s! You have %d messages.\n", "user", 5);
    return 0;
}
```
