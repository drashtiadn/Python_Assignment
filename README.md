# Python_Assignment

Instructions:

Write your solutions in Python.
Try to solve each problem on your own first, and if you get stuck, research the topic and seek help if needed.
Document your code with comments to explain your thought process.
Submit your solutions in a single Python script file (e.g., assignment.py).
Question: Encryption and Decryption

Your task is to implement a simple encryption and decryption algorithm using Python. This algorithm should take a message, a key, and a mode (encrypt or decrypt) as input.

Encryption:
Write a Python program that takes a message (a string) and a key (an integer) and encrypts the message. The encryption should work as follows:
For each character in the message, shift the character's ASCII value by the key.
Wrap around if the shifted ASCII value goes beyond the printable ASCII character range.
Decryption:
Write a Python program that takes an encrypted message and the key and decrypts the message to its original form.
For each character in the encrypted message, shift the character's ASCII value backward by the key.
Wrap around if the shifted ASCII value goes beyond the printable ASCII character range.
Write a Python script that allows a user to input a message, a key, and a mode (encrypt or decrypt), and outputs the result of the encryption or decryption accordingly.

 

Enter the message: hello
Enter the key (an integer): 3
Choose mode (encrypt/decrypt): encrypt
Encrypted message: khoor




Enter the message: khoor
Enter the key (an integer): 3
Choose mode (encrypt/decrypt): decrypt
Decrypted message: hello
Evaluation Criteria

Evaluation Criteria

Functionality and Accuracy: 8 marks

The primary focus is on whether the program correctly implements the encryption and decryption algorithms.
Emphasis on handling ASCII character shifting and wrapping correctly.
Code Quality and Efficiency: 6 marks

Efficient and effective use of Python features and data structures is key.
Code readability, organization, and the use of meaningful variable names and comments are crucial.
User Interface and Error Handling: 4 marks

The ease of use and clarity of user instructions are important.
Robust handling of edge cases and user input errors is essential.
Adherence to Standards and Testing: 2 marks

Compliance with Python coding conventions and best practices.
Inclusion of tests for various input scenarios to ensure code robustness.
