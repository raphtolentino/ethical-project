# Ethical Hacking Password Manager

## Project Overview
A secure command-line password manager developed as part of an ethical hacking project. This application allows users to create, store, and manage encrypted passwords locally, enhancing security by keeping sensitive data off cloud servers.

## Features
- Secure password generation with customizable complexity
- Local encryption of stored passwords
- Command-line interface for easy management
- User authentication to protect stored passwords
- Password strength evaluation

## Technologies Used
- Python 3.x
- Cryptography library for encryption
- Argparse for CLI argument parsing
- SQLite for local database storage

## Installation & Setup
```bash
# Clone the repository
git clone https://github.com/raphtolentino/ethical-project

# Navigate to the project directory
cd ethical-project

# Install dependencies
pip install -r requirements.txt

# Run the application
python password_manager.py
