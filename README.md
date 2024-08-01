# Password Checker
This is a Python project that checks how many times a password has been leaked, similar to the 'Have I Been Pwned' website.

## Features
Checks the number of times a password has been leaked.
Utilizes the 'Have I Been Pwned' API for checking password leaks.
Simple and easy-to-use interface.

## Prerequisites
Python 3.x
requests library (Install using "pip install requests")

## Installation
1. Clone the repository:
    git clone https://github.com/azizprodev/password-checker.git
2. Navigate to the project directory
    cd password-checker

## Usage
Run the script:
  python main.py yourpassword

## How It Works
1. The script hashes the password using SHA-1.
2. It sends the first 5 characters of the hash to the 'Have I Been Pwned' API.
3. The API returns a list of all leaked passwords that match the first 5 characters of the hash.
4. The script compares the rest of the hash with the returned hashes to find the exact match and the number of times it has been leaked.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.
