# Secure Code Review - CodeAlpha Internship Task

## Introduction
Secure code review is the process of examining source code to identify security vulnerabilities and improve software security.

## Sample Code Reviewed

username = input("Enter username:")
password = input("Enter password:")

if username == "admin" and password == "12345":
    print("Login Successful")
else:
    print("Login Failed")

## Security Issues Identified

1. Hardcoded Credentials
The username and password are stored directly in the source code.

2. Weak Password
The password "12345" is very weak and can be guessed easily.

3. No Password Encryption
Passwords are stored in plain text.

4. No Input Validation
User input is not validated before processing.

## Recommendations
- Use strong passwords.
- Store passwords using hashing.
- Avoid hardcoded credentials.
- Validate user input.
- Follow secure coding practices.

## Conclusion
The reviewed code contains several security weaknesses. Applying secure coding techniques can improve application security and protect sensitive data.

Submitted By: Syeda Madina Fatima
