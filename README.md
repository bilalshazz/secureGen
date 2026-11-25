# Random Password Generator 🔐

A command line password generator written in Python. It creates a random password of the length you choose, using a mix of letters, numbers and special characters.

## What it does

* **Custom length** with a minimum of 8 characters
* **Guaranteed variety**, so every password contains at least one uppercase letter, one lowercase letter, one digit and one special character
* **Random order**, as the characters are shuffled so the password never follows a predictable pattern
* **Input validation**, so invalid entries such as letters or numbers below 8 are rejected and you are asked again

## How to use it

1. Run the script with Python 3. No extra libraries are needed.
2. Enter the password length you want (minimum 8).
3. Your generated password is printed in the terminal.

## Example

```
Password must be at least 8 characters long.

Please enter the desired password length (MIN 8): 12

Here is a strong random password: k7$Tq!mB2x#R
```

The password above is just an example. Every run produces a different one.
