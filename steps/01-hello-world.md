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
This should return `hello world`.

Things to note:

- The hash `#` symbol is used for comments. Anything after this on that line is ignored by python.
- The function is defined using `def`.
- The function has a name `hello_world`.
- The next line is indented to show it is inside the function.
- The function is called by last line `hello_world()`.

### Returning information from a function

When a function performs some kind of activity, by default the information it remains contained within the boundary of the function. To pass the information to other parts of your code, you need to use `return`. The value the function returns is called the ***return value*** and it is passed back to the line which called the function.

Modify `hello_world.py` as follows:

```python
# A function that returns hello world
def hello_world():
    return 'hello world'

# Assign the hello_world() function to a variable.
greeting = hello_world()
print(greeting)
```

Here's what python does:
- In the first example, python calls the `hello_world()` function and prints out the string using `print(hello_world)`.
- In the second example, python assigns the `hello_world()` function to a variable and stores the returned value.


## Next Steps
In the [next step](./02-create-flask-app.md) you will create a simple Flask Web App.