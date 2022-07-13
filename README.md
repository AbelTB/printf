.TH man 3 "13 July 2022" "0.01" "_printf man page"

.SH NAME

.B _printf

- A simple re-creation of the printf function

.SH SYNOPSIS

To use this function the #include "main.h" header is needed.

.SH DESCRIPTION

The _printf() function produces output according to a format which is described

below. This function write its output to the stdout, the standard output stream.

.SH USAGE

To use _printf you have to use the following key characters preceeded by % symbol.

.RS 3

%c: To be used to print characters

.RS 0

%s: To be used to print strings

.RS 0

%d: To print integers of max and min size of an int type

.RS 0

%i: To print integers of max and min size of an int type

.RS 0

%b: To print a number in binary form

.SH RETURN VALUES

The _printf() function returns an integer representing the number of symbols

printed not counting \\0 for the string.

.SH SEE ALSO

.I printf(3)

.SH BUGS

No known bugs.

.SH AUTHOR
Yohannesteshome and AbelTB
