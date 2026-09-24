## 1. DATA TYPES
+ **int:** Stores whole numbers without decimals (e.g., -5, 0, 42). Typically consumes 4 bytes of memory.
- **float:** Stores single-precision floating-point numbers (decimals), usually taking 4 bytes and offering 6–7 decimal digits of precision (e.g., 3.14, -0.001).
- **double:** Stores double-precision floating-point numbers, taking 8 bytes and providing higher precision (about 15 decimal digits) for large or precise numbers.
+ **char:** Stores a single character enclosed in single quotes (e.g., 'A', 'z'), taking 1 byte of memory. Internally, it stores the character's integer ASCII value.
- **bool:** Stores boolean values representing truth states: true (1) or false (0). Note: Requires #include <stdbool.h> in standard C.
+ **void:** Represents the absence of a value or type. It is primarily used to declare functions that do not return a value or functions that take no arguments.

  ## 2. FORMAT SPECIFIERS
+ %d
- %u
+ %o
- %x
+ %X
- %f
+ %e
- %c
+ %s
- %ld
##

## 3. Input/Output Functions
+ **printf():** Formatted Output — Prints formatted text and data values to the standard output (screen) using format specifiers like %d, %s, or %f.
- **scanf():** Formatted Input — Reads formatted data entered from the standard input (keyboard) and stores it into specified variables using memory addresses (&).
+ **getchar():** Single Character Input — Reads a single character from the standard input (keyboard) and returns its ASCII integer value.
- **putchar():** Single Character Output — Writes a single character (passed as an integer or char) to the standard output (screen).
+ **fgets():** String Input — Reads a complete line of text from a stream (like standard input) until a newline character is reached or the buffer size limit is met, making it safe against buffer overflows.
- **puts():** String Output — Prints a null-terminated string to the standard output (screen) and automatically appends a trailing newline (\n).
##

## 4. Escape Sequences
+ **\t:** Inserts a tab in the text.
- **\b:** Inserts a backspace in the text.
+ **\n:** Inserts a newline in the text.
- **\f:** Inserts a form feed in the text.
+ **\\:** Inserts a backslash character in the text.
##

## 5. Precision
Floating-point output precision is specified inside the conversion specifier of printf() (or related functions like sprintf() and fprintf()).
Precision is written as a period (.) followed by an integer, placed between the % symbol and the conversion specifier character (such as f, e, or g).
