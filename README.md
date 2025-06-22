# 🔐 Cryptography Tool

A simple and secure Python-based tool for encrypting and decrypting **text and documents**, developed to help users protect their sensitive data using modern cryptographic techniques.

---

## ✨ Features

- 🔏 **Text Encryption/Decryption**  
  Securely encrypt or decrypt messages using a secret key.

- 📄 **Document Encryption/Decryption**  
  Upload `.txt`, `.pdf`, or `.docx` files and encrypt their content. Easily decrypt them later using the correct key.

- 📥 **Downloadable Encrypted Files**  
  Get encrypted content as downloadable files for easy sharing and storage.

- 📤 **Upload-to-Decrypt Functionality**  
  Decrypt previously encrypted documents by uploading them back to the tool.

- 🛡️ **Security First**  
  Utilizes strong symmetric encryption (AES or Fernet). User data and keys are not stored anywhere.

---

## 🧠 How It Works

1. **Encrypt Text**  
   - Enter a plain message and a key.  
   - Get an encrypted text output + option to download.

2. **Encrypt Document**  
   - Upload a `.txt`, `.pdf`, or `.docx` file.  
   - Enter a password.  
   - Get the encrypted file for download.

3. **Decrypt Text or File**  
   - Upload the encrypted file.  
   - Enter the same key used to encrypt.  
   - Retrieve the original content.

---

## 🚀 Technologies Used

- **Python** – for core logic
- **Cryptography Library / PyCryptodome** – for AES encryption
- **Google AI Studio** – for interactive frontend experience
- **Base64** – for encoding encrypted content safely
- **Google Colab (Prototype stage)** – for quick testing and demos

---

## 📦 Installation (If Using Locally)

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cryptography-tool.git
   cd cryptography-tool

