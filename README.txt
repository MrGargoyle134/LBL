--LBL Documentation--

Run a LBL program:
$ lbl file.lbl

An LineByLine program have 6 variables: A, B, C, D, E and F.

DIS-variable -> print the value of a variable.
Example: DISA
DIC-variable -> print the ascii value of a variable.
Example: DICC
INC-variable -> increment the value of a variable.
Example: INCF
DEC-variable -> decrement the value of a variable.
Example: DECB
CLS-variable -> put the value of a variable to 0.
Example: CLSD
EQ-variable1-variable2 -> put the value of a variable as the value of another variable.
Example: EQDA
ENDL -> print a \n