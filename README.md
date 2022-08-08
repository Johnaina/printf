# _printf

```_printf``` is a custom implementation of the C programming function ```printf```.

## Format
**Prototype:** ```int _printf(const char *, ...);```

## Examples
**String**
* Input: ```_printf("%s\n", 'A string');```
* Output: ```A string```

**Character**
* Input: ```_printf("The last letter in the alphabet is %c\n", 'Z');```
* Output: ```The last letter in the alphabet is Z```

**Integer**
* Input: ```_printf("There are %i dozens in a gross\n", 12);```
* Output: ```There are 12 dozens in a gross```

**Decimal:**
* Input: ```_printf("%d\n", 542);```
* Output:  ```542```


## Project Requirements
* All files will be compiled on Ubuntu 14.04 LTS
* Programs and functions will be compiled with gcc 4.8.4 using flags -Wall -Werror -Wextra and -pedantic
* Code must follow the [Betty](https://github.com/holbertonschool/Betty/wiki) style
* Global variables are not allowed

## Contributors
[John Aina](https://github.com/johnaina)

[Abdulrahman Oyetade](https://github.com/ola-mide)
