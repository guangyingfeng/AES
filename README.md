# 🔐 AES Encryption Module (CBC Mode, 128/256-bit Keys)

This module provides symmetric encryption and decryption based on the **Advanced Encryption Standard (AES)**, supporting **128-bit** and **256-bit** key lengths, and operating in **CBC (Cipher Block Chaining)** mode, compliant with NIST SP 800-38A.

---

## ✨ Key Features

- **Flexible Key Sizes** – Supports both 128-bit and 256-bit keys to meet different security requirements.

- **Secure Mode** – CBC mode uses chaining (XOR) to ensure that identical plaintext blocks produce different ciphertext blocks, effectively resisting statistical analysis.

- **Simple API** – For easy integration.

---

## 🎯 Use Cases

- Data-at-rest encryption (e.g., configuration files, local sensitive data)
- Payload protection during network transmission
- Lightweight secure communication in embedded or IoT devices

