# SecureVault - Password Strength Checker with Encryption 🔐

SecureVault is a secure, offline desktop application built using Python and Tkinter. It evaluates password strength in real-time and provides a local encrypted vault to safely store credentials under a single master password.

## ✨ Features
- **Real-Time Password Checker:** Evaluates length, complexity, and checks against common weak passwords.
- **Strong Encryption:** Uses industry-standard Fernet (AES-128-CBC + HMAC) to secure stored data.
- **Secure Key Derivation:** Implements PBKDF2-HMAC-SHA256 with 390,000 iterations for master password hashing.
- **Password Generator:** Built-in cryptographically secure random password generator.
- **Local Storage:** Fully offline SQLite3 database—your data never leaves your computer.

## 🛠️ Technologies Used
- **Language:** Python 3
- **GUI Framework:** Tkinter (ttk)
- **Database:** SQLite3
- **Security Libraries:** `cryptography`, `hashlib`, `secrets`

## 🚀 How to Run
1. Clone this repository or download the source code.
2. Install the required security library:
   ```bash
   pip install cryptography
   ```
3. Run the application:
   ```bash
   python main.py
   ```
*(Note: Replace `main.py` with your actual Python file name)*
