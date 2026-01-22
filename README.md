Nov 12, 2025 at 3PM:

Python Course:

1. to zoom out the vs code: cntrl+*+

few settings in VS code:

2. to change theme of vs code: settings->theme->colors

3. to zoom in and zoom out the lines of code using mouse wheel: settings->settings->search for mouse->check the checkbox of zooming

Indentation: Indentation is used whether the lines of code are inside a block.

Variables and Data Types: 1

Variables: Variables are used to store the data, and the value is assigned to a variables using a assignment operator. Note: Python is a Dynamic type programming language, because we no need to explicitly define the type of variable for it, python interpreter understands by itself whether the variable is int, string, float and Boolean.

Rules of defining variables in python:
1. variables can starts with lower and upper case letters and underscore.

2. it can contains numbers

3. it should not have any special characters

4. variable names are case sensitive means (age and Age both are different)

Datatypes in python:

1. Integers (int): whole numbers (e.g., 10, 6)

2. Float (float): Decimal numbers (e.g., 7.89, 9.80)

3. String (str): Text data enclosed in inverted commas (e.g., "spandana")

4. Boolean (bool): Represents True or False

To get the what is the datatype of variable is: typeofvariable type(age) or print(type(age))

To define and declare the variables: age =25

To get the what is the datatype of variable is: typeofvariable type(age) or print(type(age))

for e.g.: convert of variable from int to string a- 1

Typecasting in Python: Converting the variable from one datatype into another data type.

b- str(1)

print(b) # output: "1"

Conversion of int to bool

a 1

b- bool(1)

print(b) # output: True (in Boolean 0 is considered as False, 1 is considered as True)

Taking user input in python:

In python, by default the user input is a string ex: a input("enter a number")

so, when the user enter a number the datatype of a is string

to convert it, we can use type casting

ex: a int(input("enter a number")

b- int(input("enter a second number")

catb

Note: if we want type any text or something other else in vs code, click "alt" and place your cursor at where you want to write, click alt and cursor at same time. then you are able to write text one time at multiple place, don't go to each line and type same thing again and again.

print(c)

Comments: Comment are used to inform about the code to fellow developer or any identification purpose

single line comments are used with #, select all line and press cntrl+/ all line will comment with # Multi Line Comments: encloed them with triple single line quotes. enclosing in triple line quotes"

Typecasting in Python: Converting the variable from one datatype into another data type.

Escape Sequence characters: Escape sequence characters are used to include special characters in strings \n: it prints newline ex: print("hello world \n spandana")

output: hello world

spandana

\t: tab

": it prints double inverted commas b/w two string or two words

': it prints single inverted commas b/w two string or two words

Print statement: print is a function, we can write print in single quotes as well. to separate the strings in print statement by commas we can use sep"," ex: print("hello world", "spandana", sep ",") #output: hello world, spandana by default if we haven't give spaces, it prints spaces b/w words.

Dec 8th 2025:

1. Arithmetic Operators: addition(+), subtraction(-), multiplication(), Division(/), Modulus(%), Exponential (*), Floor Division(//)

Operators in Python:

floor division means after dividing a number, it removes the quotient values after decimal point, for ex: 34/2 17.0, if we do 34//2, the output is 17, so it removes

dot 0.

2. Comparison Operators: less than(<), greater than (>), not equal to (!)

3. Logical Operators: and or not, logical operators works on Boolean values

AND: if both values are true, output is true.

if any one of the value is false, output is false. if both values are false, output is false.

if both values are true, output is true.

OR: OR is opposite to AND

if any one of the value is true, output is true.

if both values are false, output is false.

NOT: not(false) true, not(true) false, if we want negate the true or false, we can use not operator.

4. Assignment Operators: ", +,,,,,**, //- ex: a+-3 means a-a+3

Conditional statements: conditional statements are used to execute the code based on certain conditions

1. if else: if statement condition is true, then the lines of code within if block executes, if not, else block lines of code will execute.

ex: a= 35

if a>18:

print("you can drive")

else:

print("you can't drive")

output: you can drive, because 35 is greater than 18, if condition is true.

2. if elif else: if elif condition is used to check multiple conditions after if statement.

Match statement: it is same as switch statement. when we have multiple conditions we can go for switch statement.

ex: a int(input(enter number b/w 1 to 10")

match a:

case 1:

print("yes you won TV")

case 2:

Loops: loops are used to do the repetitive tasks. iterate the items in sequence, there are two types of loops in python, for loop and while loop.

print("you won $3")

case:

print("better luck next time")

I

for loop:

syntax: for i in range(1, 10):

print the code

ex: if I want to print 5 table

for i in range(1, 11):
print(5*i)

range function goes from first number and second number -1

print("5 x ", i, "-" 5*1)

while loop: while loop is execute the code as long as condition is True, they are useful when the number of iteration are not known in advance.

syntax: while condition:

code execute while condition is true.

ex: a 0

while(a<5):

print(a)

a+=1

Infinite Loops: when we want to print something infinitely.

ex:

1-1

while True:

print(1)

1+-1

ouput: it prints go on....

I

break: break statement is used to break the loop, cancel the execution of code.

ex: for i in range(10):

if 15:

break

print(i) output: 0,1,2,3,4

continue: continue statement skips the rest of code under it, and move to the next iteration.

for i in range(10):

if i==5:
continue
print(i) output: 0,1,2,3,4,6,7,8,9

