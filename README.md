# Python Email Automation

This is a simple Python script that automates the process of sending emails using the `smtplib` library. It allows users to send automated email notifications with ease.

## Features
- Sends automated emails using SMTP.
- Uses `MIMEText` and `MIMEMultipart` for structuring email content.
- Secure login with TLS encryption.

## Prerequisites
Ensure you have the following before running the script:
- Python installed (version 3.x recommended)
- A Gmail account (for sending emails)
- Enable "Less secure apps" access or generate an App Password for security

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/python-automation-basics.git
   cd python-automation-basics
   ```
2. Install required dependencies (if needed):
   ```sh
   pip install smtplib
   ```

## Usage
1. Open `automation_script.py` and replace the placeholders with your email credentials:
   ```python
   sender_email = "your_email@gmail.com"
   receiver_email = "receiver_email@gmail.com"
   password = "your_email_password"  # Use an app password for security
   ```
2. Run the script:
   ```sh
   python main.py
   ```

## Security Considerations
- Do **not** hardcode your email password in the script. Instead, use environment variables or an app password.
- Use `starttls()` to establish a secure connection with the SMTP server.

## Contributing
Pull requests are welcome! If you find any issues, feel free to submit an issue or contribute by improving the code.

## Author
Created by [Rohan Das](https://github.com/rohandas28).
