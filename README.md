# Password_Generator-Checker

This project is a password generator and strength checker written in Java. It includes four main components: Main.java, Password.java, Alphabet.java, and Generator.java. The Main class initializes the program and starts the user interaction loop. The Password class represents and evaluates the strength of passwords based on character diversity and length. The Alphabet class defines character pools for generating passwords, including uppercase, lowercase, numbers, and symbols. The Generator class manages user interactions, generates passwords based on user preferences, and checks password strength. A GeneratorTest class provides unit tests to ensure the functionality of the password generation and validation processes.

Main.java:-
Entry point of the program.
Initializes a Scanner object for user input.
Creates an instance of the Generator class and starts the main loop for user interaction.

Password.java:-
Represents a password and provides methods to determine its strength.
CharType method identifies if a character is uppercase, lowercase, digit, or symbol.
PasswordStrength method calculates the strength of the password based on character diversity and length.
calculateScore method returns a message indicating the password's strength.

Alphabet.java:-
Defines pools of uppercase letters, lowercase letters, numbers, and symbols.
Constructor allows the selection of which character types to include in the pool.
getAlphabet method returns the combined pool of selected characters.

Generator.java:-
Handles user interaction and password generation.
mainLoop method presents a menu for the user to choose between generating a password, checking password strength, viewing useful information, or quitting the program.
GeneratePassword method creates a password of specified length from the selected character pool.
requestPassword method prompts the user for their preferences and generates a password accordingly.
checkPassword method allows the user to input a password and receive feedback on its strength.
printUsefulInfo method provides guidelines for creating strong passwords.

GeneratorTest.java:-
Contains unit tests for the Password, Alphabet, and Generator classes.
Verifies the correct functionality of methods and ensures expected behavior.
