# Strings it (100 points) - picoCTF 2019

## Description

Can you find the flag in file (strings) without running it?

### strings
![file: strings](https://github.com/Kaminaru/picoCTF-writeups/blob/main/strings%20it/strings)

## Solution
We can use command:
strings <filename> , that prints the strings of printable characters in the file and pipe it to the grep command. (We also know that flag contains picoCTF{ at the start)

Command will do the work:

strings strings | grep picoCTF 


**Flag**: picoCTF{5tRIng5_1T_7f766a23}
