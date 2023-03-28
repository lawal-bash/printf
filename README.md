An ALX team project for the printf.
Collaboration between Ruth Ambogo & Lawal Olatunji 

The goal was to create the printf function (using man printf as guide).

Printf() function is used on Linux and any other terminals to prints output to stdout, inline with the format and other arguments passed to printf(). The string format consists of two types of items; 1. characters that will be printed to the screen, and 2. formatted commands that define how the other arguments to printf() are displayed. 
To achieve this, a format string that has text in it, as well as special characters that map to the other arguments of printf().

Prototype deployed: int _printf(const char format, ...);

Below are definitions of files created for Printf Projects;

main.h
A header file that conains all prototypes for printf function

printf.c
The entry point for the printf

functions.c
This file includes codes that prints binary representation using %b
custom implementation of the inbuilt putchar
code that prints string using %s
code that prints interger using %d and %i and 
code that prints the percentage sign % that will be used in the handle specifier 


functions1.c
This file includes codes for printing an unsigned number using 
code for printing unsigned number in octal using %o
code for printing unsigned number in hexadecimal 
code for printing unsigned number in upper hexadecimal 
code for Printing a hexadecimal number in lower or upper using %x and %X


functions2.c
This file contains 
codes for printing pointers using %p
codes for Printing ascii codes in hexadecimal  of non printable characters
codes for printing a reverse string using %r
codes for Printing a string in rot13.


get_flags
An implementation that extracts the formatting flags from the format string


get_precision
This file contains code that extracts precision from the format string


get_size
This file contains code that will help in the implementation of printf when you need to handle the size modifier field in the format string


get_width
This file contains code that will help in handling the width and precision fields in the format string


Write_handlers.c
this file contains codes for
printing a string using %s
printing a number

Handle print
This files contains codes for printing arguments based on type

utils.c
This file contains code that holds macros to support the implementation of printf function
