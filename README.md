# calculator-GUI-tkinter-in-python
a simple python calculator


Import `tkinter`: The code starts by importing the `tkinter` library to build the graphical user interface.

Create a Calculator Class: The calculator's functionality is encapsulated within a class named `Calc`. The class constructor (`__init__`) initializes the GUI and other necessary variables.

Configure Main Window: The main window of the calculator is configured with a title and a default font for all widgets.

Menu Bar: A simple menu bar is created with an "About" option that displays information about the calculator and its developer.

Display Field: A text entry widget (`Entry`) is used to display the numbers and mathematical expressions. This widget is configured to allow only valid characters for calculations.

Number and Operator Buttons: Buttons for digits (0-9), operators (+, -, *, /), decimal point (.), and equals (=) are created. Each button is associated with a specific command using lambda functions to capture button presses.
Clear and Quit Buttons: A "clr" button is provided to clear the display, and an "Esc" button is created to exit the calculator.

Event Bindings: The `Return` key (Enter) is bound to the `calc_expression` method to allow users to press Enter to calculate the result.

GUI Layout: The `mount_gui` method arranges the GUI elements on the window using the `grid` layout manager.

Button Press Method: The `button_press` method is called when a button is pressed. It handles the input of digits, operators, and the decimal point. It also manages the expression and decimal point control.

Prepare Expression: The `prepare_expression` method processes the input expression and prepares it for calculation by splitting it into individual elements (numbers and operators).

Calculate Expression**: The `calc_expression` method performs the actual calculation of the expression, following the order of operations (PEMDAS) - parentheses, exponents, multiplication/division, addition/subtraction.

Clear Method: The `clear` method resets the display field and the decimal point control.

About Method: The `about` method displays information about the calculator and its developer in a separate window.

Main Execution: The `__name__` check ensures that the code is executed only when the script is run directly, not when it's imported as a module.
Mainloop: The `mainloop` method starts the main event loop of the `tkinter` application, which handles user interactions and GUI updates.

Overall, this code creates a functional calculator application with a basic graphical interface that allows users to perform arithmetic calculations using buttons and display the results on the screen. The code is well-commented, which makes it easier to understand the purpose of each section.
