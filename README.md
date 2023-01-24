Printf project is the first group project consisting of two patners in corhort 11, which consists  replicating the printf (3) function of language in c, 

THE FUNCTIONS:
This function is part of the standard library and to use it we must specify it in the header file <stdio.h>.

Writes the C string pointed by format to the standard output (stdout). If format includes format specifiers (subsequences beginning with %), the additional arguments following format are formatted and inserted in the resulting string replacing their respective specifiers.

Parameters
format -> C string that contains the text to be written to <stdout>

Where the specifier character at the end is the most significant component, since it defines the type and the interpretation of its corresponding arguments.

RETURN VALUE:
On success, the total number of characters written is returned. If a writing error occurs, the error indicator is set.

Tasks
0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life

Write a function that produces output according to a format.

Prototype: int _printf(const char *format, ...);
Returns: the number of characters printed (excluding the null byte used to end output to strings)
write output to stdout, the standard output stream
format is a character string. 

1. Education is when you read the fine print. Experience is what you get if you don't
mandatory
Handle the following conversion specifiers:

d
i
You don’t have to handle the flag characters
You don’t have to handle field width
You don’t have to handle precision
You don’t have to handle the length modifiers

2. With a face like mine, I do better in print
3. What one has not experienced, one will never understand in print
4. Nothing in fine print is ever good news
5. My weakness is wearing too much leopard print
6. How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print
7. The big print gives and the small print takes away
8. Sarcasm is lost in print
9. Print some money and give it to us for the rain 
10. The negative is the equivalent of the composer's score, and the print the performance
11. It's depressing when you're still around and your albums are out of print
12. Every time that I wanted to give up, if I saw an interesting textile, print what ever, suddenly I would see a collection
13. Print is the sharpest and the strongest weapon of our party
14. The flood of print has turned reading into a process of gulping rather than savoring

COMPILATION:
All of the .c files along with a main.c file are to be compiled with gcc 4.8.4 on Ubuntu 14.04 LTS with the flags -Wall Werror -Westra and -pedantic.
The files will be compiled this way:
gcc -Wall -Werror -Wextra -pedantic *.c

CONTRIBUTORS:
Owoyomi Taiwo (Eto4God)
Chidera Onyekachi (ChideraDev)
