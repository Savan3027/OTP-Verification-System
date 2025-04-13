
# 🔐 OTP Verification System in Python

This is a simple Python project that demonstrates an OTP (One-Time Password) verification system. The OTP is generated using Python and sent via email using the `smtplib` module. Users are prompted to input the OTP and can retry until successful.

## 📌 Features

- ✅ 6-digit random OTP generation
- 📤 Sends OTP via email using SMTP (Gmail)
- 🔁 Unlimited attempts for OTP input
- 🧠 Basic input validation and error handling
- 💡 Structured with reusable functions for clarity

## 📂 Technologies Used

- Python 3.x
- Jupyter Notebook
- Modules:
  - `random` – for OTP generation
  - `smtplib` – to send emails
  - `email.mime.text` – to format email content

## 🛠 How It Works

1. The program generates a 6-digit OTP.
2. It sends the OTP to a specified email using `smtplib`.
3. The user is prompted to enter the OTP.
4. If the entered OTP is correct, access is granted.
5. If not, the user is prompted again until success.

## 🚀 Getting Started

### Prerequisites
- Python installed (version 3.x)
-  A Gmail account with "App Password" enabled for SMTP login
### Installation

Clone the repository:
```bash
git clone https://github.com/Savan3027/OTP-Verification-System.git
