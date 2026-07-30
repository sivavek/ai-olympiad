Python Programming for Middle Schoolers
=======================================

# Table of Contents

1. Welcome to the World of Python
  1.1 Why is Python easy to learn?
	1.2 Where is Python used?
	1.3 First Python Program
	1.4 How to add Comments
	1.5 What is Input in Python?
	1.6 How to Take Input in Python?
	1.7 What is a Variable?
	1.8 How to Create a Variable in Python?
	1.9 Rules for Variable Names
	1.10 Data Types in Python
   
2. Arithmetic Operators
3. Conditional Statements in Python
	3.1 What are Conditional Statements?
4. Loops in Python
	4.1 for loop
	4.2 while loop
5. Strings in Python
	5.1 What is a String?
	5.2 String Operations
	5.3 String Functions (Methods)
6. Lists in Python
	6.1 Creating Lists
	6.2 Accessing Elements (Indexing)
	6.3 Adding Elements to a List
	6.4 Removing Elements from a List
7. Introduction to Tuple, Set & Dictionary
	7.1 What is a Tuple?
	7.2 What is a Set?
	7.3 What is a Dictionary?
8. Functions in Python
	8.1 What is a Function?
	8.2 Why Use Functions?
	8.3 How to Create a Function in Python?
	8.4 Calling a Function
	8.5 Functions with Parameters
	8.6 Functions with Return
9. Basic Python Problems
	9.1 Section I: Code Reading
	9.2 Section II: Practice Problems

