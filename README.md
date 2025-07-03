# 🔐 Image Encryption Tool

## 📌 Description
This project demonstrates a **secure image encryption and decryption system** using Node.js.  
Even if someone gains access to the encrypted image file, they cannot decrypt it without the correct secure key.

This is a beginner-friendly cybersecurity project that introduces the basics of **cryptography**, **secure file handling**, and **command-line interfaces**.

---

## 🚀 Features
- 🔒 Encrypts image files using **AES-256 encryption**
- 🔓 Decrypts only with a valid key
- 🧪 Simple CLI-based tool
- 💡 Great for learning cybersecurity fundamentals

---

## 📂 Project Structure
cli.js # Main command-line interface
├── encrypt.js # Encryption logic
├── decrypt.js # Decryption logic
├── init.js # Key initialization
├── index.js # Entry point
├── package.json # Node.js dependencies

---

## 🛠️ Installation

1. Clone the repository or download the source files.

2. Install dependencies:
```bash
npm install
 Encrypt an Image

node cli.js encrypt path/to/image.jpg
This creates an encrypted .enc file.

 Decrypt an Image

node cli.js decrypt path/to/encrypted-file.enc
