# Software Development Standards 
aka coding standards or coding conventions

- a set of best practices to ensure consistent and readable code across a dev team or organization
- some standards are language specific 
- other standards transcend languages

### common software development standards 

#### Naming conventions 
- Standards for how variables, functions, classes and other program elements should be named in an effort to promote readability and consistency. 

#### Code Formatting
- Best Practices for how code should be structured and formatted to make it easy to read and understand

#### Documentation and Commenting 
- Standards for documenting code and adding comments to make it easier to understand and maintain.

#### Error Handling
- Standards to define how errors and exceptions should be handled in a way that promotes consistency and reliability.

#### Appropriate selection of Logic Constructs
- Standards for selecting and using the most appropriate logic construct to promote efficiency

## Python Standards

### Python Enhanced Proposal, PEP 8
- comprehensive set of published standards
- These standards published as part of the Python Enhanced Proposal or PEP, which is a document that describes features and improvements to the Python language
- entire section of pep just dedicated to standards, aka PEP 8 

#### important standards include:

##### Code formatting

Python has a number of rules centered around the way in which code is presented:
- Limiting lines of code to a maximum of 79 characters.
- Use whitespace to improve readability.

##### Naming conventions

Python has its own naming conventions
- Variable names are typically written in lowercase, with underscores separating words (for example: first_name)
- Class names (Classes will be discussed in a later module) are typically written in CamelCase (for example: TransactionManager)
- Avoid single-character variable names except in certain cases

##### Documentation

Documentation is an essential part of programming and is critical for code maintenance. Python uses docstrings to define code modules, class and function documentation. While inline commenting is typically used sparingly in Python, it is encouraged for code that could be difficult to understand

## PEP 8

- a style guide for python code that provides recommendations for coding conventions 
- following PEP 8 guidelines, developers can write code that is consistent, readable, and easy to maintain
-  This is particularly important for large projects and development teams, where consistent coding conventions are necessary to ensure that everyone can read and understand the code

## Linters

- a tool that is used to analyze source code for potential errors, bugs, and stylistic issues. It is also sometimes called a code linter, syntax checker, or static analyzer
- typically operate by parsing the source code of a program and then analyzing it against a set of predefined rules or guidelines
- checks for syntax errors, potential security vulnerabilities, and adherence to coding conventions and best practices
- benefits of using a linter is that it can help catch errors and issues before the code is run or compiled - saves time
- popular linters include PyLint, Flake8, and Pyflakes
- VS code has a built in linter


