# 🔐 Project Encryption Tool

A lightweight, standalone **text file encryption utility** designed for simplicity and strong protection. The tool generates a secure executable, encrypts text files using a unique key, and ensures that **only the correct key can restore the data**.

This project is intentionally strict. If you lose your key, your data is **gone forever**. No recovery tricks. No shortcuts. Cryptography does not care about regret.

---

## ✨ Features

- **Unique key per encryption**
- Fully **offline** operation
- **Guided command-line interface** for easy use
- **Strong encryption** designed to prevent unauthorized access
- Simple workflow with minimal user input

---

## ⚙️ How It Works

1. Open the **main software folder**
2. Run **`generate.exe`**
3. The tool creates:
   - `encrypt.exe`
   - A key file named **`format.txt`**
4. Open **`encrypt.exe`**
5. Follow the guided on-screen instructions to:
   - Encrypt a text file
   - Decrypt an encrypted text file

The interface is command-line based but fully guided, so users do not need prior encryption knowledge.

---

## 🔑 Important: Key File (`format.txt`)

- `format.txt` is the **encryption key**
- You may use:
  - The **same key** for multiple files, or
  - **Different keys** for different files
- **Decryption requires the exact key used during encryption**

If the correct key is not provided during decryption:

➡️ The data is permanently lost.

There is no recovery method.

Always keep secure backups of your key files.

---

## 🚨 Warnings & Responsibility

- This software provides **no data recovery** features
- Losing the key means **permanent data loss**
- The author is **not responsible** for:
  - Lost files
  - Corrupted data
  - User mistakes

By using this software, you agree that you are encrypting files **at your own risk**.

---

## 📁 Supported Files

- Plain text files (`.txt`)

Binary or large structured files are **not recommended** unless you know exactly what you are doing.

---

## 🖥️ System Requirements

- Windows OS
- Ability to run `.exe` files
- Basic file management knowledge

---

## 🛠️ Usage Tips

- Store `format.txt` on:
  - External USB
  - Encrypted archive
  - Offline storage
- Do **not** rename the key file
- Do **not** edit the key file

---

## 📜 License

This software is **free to use** for personal and educational purposes.

❌ **Modification, redistribution, or commercial use is NOT permitted** without **explicit authorization from the author**.

Unauthorized modification or redistribution is prohibited.

---

## 📌 Final Note

Encryption is strict by design.

If the key used for encryption is missing or incorrect, the data is **gone permanently**.

**Sowhardo Islam is not responsible for any data damage or loss.**

Use this tool only if you understand the risks involved.
