# Python-Programming-MOOC-2023-Univserity-of-Helsinki-PART1_Notes

## Strings, inputs and variables, print statements, integars, floats
## f-strings, conditional statements, boolean
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

## Operator	Purpose	Example	Result

(+)	    Addition	2 + 4	6

(-)	    Subtraction	10 - 2.5	7.5

(*)	    Multiplication	-2 * 123	-246

(/) 	Division (floating point result)	9 / 2	4.5

(//)	Division (integer result, rounds down)	9 // 2	4

%	Modulo	9 % 2	1

**	Exponentiation	2 ** 3	8

if a single one of the operands in an expression is a floating point number, the result will also be a floating point number, regardless of the other operands.


## int as an input, or float
the default input takes a string.

input_str = input("enter number: ")

num = int(input_str) 

orrr direct conversion: year = int(input("Which year were you born? "))

for floating point just do float instead of int before the input

## +=, *=
sum += 5 == sum = sum + 5

sum *= 5 == sum = sum*5


its saying the new sum is the old sum + 5

## CONDITIONAL STATEMENTS
: (colon) used after conditonal statement

python uses indentation to determine what is in the block of code for the conditional statement


Operator	Purpose	Example

==	Equal to	a == b

!=	Not equal to	a != b

(>)	Greater than	a > b

(>=)	Greater than or equal to	a >= b

<	Less than	a < b

<=	Less than or equal to	a <= b


if(name=="Jerry") ----> comparing the string Jerry to the variable string name

## Boolean data types

true or false, 1 or 0


a = 3

condition = a < 5

print(condition)

if condition:

    print("a is less than 5")



## The else if (elif)
elif - "if the previous condition didn't execute, try this condition. Otherwise, move on"




end part1
