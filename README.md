# CodeAlpha_Test-psd-strength
This is a Python script that allows you to check the strength of passwords. It uses the zxcvbn library to evaluate the strength of passwords based on factors such as length, complexity, and common usage.

# Table of Contents

1. [Features](#features)
2. [Requirements](#requirements)
3. [Usage](#usage)

## Features

* Check the strength of a password and provide a score and feedback message.
* Option to use custom wordlists for checking weak and banned passwords.
* Simple command-line interface for easy interaction.

## Requirements

* Python 3.x
* zxcvbn library

## Usage

1. Clone the repository or download the script file:
```
git clone https://github.com/thangaraj-333/CodeAlpha_Test-psd-strength
```

2. Install the zxcvbn library by running the following in your terminal:
```
pip install zxcvbn
```

3. Run the script using:
```
python password_strength_checker.py.
```

4. Follow the prompts to enter the number of passwords to test, the path to the weak wordlist file (optional), and the path to the banned wordlist file (optional).
Enter the passwords to test when prompted.

5. To exit the tool, enter 0 when prompted for the number of passwords to test.

Example:
```
$ python password_strength_checker.py
Enter the number of passwords to test (enter 0 to exit): 1
Enter the path to the weak wordlist file (leave blank for default):
Enter the path to the banned wordlist file (leave blank for default):
Enter a password: Asdfg@123456
Strong: Password meets all the requirements. Score: 3/4
Enter the number of passwords to test (enter 0 to exit):
Thank you for using the Password Strength Checker.
```
