# Computer-Science-101
My notes about computer science


###  1. Objectives

* To review the ideas of computer science, programming and algorithms.
* To understand abstraction
* To review the Python programming language


### 1.2 Introduction
Technology has changed our society. It created a huge impact on our lives. Changes in computing technology provided us with a growing number of tools and platforms. Despite this rapid evolution, a number of basic principles have remained constant.

### 1.3 What is computer Science?
Computer science is not a study of computers. It is the study of problems, problem-solving, and the solution to those problems. Given any problem a computer scientist's goal is to create an algorithm, a step-by-step list of instructions for solving any instance of that problem. Algorithms are finite process. Algorithms are solutions.

Computer science focuses on abstraction. Abstraction allows us to view the problem and solution in a way separate from its implementation.

### 1.4 What is programming ?

Programming is the process of implementing algorithms into a notation or program. Programming is the way of creating a representation of algorithms. Without algorithms, a program can not exist.

### 1.5 Data Structures and Abstract Data Types

Computer scientist uses abstraction to manage the complexity of problems and the problem-solving process. Abstraction is the process of creating models of the problem domain. These models allow us to describe the data that our algorithms will manipulate in a much more consistent way.

An abstract data type is a logical description of how we view the data and the operations that are allowed.

The implementation of an abstract data type is referred to as a data structure. It requires a physical view of the data using some primitive data types.


### 1.6 Algorithms

Algorithms are the solution to problems. Algorithms are often different from one way to another. An algorithm can be faster or use fewer resources than others. Algorithms are often evaluated with time and space complexity.


### 1.7 Basics of Python

Python is the most popular programming language in 2019. It is a general-purpose programming language. It is used in different industries and being applied to different tools. It is capable of doing system programming, machine learning, data visualization, web development, automation, scientific computation, datascience, etc.

An example of hello world in python
``` python
print('Hello World')
```


### 1.8 Data types

#### Numeric Datatypes
Python has two numeric data types integer and float. These datatypes have standard arithmetic operations. `+,-,*,/ and **(exponentiation)` . Numeric data types also supports the (modulo) operator `%` and integer division `//`.

An example of how to use arithmetic operators in python.

```python

print(2+3*4)
print((2+3)*4)
print(2**8)
print(7/4)
print(7//4)
print(7%4)
print(3/7)
print(3/6)
print(3//6)
print(3%6)
```
#### Boolean data type.
Boolean datatypes are often use in flow control. There are only two possible value for Boolean. `True` and `False`. Standard boolean operators are `and`, `or`, and `not`.

```python
>>> True
True
>>> False
False
>>> False or True
True
>>> not (False or True)
False
>>> True and True
True
```

Boolean datatypes are also the result of comparision operators such as equality `==` and less than `<`. Logical and comparision operators can be combined to create a complex logical statements.


|Operator Name   	        |  Operator   | Explanation                                                    |
|---	                    |---	        |---          	                                                 |
|less than 	              | <	          |Less than operator                                              |
|greater than   	        | >	          |Greater than operator            	                             |
|less than or equal   	  | <=          |Less than or equal to operator              	                   |
|greater than or equal    | >=          |Greater than or equal to operator              	               |
|equal 	                  | == 	        |Equality operator              	                               |
|not equal	              | !=	        |Not equal operator              	                               |
|logical and              | and         |Both operands True for result to be True              	         |
|logical or	              | or	        |One or the other operand is True for the result to be True      |
|logical not	            | not	        |Negates the truth value, False becomes True, True becomes False |

```python
print(5==10) # False
print(10 > 5) # True
print((5 >= 1) and (5 <= 10)) # True
```

# Containers
`mutable` objects can be modified after creation and `immutable` objects cannot.
* `str` are immutable objects; indexed by integers; items are stored in the order they were added.
* `list` are mutable object; indexed by integers; items are stored in order they were added.
  * `[3, 4, 5, 'cat', dog', False]`
* `tuple` are immutable objects; index by integers; items are stored in the order they were added.
  * `(3, 4, 5, 'dog', 'cat', False)`
* `set` are mutable objects; not index at all; items are *NOT* stored in order they were added; only contain immutable objects; does *NOT* contain duplicate elements.
  * `{ 'Python', 'C#', 'Java', 'JavaScript' }`
* `dict` are mutable objects; key-value pairs are indexed by immutable keys; items are *NOT* stored in the order they were added.
  * `{'name': 'kranz', 'age': '28', 'fav_foods': ['chicken','soup','rice'] }`
