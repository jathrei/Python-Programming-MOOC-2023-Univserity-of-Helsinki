# Python-Programming-MOOC-2023-Univserity-of-Helsinki-PART1_Notes

## Strings, inputs and variables, print statements, integars, floats
## f-strings, 
strings are sequence of characters, either literal constant or variable. printed out in python using print("string")

python also accepts ' in the print("") instead of "

variables can store a value like a string or a number

can print out a variable combined with a string using a plus

## print
prints work like -- print("print this" + this + name + "!"), variables this and name are variables duh
inputs work like -- this=input("input this: ")
if the print command is given an additional argument end = "", it will not print a line change.

adding strings together -- name = first_name + " " + last_name

For integer values the + operator means addition, but for string values it means concatenation, or "stringing together".

combining values when printing: the following program will not work, because "The result is " and result are of two different types:
result = 10 * 25
#the following line produces an error
print("The result is " + result)
TypeError: unsupported operand type(s) for +: 'str' and 'int'

must fix it by using +str(result)
also ,result works: print("The result is", result)
**Notice that there is an automatically added whitespace character between the values separated by a comma here.

## printing f-strings:
the f after the print statement tells python that its an f-string, the { } values are concatenated to the string
print(f"Hi {name}, you are {age} years old. You live in {city}.")

**Hint: you can print an empty line by adding an empty print command, or by adding the newline character \n into your string.


## floating point
floating point numbers: numbers with a decimal point
if you have integers and do division, it returns a floating point
