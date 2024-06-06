# CODETECH_JAVA
CALCULATOR DESCRIPTION:

This is a simple calculator application built using Java Swing. It provides basic arithmetic operations including addition, subtraction, multiplication, division, modulus, and exponentiation. The application also supports negating values, deleting the last character, and clearing the input.
Features

    Basic Arithmetic Operations: Addition, subtraction, multiplication, and division.
    Additional Operations: Modulus, exponentiation, and negation.
    Decimal Point: Supports floating-point numbers.
    Clear Function: Clear the input field.
    Delete Function: Delete the last character in the input field.

Components
JFrame and JPanel

    JFrame: The main window of the application titled "Simple Calculator".
    JPanel: Used to organize buttons in a grid layout.

Buttons

    Number Buttons (0-9): Buttons for each digit from 0 to 9.
    Operation Buttons: Buttons for addition (+), subtraction (-), multiplication (*), division (/), modulus (%), exponentiation (^), and negation ((-1)).
    Special Buttons: Buttons for decimal point (.), equals (=), clear (CLR), and delete (DEL).

JTextField

    t1: A text field for displaying the input and results.

JLabel

    l: A label displaying "Simple Calculator".

Layout

The main layout is a FlowLayout, while the buttons are arranged in a GridLayout with 7 rows and 2 columns.
Event Handling

The ActionListener interface is implemented to handle button click events.
Operations

    Numbers and Decimal Point: Appends the clicked number or decimal point to the input field.
    Clear (CLR): Clears the input field.
    Delete (DEL): Deletes the last character in the input field.
    Negation: Multiplies the current input by -1.
    Arithmetic Operations: Stores the current input and sets the operation type.
    Equals (=): Performs the stored operation using the current input and the stored value.

Code Flow

    Initialization:
        A new JFrame is created with the title "Simple Calculator".
        JTextField for input/output is created and styled.
        Buttons for digits, operations, and special functions are created and added to a JPanel with a grid layout.
        All components are added to the main JFrame.

    Event Handling:
        Each button has an ActionListener that defines its behavior when clicked.
        The input and operations are managed through the actionPerformed method.
        The equals button performs the stored operation and updates the input field with the result.

    Main Method:
        Creates an instance of the calculator class, launching the application.


CHATBOT DESCRIPTION:

    This is a simple ChatBot application developed using Java Swing. The ChatBot provides automated responses to predefined user inputs, simulating a conversation. It demonstrates basic GUI elements and event handling in Java.
Features

    Responds to user inputs with predefined messages.
    Displays conversation history in a text area.
    Includes a text field for user input and a submit button to send messages.

Components
JFrame and Components

    JFrame: The main window of the application titled "ChatBot".
    JTextArea: Displays the conversation history.
    JTextField: Allows the user to input their message.
    JButton: Submits the user's message.
    JLabel: Displays the text "SUBMIT" on the button.

Layout

    The layout is managed manually by setting bounds for each component.

Event Handling

The ActionListener interface is implemented to handle button click events.
Code Flow

    Initialization:
        A new JFrame is created with the title "ChatBot".
        JTextArea for displaying conversation history is created and styled.
        JTextField for user input is created and styled.
        JButton for submitting messages is created and styled.
        A JLabel is added to the button to display the text "SUBMIT".
        All components are added to the main JFrame with specified bounds.

    Event Handling:
        The ActionListener is added to the button.
        When the button is clicked, the input text is retrieved from the JTextField, and a corresponding reply is generated based on predefined conditions.
        The conversation history is updated in the JTextArea.

    Predefined Responses:
        The bot responds to greetings, inquiries about its well-being, name, book suggestions, gender, and expressions of affection or dislike.
        If the input does not match any predefined condition, a default response is provided.

    Main Method:
        Creates an instance of the chatBot class, launching the application.
