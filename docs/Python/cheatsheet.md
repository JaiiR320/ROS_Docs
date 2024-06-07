---
sidebar_position: 2
---

# Python Cheatsheet

In python you can create functions, classes and initialize variables. The goal of each file is to use these tools to do some math, some processes, calculations, whatever you need your code to do, you put it in here. 

## Basic Syntax

### Data Types

In python there are many ways to represent data. 

 - Text Type: 	str
 - Numeric Types: 	int, float, complex
 - Sequence Types: 	list, tuple, range
 - Mapping Type: 	dict
 - Set Types: 	set, frozenset
 - Boolean Type: 	bool
 - Binary Types: 	bytes, bytearray, memoryview
 - None Type: 	NoneType

You can 

### Variables

To create a variable, simply set the name of a variable to a value

```py
yourVariable = 10
```

The data type is implied when you set variables. For example, if we set `yourVariable` to `"hello, world"`, then the data type of `yourVariable` would be a string.

## Main function

The main function is the function that runs when you start your program. All other code inside the file only runs if something within main calls it. For example, if you make a function, it will not run unless that function is called inside main, or if something within main calls it.

```py
if __name__ == "__main__":
	yourCodeGoesHere
```

## Classes
A class is just a way of organizing your code, which allows you to define a container that holds variables, functions and other information. It allows you to refer to the class within the code. 

A basic class setup is like this
```py
class MyClass:
	def __init__(self):
		# yourInitializationGoeshere
		
	def another_func(self, data):
		# another function that does some stuff
```