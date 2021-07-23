# Python Basics

This workshop shows how to get started with the [Python](https://www.python.org), [Flask](http://flask.pocoo.org) and [SQLite](https://sqlite.org/index.html). This workshop is designed for anyone to get started on their local machine.

## Prerequisites

To complete this workshop, you will need:

* [Python 3](https://www.python.org/downloads/).
  
  > If you are using Windows you will need to restart your machine after installing to ensure you can use Python and Pip from the command line.

* [Visual Studio Code](https://code.visualstudio.com/)
* The [Python Extension for Visual Studio Code](https://marketplace.visualstudio.com/itemdetails?itemName=ms-python.python). This can be installed from inside VS Code using the *Extensions* tab.
  ![The Python extension in Visual Studio Code](https://github.com/thecloudranger/python-basics-devance/raw/master/images/Fri_Jul_23_2021_1627028750005.png)

* The [SQLite Extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=alexcvzz.vscode-sqlite). This can be installed from inside VS Code using the *Extensions* tab.
  ![The SQLite Extension for Visual Studio Code](https://github.com/thecloudranger/python-basics-devance/raw/master/images/Fri_Jul_23_2021_1627028835013.png)


* A laptop/PC (with internet connection for intial setup).

This workshop works on MacOS and Windows.

## The Flask SQLite app

## Code format

All code in this sample is shown in code blocks like this one:

```python
print('Here is some code')
```

Ellipses will be used to indicate other code, removed to make new code or the code that is being discussed easier to see. For example a code block like this:

```python
def func():
  ...
  print('end of the suite')
```

means that the `print('end of the suite')` will need to go inside the `func` function, but *after* all existing code in this function

## Steps

The steps for this workshop are:

1. [Build a Hello World python app](./steps/01-hello-world.md)
2. [Create a Flask App](./steps/02-create-flask-app.md)
3. [Create a SQLite Database](./steps/03-create-sqlite-db.md)
4. [Read data from DB and serve over API](./steps/04-read-db-api.md)
5. [Write and save data to DB from API](./steps/05-write-db-api.md)
6. [Clean up](./steps/06-cleanup.md)

## Code

For reference, you can find the final code for this workshop in the [code](./code/) folder.

