# 🔐 File Encryption and Decryption using Python

A Python tool that encrypts and decrypts files using symmetric key cryptography via the `cryptography` library (Fernet).

## 📌 Features
- Generates a secure symmetric encryption key
- Encrypts any file and saves the encrypted version
- Decrypts the encrypted file back to original content
- Uses industry-standard Fernet (AES-128-CBC) encryption

## 🛠️ Tech Stack
Python, cryptography (Fernet), File I/O

## ▶️ How to Run

```bash
pip install cryptography
python encrypt_decrypt.py
```

Place your file as `encrypt_decrypt.txt` in the same directory before running.

## ⚙️ How It Works
1. A Fernet key is generated and saved to `mykey.key`
2. The original file is read and encrypted → `enc_encrypt_decrypt.txt`
3. The encrypted file is decrypted → `dec_encrypt_decrypt.txt`

## 📁 Project Structure
```
File-Encryption-and-Decryption-using-Python/
├── encrypt_decrypt.py
├── encrypt_decrypt.txt
├── enc_encrypt_decrypt.txt
├── dec_encrypt_decrypt.txt
├── mykey.key
└── README.md
```

## 🧠 Skills Demonstrated
- Python cryptography library usage
- File I/O (read/write binary)
- Symmetric key encryption/decryption
- Security concepts in Python
