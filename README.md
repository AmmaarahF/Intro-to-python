# Intro-to-python

- Python has been around for thirty years and has seen a consistent rise in popularity.
- Unlike JavaScript, Python is praised for its elegance and consistency in syntax.
- Python is not just for beginners; it is used in developing complex systems due to its ability to handle complexity effectively.
- The "import this" statement serves as a hidden mission statement, emphasizing Python's focus on simplicity and readability.
- To access the Python command prompt, open a terminal and type "Python", where three greater-than symbols indicate readiness to accept Python code.

How to create a python program 
-----------------------------------
- Create a new file named "hello.py" with the .py extension.
- Add the following single line of Python code to print "Hello, World!": print('Hello, World!')
- Use single quotes to enclose the text string.
- Add a comment using the hash symbol (#) to remind yourself or other programmers about the purpose of the line of code.
- Comments serve as helpful explanations for code functionality.
- Save the file before proceeding.
- Navigate to the terminal or command prompt.
- Use the "cd" command to change directory to where the file is stored.
- Run the "hello.py" program using the command "python hello.py".
- Alternatively, type "h" and tab for autocomplete if the file name is unique.
- Upon running the program, the text "Hello, World!" will be printed to the screen.

Jupyter Notebooks
----------------------
- <b>Jupyter Notebooks:</b> Utilized for programming work in the course.
- <b>Project Jupyter:</b> A non-profit organization developing Python tools.
- <b>Jupyter Notebook:</b> Web application allowing writing and executing Python code in the browser.
- <b>Launching:</b> Initiated from the command line, it starts a web application server, opening in the browser automatically.
- <b>File Structure</b>: Shows a list of files, with ipynb files indicating Jupyter Notebook files.
- <b>Notebook Usage:</b> Popular for data science, presenting findings, creating charts, and sharing results.
- <b>Creating Notebooks:</b> Click "new" then select "Python 3" to create or open an existing notebook.
- <b>Functionality:</b> Used for experimentation, creating reports with code, and teaching Python efficiently.
- <b>Exporting:</b> Notebooks can be exported in various formats for sharing.
- <b>Cell Creation and Deletion:</b> Cells can be created with shift + enter and deleted with command mode + dd.
- <b>Entering Code:</b> Click inside a cell to enter edit mode and start typing Python code.
- <b>Running Code</b>: Execute code by holding shift and pressing enter.
- <b>Adding Cells:</b> Use keyboard shortcuts A or B in command mode to add cells above or below.
- <b>Markdown Cells:</b> Created with M in command mode, used for adding text, titles, and math equations.


Variables and Types
----------------------------
- Variables are basic units of programs, assigned values with equal sign.
- Jupyter Notebook shortcuts: Shift + Enter to run cells, 'a' to insert new cell.
- Variable naming rules: No starting with numbers, lowercase tradition.
- Variable types include integers, floats, complex numbers, strings, and booleans.
- String concatenation uses plus sign; cannot add strings and numbers.
- Error messages offer helpful information for debugging.

Data Structures
----------------------------
- Data structures allow for the storage of a list of values in a single variable.
- a list can contain any data type, including a list within a list
- The length of a list can be determined using the length function.
- A set is similar to a list, except it only contains unique elements and is declared using curly braces. 

Operators
---------------------------
- Operators are instructions that perform operations on variables and values in Python.
- They are used to manipulate and perform actions on data.
- eg. 1 + 1 // Output will be 2 


Control Flow
-----------------------------
- The if statement is one of the three main types of control flow in programming, and it allows you to execute a block of code only if a certain condition is met.
- In Python, you use the if statement like this: "a = True, if a: print It is true." 
> If the condition is true, the indented code under the if statement will be executed.

Functions
-------------------------------
- is like a machine that takes inputs and produces outputs.
- functions can be defined using the "def" keyword followed by the function name and arguments in parentheses.
- the "return" keyword is used to specify the output.

Classes and Objects
--------------------------------
- When we define a class, we use an uppercase letter for the class name, and we start defining all the functions and attributes inside the class definition. 
- use 'self' as 'this' property


Anatomy of a Function
-------------------------------
- Functions are composed of a name and parameters.
- Programs involve systems, tasks, objects, and interacting components.


*args
-----------------------------
-  If we want to allow users to pass in any number of variables, use the asterisk symbol before the argument name to create a pointer to the inputted variables.
-   By adding the asterisk before args, Python understands that the variable name is just a reference to the arguments being passed in.
- This trick works only for positional arguments, not keyword arguments.
- If a keyword argument is passed in, an "unexpected keyword argument" error will occur.


**kwargs
-----------------------------
- In order to handle keyword arguments, a method called kwargs can be used.
- Kwags is short for keyword arguments.
- Print kwargs to see that the keyword arguments are now stored as a dictionary instead of a tuple.
- This makes sense because keyword arguments have keys and values and can be passed in any order, so a dictionary is a more appropriate data structure for referencing them.

Variables and Scope
------------------------------
- Python has two types of variables: local variables, defined within a function, and global variables, defined outside the function within the main code block.


Function Scope
-----------------------------
- the method called <b>locals()</b> , is utilized to print out a dictionary containing all the variables passed into the function, whether provided as positional or keyword arguments.
- The name locals refers to the fact that the function retrieves the variables that are accessible locally within the function's scope.
- Variables defined within a function's scope are available throughout that function, but attempting to reference them outside their scope will result in an error.

- The built-in function <b>globals()</b> in Python allows retrieval of all global variables, providing access to variables defined outside the current function's scope.
- This function enables accessing global variables from within a function, offering flexibility and convenience in programming tasks.
- Running the code may result in numerous items displayed by the globals() function, including Python's pre-built variables and variables related to classes and packages.

Global and Local Scope
-----------------------------
- Functions can be declared within other functions, such as the inner function in function one, but they can only be called within the parent function. Attempting to call them outside results in a syntax error.

Functions As Variables
-----------------------------
<br>

Variables as Functions
-----------------------------
- Both variables and functions have names and associated data.
- For functions, this data includes information about required parameters and the lines of instructions to be executed.

Viewing Function Data With  __code__
-------------------------------------------------
- The "code" attribute of Python function objects can be used to confirm that functions are just variables in Python.

Lambda Functions
-------------------------------
- These are a way to represent a function without giving it a variable name.
- Lambda functions can come in handy when you need to pass a function as an argument to another Python function, such as the sorted function that sorts a list of values.  


User Stories
--------------------------
- User stories are a fundamental concept in Agile development, designed to capture a description of a software feature from an end-user perspective.
- User stories guide the development process, ensuring that the software meets the needs of the users.

Use Cases
--------------------------
- A use case is a description of how a user interacts with a system to achieve a specific goal.
- use cases are used to capture the functional requirements of a system
- They describe the sequence of steps, including interactions between a user and the system


Writing and Formatting Email Messages
------------------------------------------
- 
