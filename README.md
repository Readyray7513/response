# Email Validator

## Description
This is a simple Python program that prompts the user for an email address and checks if it is syntactically valid. It uses the `validator-collection` package from PyPI to validate the email address.

## Features
- Prompts the user for an email address via `input()`.
- Checks if the email address is in a valid format.
- Prints `Valid` if the email is syntactically correct, otherwise prints `Invalid`.
- Does **not** check if the domain actually exists.
- Does **not** use regular expressions (`re`).

## Installation
Ensure you have Python installed on your system. Then, install the required package by running:

pip install validator-collection


## Usage
1. Run the script:
   python response.py
2. Enter an email address when prompted.
3. The program will print `Valid` if the email is in a correct format, otherwise `Invalid`.

## Code Overview
The script follows these steps:
1. Imports `validators` from `validator_collection`.
2. Prompts the user for an email address.
3. Uses `validators.email()` to validate the input.
4. Prints `Valid` if the email format is correct; otherwise, prints `Invalid`.

## Example
```
Enter your email address: test@example.com
Valid
```
```
Enter your email address: invalid-email
Invalid
```

## License
This project is free to use and modify.
