## Collaborative Project
### 1. Objective
* Setup a collaborative working space on github 
* Work as a team to develope printf-like function as mentioned in the following tasks
* Create a manual for the printf function

#### Task-0
Create a printf-like function and handle the specifiers `c`, `s` and `%`.
#### Task-1
Create a printf-like function and handle the specifiers `d`, and `i`.

### 2. File organization
* **main.c** --> Our main function which handles code snippets for testing
* **main.h** --> Defines function prototypes
* **ch_str_percnt.c** --> Handles functions taking care of the specifiers mentioned in Task-0
* **int_dec.c** --> Handles functions taking care of the specifiers mentioned in Task-1
* **_printf.c** --> Handles the overall format of the user-defined printf-like function
* **_putchar.c** --> Used to write to a standard output

### 3. Important Concepts
#### stdarg.h
* `stdarg.h` is a header in the C standard library of the C programming language that allows functions to accept an indefinite number of arguments
* Its contents are typically used in variadic functions
* Variadic functions are functions which may take a variable number of arguments

#### stdarg.h types
* **va_list** --> Type for iterating arguments
* **va_start*** --> Start iterating arguments with a va_list
* **va_arg** --> Retrieve an argument
* **va_end** --> Free a va_list
* **va_copy** --> Copyt contents of one va_list to another



