# Build a Hello World python app

## Getting started
* Create a new python file named `hello.py`.
  
## Variables

A variable is a value that can change. They can be used to store information that can be referenced and used by programs. Instead of using the stored value directly, we can use the variable instead. Variables could be any number of things, such as, a string of text, a list or an object. Using variables makes our code flexible and reusable. Without variables we would have to hard code all our values into the code.

Variable names are defined when you declare them. The convention for variable names is set out in pep8, the style guide for python. They should be lowercase, with words separated by underscores as necessary to improve readability.

Variables in python are declared in the format name = value. In python we can store different types of data without having to be explicit about the type when we declare it.

Below are some examples:
```python
a_str = "This is an example of a string in quotes" # In python the word string is abbreviated to str
my_float = 5.5
an_integer = 5 # integer is abbreviated to int
shopping_list = ["apples", "oranges", "pears"]
a_dict = {"userId": "JBloggs"} # dictionary is abbreviated to dict
my_var = another_variable # variable is abbreviated to var
test_function = my_function() #function is abbreviated to func
example_tuple = ("apple", "orange", "pear")
boolean_values = True # boolean is abbreviated to bool
```

## Data Types

In this section we look at data types. The computer needs to know whether a variable is a string or a number or another type of data. This to prevent mistakes like attempting to add a string `"Alice"` to a number `5`.

## Functions

A function is a named section of a program which performs a specific task. Functions add flexibility to code like variables because they are reusable, which reduces the amount of code we have to write.

In python we can declare a function using the syntax `def function_name():`
A function begins with `def`, has a name in lower case, with words separated by underscores to improve readability, a set of `()` which contain parameters (more on this later) and ends in `:`.

Here is a very simple function that when it is called will return `hello world`.

``` python
# A function that prints hello world
def hello_world():
    print('hello world')

# This line calls (runs) the function
hello_world()
```
Save the file using `file > save` or `command + s`.

To run the program, enter the following command in the terminal:
```sh
python hello.py
```


##

## Next Steps
In the [next step](./02-create-flask-app.md) you will create a simple Flask Web App.