# Password_Checker

# Password Strength Checker

## Overview

This project is a simple Python application that assesses the strength of a password using common security criteria. It evaluates passwords based on their length and the presence of uppercase letters, lowercase letters, numbers, and special characters.

The application continuously prompts users to enter a password and classifies it as **Weak**, **Medium**, or **Strong** based on predefined rules.

## Features

* Checks for a minimum password length of 8 characters
* Detects uppercase letters
* Detects lowercase letters
* Detects numeric characters
* Detects special characters
* Classifies passwords as:

  * **Weak**
  * **Medium**
  * **Strong**
* Runs in a continuous loop until the program is stopped

## Technologies Used

* Python 3
* Built-in `string` module

## How It Works

The program evaluates each password against the following criteria:

| Strength   | Requirements                                                                                           |
| ---------- | ------------------------------------------------------------------------------------------------------ |
| **Strong** | At least 8 characters, including uppercase letters, lowercase letters, numbers, and special characters |
| **Medium** | At least 8 characters with letters and either numbers or special characters                            |
| **Weak**   | Does not meet the above requirements                                                                   |

## Example

```text
Enter a password: Password123!
Password strength: Strong

Enter a password: password123
Password strength: Medium

Enter a password: hello
Password strength: Weak
```

## Learning Objectives

This project demonstrates the use of:

* Functions
* Conditional statements
* Loops
* String methods (`isupper()`, `islower()`, `isdigit()`)
* Generator expressions with `any()`
* Basic password validation techniques



