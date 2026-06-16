# Password Generator

## Project Description
This is a Password Generator application developed using Python. The program generates strong and random passwords based on the length specified by the user. It helps users create secure passwords for their online accounts and applications.

## Features
- Generate random passwords
- User-defined password length
- Includes uppercase and lowercase letters
- Includes numbers and special characters
- Simple and easy-to-use interface

## Technologies Used
- Python 3
- Random Module
- String Module

## How to Run the Project

1. Install Python on your system.
2. Download or clone this repository.
3. Open a terminal in the project folder.
4. Run the program using:

```bash
python password_generator.py
```

## Project Structure

```text
Task3_PasswordGenerator/
│
├── password_generator.py
└── README.md
```

## Sample Output

```text
Enter password length: 12

Generated Password: @K7#pL9!xQ2$
```

## Code Explanation

- The user enters the desired password length.
- The program combines:
  - Uppercase letters (A-Z)
  - Lowercase letters (a-z)
  - Numbers (0-9)
  - Special characters (!, @, #, $, etc.)
- A random password is generated using Python's `random` and `string` modules.
- The generated password is displayed on the screen.

## Learning Outcomes

- Understanding Python modules
- Working with random data generation
- String manipulation
- User input handling
- Creating secure passwords programmatically

## Future Enhancements

- Option to choose password complexity
- Copy password to clipboard
- GUI version using Tkinter
- Password strength checker

## Author

Dev Anand R

## Internship

CodSoft Python Programming Internship - Task 3
