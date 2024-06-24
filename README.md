[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15317201&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
- What is Python, and what are some of its key features that make it popular among developers?
   - Python is a high-level, interpreted programming language known for its readability and simplicity, making it ideal for both beginners and experienced developers. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming, and is widely used for web development, data analysis, artificial intelligence, and scientific computing.
  
- Provide examples of use cases where Python is particularly effective.

 - **Web Development** - Frameworks like Django and Flask make it easy to build robust web applications.
 - **Data Analysis and Visualization** - Libraries such as Pandas, NumPy, and Matplotlib allow for efficient data manipulation and visualization.
 - **Machine Learning and AI** - Tools like TensorFlow, Keras, and scikit-learn support the development of machine learning models and artificial intelligence applications.
 - **Scientific Computing** - Packages such as SciPy and SymPy provide powerful tools for scientific and mathematical computations.
 - **Automation and Scripting** - Python's simplicity and versatility make it ideal for automating repetitive tasks and writing scripts to manage system operations.
 - **Game Development** - Libraries like Pygame enable the creation of 2D games and multimedia applications.
 - **Network Programming** - Python's built-in libraries, like socket and asyncio, facilitate the development of network applications and services.
 - **Web Scraping** - Libraries such as BeautifulSoup and Scrapy are used for extracting data from websites.

3. Installing Python:
- Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
 - Go to the official Python website (python.org) and download the latest Python installer for Windows.
 - Execute the downloaded installer, check "Add Python to PATH," and choose "Install Now."
 - Open Command Prompt and type python --version to verify the installation.
 - In Command Prompt, run python -m pip install virtualenv to install the virtual environment package.
 - Navigate to your project directory and run python -m venv venv to create a virtual environment named "venv."
 - Navigate to your project directory and run python -m venv venv to create a virtual environment named "venv."

5. Python Syntax and Semantics:
- Write a simple Python program that prints "Hello, World!" to the console.
```
 print("Hello, World!")
```
- Explain the basic syntax elements used in the program.

 1. **print** - This is a built-in Python function used to output text or other data to the console.
 2. **(** - This opening parenthesis starts the argument list for the `print` function.
 3. **"Hello, World!"** - This is a string literal, enclosed in double quotes, which represents the text to be printed.
 4. **)** - This closing parenthesis ends the argument list for the `print` function.

7. Data Types and Variables:
 - List and describe the basic data types in Python.
 - interger - Represents whole numbers without a fractional component.
 - Float - Represents real numbers with a fractional component.
 - String - Represents a sequence of characters enclosed in single, double, or triple quotes.
 - Boolean - Represents one of two values: True or False.
 - List - Represents an ordered collection of items which can be of different types, enclosed in square brackets.
 - Tuple - Represents an ordered collection of items, similar to lists, but tuples are immutable (cannot be changed) and enclosed in parentheses.
 - Dictionary - Represents a collection of key-value pairs, enclosed in curly braces.
 - Set - Represents an unordered collection of unique items, enclosed in curly braces.

- Write a short script that demonstrates how to create and use variables of different data types.
```
 # Numeric data types
 num1 = 5
 print(num1, 'is of type', type(num1))  # Output: 5 is of type <class 'int'>
 
 num2 = 2.0
 print(num2, 'is of type', type(num2))  # Output: 2.0 is of type <class 'float'>
 
 num3 = 1 + 2j
 print(num3, 'is of type', type(num3))  # Output: (1+2j) is of type <class 'complex'>
 
 # List data type
 languages = ["Swift", "Java", "Python"]
 print("First language:", languages[0])  # Output: First language: Swift
 print("Third language:", languages[2])  # Output: Third language: Python
 
 # Tuple data type
 product = ('Xbox', 499.99)
 print("Product name:", product[0])  # Output: Product name: Xbox
 print("Product price:", product[1])  # Output: Product price: 499.99
```

8. Control Structures:
- Explain the use of conditional statements and loops in Python.
 - Conditional statements allow you to make decisions in your code based on certain conditions. They control the flow of your program by executing specific blocks of code depending on whether a condition is true or false.
 - Loops allow you to repeat a block of code multiple times. They are essential for tasks like iterating over lists, processing data, and creating patterns.

- Provide examples of an `if-else` statement and a `for` loop.
```
 x = 3
 if x == 4:
     print("Yes")
 else:
     print("No")
```
```
 fruits = ["apple", "banana", "cherry"]
 for fruit in fruits:
     print(fruit)
```
9. Functions in Python:
- What are functions in Python, and why are they useful?
 - Functions in Python are blocks of reusable code that perform a specific task. Functions allow you to write a block of code once and reuse it multiple times throughout your program, promoting DRY (Don't Repeat Yourself) principles.

- Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
   ```
    def add_numbers(a, b):
     return a + b
    result = add_numbers(3, 5)
    print(f"The sum of 3 and 5 is: {result}")
   ```

10. Lists and Dictionaries:
- Describe the differences between lists and dictionaries in Python.
 - **Structure** - Lists are ordered collections of items, whereas dictionaries are unordered collections of key-value pairs.
 - **Syntax** - Lists are defined using square brackets (`[]`), while dictionaries are defined using curly braces (`{}`) with keys and values separated by colons.
 - **Indexing** - List elements are accessed by their position (index), whereas dictionary values are accessed using unique keys.
 - **Order** - Lists maintain the order of elements as they were added, while dictionaries (since Python 3.7) maintain insertion order but were unordered before that.
 - **Mutability** - Both lists and dictionaries are mutable, meaning their contents can be changed after creation.
 - **Use Cases** - Lists are typically used for ordered sequences of items, while dictionaries are used for associating unique keys with values.
 - **Performance** - Accessing elements in a list by index is generally faster than accessing values in a dictionary by key, but dictionary lookups are optimized for key-based access.
 - **Duplicates** - Lists can contain duplicate values, but dictionary keys must be unique.

- Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

```
 numbers = [1, 2, 3, 4, 5]
 
 
 my_dict = {
     'name': 'Alice',
     'age': 30,
     'city': 'Seattle'
 }
 
 print("List of numbers:", numbers)
 print("Dictionary:", my_dict)
 
 print("First number:", numbers[0])
 print("Age of the person:", my_dict['age'])
```


12. Exception Handling:
- What is exception handling in Python?
 - Exception handling in Python allows you to gracefully handle errors that occur during program execution. When an error occurs, Python raises an exception, which can be caught and handled using try, except, else, and finally blocks.
  
- Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
  ```
   try:
     num = int(input("Enter a number: "))
     result = 10 / num
 except ZeroDivisionError:
     print("Cannot divide by zero.")
 except ValueError:
     print("Invalid input. Please enter a valid number.")
 else:
     print(f"Result: {result}")
 finally:
     print("Execution completed.")
``` 

13. Modules and Packages:
- Explain the concepts of modules and packages in Python.
 - A module in Python is a single file that contains Python code. It can include functions, classes, variables, and executable statements.
 - A package is a collection of related modules organized in a directory structure.

- How can you import and use a module in your script? Provide an example using the `math` module.
 ```
  import math
 
  def square_root(number):
     """Calculate the square root of a number."""
     return math.sqrt(number)
 ```

11. File I/O:
- How do you read from and write to files in Python?

 **Reading a file**
   open('filename', 'r')
   read(), readline(), readlines()
   close()

**Writing a file**
 open('filename', 'w') for writing (overwrites)
 open('filename', 'a') for appending
 write(), writelines()
 close()
 Or use with open('filename', 'w') as file
 Or use with open('filename', 'r') as file

- Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

```
 with open('file'.txt', 'r') as file:
     content = file.read()
     print(content)
```
```
 with open('file.txt', 'w') as file:
     file.write("Hello, World!\n")
 
 with open('file.txt', 'a') as file:
     file.write("This is an appended line.\n")
```

**References**
https://www.python.org/doc/
https://www.geeksforgeeks.org/python-programming-language-tutorial/


# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


