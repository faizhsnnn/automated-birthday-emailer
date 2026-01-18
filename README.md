# 🎂 Automated Birthday Emailer (Python)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Challenge](https://img.shields.io/badge/Challenge-90DaysOfCode-orange)

---
# 📌 Overview

The Automated Birthday Emailer is a Python-based automation project that sends personalized birthday emails automatically based on the current date.

The application reads birthday data from a CSV file, selects a professional email template dynamically, personalizes the message, and sends the email securely using SMTP.

This project was built as part of my #90DaysOfCode journey to practice real-world automation, file handling, and external service integration using Python.

---
# 🚀 Key Features

📅 Automatic birthday detection using date-based logic

📨 Personalized email content using dynamic templates

📄 CSV-driven contact management with Pandas

🔐 Secure email delivery using Gmail SMTP (App Password)

🎯 Clean and professional email formatting

🔄 Randomized template selection for natural messaging

---
# 📁 Project Structure
```
automated-birthday-emailer/
│
├── main.py
│   └── Core automation logic and email sending script
│
├── birthdays.csv
│   └── Stores names, emails, and birth dates
│
├── letter_templates/
│   ├── letter_1.txt
│   ├── letter_2.txt
│   └── letter_3.txt
│   └── Professional email templates
│
└── README.md
    └── Project documentation
```
---
# 🛠️ Application Workflow

The script checks the current date.

Birthday data is read from birthdays.csv.

If a birthday matches today’s date:

A random email template is selected

The [NAME] placeholder is replaced with the recipient’s name

A personalized birthday email is sent securely using SMTP.

If no birthday matches, the script exits silently.

This demonstrates real-world automation logic and conditional execution.

---
# ▶️ Execution Instructions
1️⃣ Clone the Repository
```
git clone https://github.com/your-username/automated-birthday-emailer.git
cd automated-birthday-emailer
```
---
2️⃣ Install Required Dependencies
```
pip install pandas
```
---
3️⃣ Configure Email Credentials (IMPORTANT)

Before running the script, update the following variables in main.py:

MY_EMAIL = "your_email@gmail.com"

MY_PASSWORD = "your_app_password"

---
⚠️ Important Notes:

You must use a Gmail App Password, not your regular Gmail password.

Enable 2-Step Verification in your Google account before generating an App Password.

Do not share or commit your credentials publicly.

---
4️⃣ Run the Script
```
python main.py
```
---
# ⚠️ Important Notes

Python 3.x is required

Internet connection must be active

Gmail SMTP uses port 587 with TLS encryption

The letter_templates folder must remain unchanged

This script is intended for educational and personal automation use

---
# 🧠 Concepts Demonstrated

Python automation workflows

Datetime-based conditional logic

CSV data handling using Pandas

SMTP email communication

Template-based content generation

Secure credential usage

Clean and readable Python code

---
# 🎯 Project Significance

This project demonstrates how Python can be used to automate real-life tasks involving dates, data processing, and external services. It reflects practical problem-solving skills and highlights automation concepts commonly used in productivity tools and backend systems.

---
# 👨‍💻 Author

Faiz Hasan
BCA Final Year — Graphic Era University

🚀 Python Learner | #90DaysOfCode

---
*“Automation is not about replacing effort — it’s about using effort wisely.”*
