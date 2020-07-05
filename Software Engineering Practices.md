# software Engineering Practices

	***My Learnings/jottings on software Engineering Practices***

These are practices that every developers should learn and apply in their day to day coding activities.
Every code should be: 
- [Clean](#writing-clean-code)
- [Modular](#writing-modular-code)
- [Efficient](#efficient-code)
- [Well documented](#documentation) and
- [version controled](#version-control) 

This makes code to be reused and shared among other developers.

## Clean Code

	A *clean* code is simple, concise and readable

## Modular Code

	A *Modular code* is one that is logically broken down into smaller parts; as function and modules. 

	It makes code more organised, modular and reusable.

## Module 

	A *Module* is a file that allow code to be reused by encapsulating them into files that can be imported into other files.

## Production Code Quality

	This shows the efficiency of code in production servers. 

## Writing Clean Code

### Tip: Use meaningful names

* Be descriptive and imply type
* Be consistent but clearly differentiate - E.g. age_list and age is easier to differentiate than ages and age.
* Avoid abbreviations and especially single letters
* Long names != descriptive names


### Tip: Use whitespace properly

* Organize your code with consistent indentation
* Separate sections with blank lines to keep your code well organized and readable.
* Try to limit your lines to around 79 characters, which is the guideline given in the PEP 8 style guide.

## Writing Modular Code

* DRY (Don't Repeat Yourself)
* Abstract out logic to improve readability
* Minimize the number of entities (functions, classes, modules, etc.)
* Functions should do one thing
* Arbitrary variable names can be more effective in certain functions
* Try to use fewer than three arguments per function

## Efficient Code

Optimizing code to be more efficient can mean making it:

- Execute faster
* Take up less space in memory/storage


## Documentation

Documentation is an additional text or illustrated information that comes with or is embedded in the code of software.

Helpful for clarifying complex parts of code, making your code easier to navigate, and quickly conveying how and why different components of your program are used.

Several types of documentation can be added at different levels of your program:
- In-line Comments - line level
- Docstrings - module and function level
- Project Documentation - project level

**In-Line Comments:**
- It is used to document the major steps of complex code to help readers follow. 
- Comments are valuable for explaining where code cannot.

**Docstrings:**

Docstrings are valuable pieces of documentation that explain the functionality of any function or module in code. Ideally, each function should always have a docstring.

Docstrings are surrounded by triple quotes. The first line of the docstring is a brief explanation of the function's purpose.

Docstrings can be 
- one line, or
- multi line 

**Project Documentation**

Project documentation is essential for getting others to understand why and how your code is relevant to them, whether they are potentials users of your project or developers who may contribute to your code. A great first step in project documentation is your README file. It will often be the first interaction most users will have with your project.


## Version Control

Version Control helps to keep track of changes in code. This is a very useful tool that helps developers switch to different versions as they code along.
The most used version control today is [git](https://git-scm.com/).



*source: [udacity](https://classroom.udacity.com/courses/ud090/lessons/ac47b924-72d3-4bf9-971c-bfccfa368b02/concepts/0ea0ed14-f1ab-4119-bc5a-3ab2de6bc418)*
