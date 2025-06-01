# Email_autoamtion

 Automates the process of sending personalized emails to multiple recipients using an email list stored in an Excel spreadsheet. It uses Gmail's SMTP server to send emails securely.

-Read names and email addresses from an Excel file.
- Compose a personalized email for each recipient.
- Secure connection using TLS.
- Useful debug logs to monitor the process


import packages like:
-pandas
-openpyxl

The Excel file data.xlsx must contain at least the following columns:
Full name	Email Address
John Doe	john@example.com
Jane Smith	jane@example.com

Setup Gmail for App Passwords
-Enable 2-Step Verification for your Gmail account.
-Go to https://myaccount.google.com/apppasswords
-Generate a new "App Password" for "Mail".
-Replace the password in the script with this app password:

Check if you're using an app password (not your normal Gmail password).


![Screenshot from 2025-06-01 14-40-41](https://github.com/user-attachments/assets/cc98a326-6cde-46e9-9f55-fde2bdc9b4b2)
![Screenshot from 2025-06-01 15-21-04](https://github.com/user-attachments/assets/6420d602-2580-4bfa-adc1-19d59e822a50)