# 1. Welcome to the World of Python
Ever wondered how apps like Instagram and YouTube work, or how self-driving
cars make decisions? A lot of that magic is powered by Python
History of Python
Python is a popular, high-level programming language created by Guido van
Rossum at the Centrum Wiskunde & Informatica (CWI) in the Netherlands.
Development began in the late 1980s and Python was first released publicly in
1991 as version 0.9.0.
Key milestones in Python's history:
• 1989: Guido van Rossum started the development of Python as a
successor to the ABC programming language, aiming for a language that
is easy to read and use.
• February 1991: Python 0.9.0 released, including important features such
as exception handling, functions, and modules.
• January 1994: Python 1.0 released with added features like lambda
functions, map/filter, and support for complex numbers.
• October 2000: Python 2.0 introduced list comprehensions, garbage
collection, and other major enhancements.
• December 2008: Python 3.0 released, breaking backward compatibility to
fix language flaws and improve consistency. This led to a transition period
where many projects migrated from Python 2 to Python 3.
Spent S
Part of Accenture
• Present: Python has grown to be one of the most popular programming
languages worldwide due to its simplicity, large standard library, and wide
use in web development, data science, artificial intelligence, automation,
and education.
Reasons Behind Python's Popularity:
• Easy-to-read, English-like syntax that lowers the barrier to programming
• Extensive support libraries and active open-source community
• Versatility for scripting, web applications, scientific computing, machine
learning, and more
• Cross-platform support on Windows, Linux, macOS, and mobile platforms
One fun fact about Python is that the language's name was inspired not by the
snake, but by the British comedy TV show "Monty Python's Flying Circus." Guido
van Rossum, the creator of Python, was a fan of the show and wanted a name
that was short, unique, and slightly mysterious, hence "Python"
1.1 Why is Python Easy to Learn?
• Simple English-like language
• No semicolons or curly braces
• Write less code, do more work
• Free and open source
1.2 Where is Python Used?
• Games like Snake and Flappy Bird
• Apps & Websites like Instagram and YouTube
• Artificial Intelligence (AI) and Robotics
Spent S
Part of Accenture
1.3 First Python Program
print("Welcome! Learn Python")
1.4 How to Add Comments
• Single-line comment: Use #
..."**
• Multi-line comment: Use triple quotes "''*
# This is a single-line comment
This is a
multi-line comment.
1.5 What is Input in Python?
Input means taking information while the program runs, e.g., asking for your
name or numbers.
1.6 How to Take Input in Python?
Using input:
name = input("Enter your name: ")
print("'Hello", name)
Important: Inputs through input() are strings by default. Convert to
numbers when needed:
age = int(input(Enter your age: "))
print("You are", age, "years old.")
Example: Adding Two Numbers (correctly)
Part of Accenture
a = int(input("Enter first number: ")
b = int(input("Enter second number: ")
print("Sum is:", a + b)
1.7 What is a Variable?
A container that stores information such as numbers or text.
1.8 How to Create a Variable
name = "Akash"
age = 13
score = 100
1.9 Variable Naming Rules
• Can contain letters, numbers, underscores
• Cannot start with a number
• No spaces allowed
• Case-sensitive
1.10 Data Types in Python
• int: whole numbers
• float: decimal numbers
• str: text/string
• bool: True or False
talent s
Part of Accenture
Example:
name = "Rahul" # string
# integer
age = 12
#float
height = 4.8
is_student = True # boolean
print(name, age, height, is_student)
2. Arithmetic Operators
Meaning
Example
Operator
+
a + b
Addition
a - b
Subtraction
*
Multiplication
a * b
Division (float)
a / b
/
Floor Division
a // b
//
Modulus (remainder)
a % b
**
a ** b
Exponent (power)
Example:
a, b = 10, 3
print("Sum:", a + b)
print("Difference:", a - b)
print("Product:", a *b)
print("Division:", a /b)
print("Floor Division:", a / / b)
print("Remainder:", a % b)
Part of Accenture
print ("Power:", a ** b)
3. Conditional Statements in Python
Conditional statements help your program choose actions:
Syntax:
if condition:
# code if true
elif another_condition:
# code if another condition true
else:
# code if all false
Example:
age - int(input("Enter your age: "))
if age >- 18:
print("You can vote!")
else:
print("You are too young to vote.")
4. Loops in Python
4.1 For Loop
Repeats a fixed number of times:
for i in range(1, 6):
print(i)
Part of Accenture
4.2 While Loop
Repeats while a condition is True:
i = 1
while i <= 5:
print(i)
i += 1
5. Strings in Python
5.1 What is a String?
A sequence of characters in quotes: "Hello" or 'Python'
5.2 String Operations
Concatenation and repetition:
print("Hello" + " " + "World")
print("Hi" * 3)
5.3 String Functions
Method
Description
Output
Example
"HELLO"
Convert to
upperi
"hello". upper
uppercase
"HELLO".lower()
"hello"
Convert to
lower)
lowercase
"Hello World"
"hello
Title case each
title(
word
world".title0
"hi"
Remove spaces
stripl
"hi "stripl
Pant ot Assonture
"Apple"
"apple". replace'a
Replace
replace(a,b)
", "A")
substring
"a,b,c". split", ")
Split into list
spliti
l'a', b', 'c]
6. Lists in Python
6.1 Creating Lists
fruits - ['apple", "banana", "mango"]
6.2 Accessing Elements
Index starts at 0:
print(fruits(O]) # apple
print(truits -1]) # mango
6.3 Adding Elements
fruits.append("orange")
6.4 Removing Elements
fruits.remove("banana")
# removes last
fruits.pop0
# removes first
fruits.pop(0)
7. Introduction to Tuple, Set & Dictionary
Part of Accenture
7.1 Tuple
Immutable list:
colors = ('red", "green", "blue")
7.2 Set
Unordered collection of unique items:
unique_colors = ('red", "blue", "green", "red") # duplicates removed
7.3 Dictionary
Collection of key-value pairs:
student = ('name": "Rahul", "age": 13)
print(student['name"]) # Rahul
8. Functions in Python
8.1 What is a Function?
A reusable block of code with inputs and outputs.
8.2 Why Use Functions?
• Reuse code
• Organize programs
• Avoid repetition
8.3 How to Create a Function
Part of Accenture
def greet):
print(Hello!")
8.4 Calling a Function
greet)
8.5 Functions with Parameters
def greet(name):
print("Hello", name)
greet ("Alice")
8.6 Functions with Return Value
def add(a, b):
return a + b
result = add(3, 5)
print(result) # 8
9. Basic Python Problems
9.1 Section I: Code Reading
Predict outputs of small code snippets
1. print(5 + 3 * 2)
Solent s
Part of Accenture
2. print('Hello' == 'HELLO')
3. print(11 != 12 and 6 > 11)
4. print(10 + 6 * 2** 2 != 9 / / 4 - 3 and 29 >= 29 / 9)
5. print(3 % 10 + 10 < 30 and 78 < 89)
6. print((4 < 6) or (not (10 = = 6) and (10 < 4)))
7. a = 10
b = 5
a, b = b, a
print(a, b)
8. × = "Python"
print(x(0], x[-1])
print("Hello" + "World")
print("Hello" * 3)
9. x = 5
y = x
× = 10
print(y)
print(2 ** 3 ** 2)
10.
11.
def greet(name="User"):
print("Hello", name)
art of Accenture
greet)
greet("Alice")
12.
a = [1,2,3)
print(a.pop), a)
13.
x = 5
printx > 3 and x < 10)
printx < 3 or x> 10)
9.2 Section II: Practice Problems
• Write programs for displaying info, arithmetic operations, conditionals.
• Write functions to compute areas, reverse strings, multiplication tables, etc.
• Practice sorting, palindrome checks, second largest number, prime checks.
• Advanced problems: counting frequency, removing duplicates, vowels
counting, Armstrong numbers, etc.
**

