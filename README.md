# Tkinter_Calculator
Description
This is a basic Python application that uses the tkinter library to create a simple graphical user interface (GUI) calculator. The app allows users to input mathematical expressions, click the "presmetaj" button to perform the calculation, and see the result displayed below the button.

Features:
User-Friendly Interface: The application provides an easy-to-use GUI built with Tkinter.
Mathematical Expressions: Users can enter any valid mathematical expression (such as 2+2, 5*3, 10/2) into a text field.
Instant Results: After clicking the "presmetaj" button, the result of the calculation is shown immediately.

Requirements:
Python 3.x: Make sure Python is installed on your system.
Tkinter: This library comes pre-installed with Python, so no additional installation is required.
Code Overview:
The structure of the code is simple and organized into key components:

Entry Field (entry): A text box where users can type their mathematical expression.
Button (button): When clicked, this button triggers the calculation. It uses Python's built-in eval() function to evaluate the expression.
Label (label): Displays the result of the calculation.
The core functionality is encapsulated in the presmetaj function, which:

Retrieves the user input from the entry field.
Uses eval() to evaluate the mathematical expression.
Updates the label to show the result.
Example Usage:
Type an expression like 5+3, 7*9, or 10/2 into the text box.
Press the "presmetaj" button to get the result, which will appear below the button.
This simple app offers a quick way to calculate basic arithmetic expressions with a clean, easy-to-navigate interface.
