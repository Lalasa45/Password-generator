# Password-generator
This Python script generates a secure random password based on user input. It allows users to specify the desired password length and ensures that the password contains a mix of uppercase and lowercase letters, digits, and special characters.

Features:
User Input for Length: The user is prompted to enter the length of the password.
Character Variety: The password consists of:
Uppercase letters (A-Z)
Lowercase letters (a-z)
Digits (0-9)
Special characters (!@#$%^&* etc.)
Error Handling:
If the user enters a non-numeric value, the script displays an error message.
If the user enters a negative number or zero, it prompts the user to enter a valid length.
Workflow:
The script prompts the user to enter the desired password length.
It verifies if the input is a valid positive integer.
It generates a random password using random.choice() from a set of letters, digits, and special characters.
The generated password is displayed to the user.
