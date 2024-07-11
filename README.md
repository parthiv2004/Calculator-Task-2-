# Calculator Task-2

Project 02 : Basic GUI Calculator

Project Description:
The "Basic GUI Calculator" is a Python-based application that provides a user-friendly graphical interface to perform basic arithmetic calculations. The calculator supports addition, subtraction, multiplication, and division, making it suitable for everyday mathematical operations. The project's primary objective is to offer a simple and intuitive calculator interface that users can easily interact with to perform calculations.

Features:
1. Graphical User Interface: The application utilizes the Tkinter library to create a graphical user interface, providing buttons for numbers, arithmetic operators, and a display field to show the input and result of calculations.

2. Basic Arithmetic Operations: The calculator supports basic arithmetic operations, including addition, subtraction, multiplication, and division. Users can input numerical values using the provided buttons and perform calculations by clicking on the corresponding operator buttons.

3. Real-Time Calculation: As users click on the number and operator buttons, the input will be displayed in real-time on the calculator's display field. This allows users to see the current expression they are entering.

4. Error Handling: The calculator implements error handling to prevent invalid calculations and display meaningful error messages when the user enters an incorrect expression.

Technical Details:
- The project is developed in Python using the Tkinter library for the graphical user interface.
- The calculator's display field is implemented using a Tkinter Entry widget to show the user's input and the result of calculations.
- The number and operator buttons are created using Tkinter Button widgets, and their corresponding functions are bound to the buttons to handle user interactions.
- The calculator will use the `eval()` function to evaluate the user's input and perform the arithmetic calculations.

User Interaction:
Upon launching the application, users will be presented with a simple GUI calculator. They can interact with the calculator using the following features:
- Click on number buttons (0-9) to input numerical values.
- Click on the operator buttons (+, -, *, /) to specify the desired arithmetic operation.
- The input and result will be displayed in the calculator's display field.
- Click on the "=" button to perform the calculation and display the result.
- Click on the "C" button to clear the input field and start a new calculation.

Potential Enhancements:
To enhance the project further, additional features could be implemented, such as:
- Support for more advanced arithmetic operations (e.g., exponentiation, square root).
- Implementation of keyboard input for numerical values and operators.
- Incorporation of memory functionality to store and recall previous calculations.
- Integration of a theme switcher to provide different visual styles for the calculator.

Conclusion:
The "Basic GUI Calculator" is a straightforward and user-friendly Python application that allows users to perform basic arithmetic calculations through an intuitive graphical interface. By providing real-time input display and result updates, the calculator facilitates smooth interactions and helps users carry out mathematical operations efficiently. With potential enhancements, the application can be expanded to accommodate more advanced calculations and personalized customization options, catering to a wider range of user preferences and mathematical needs.
