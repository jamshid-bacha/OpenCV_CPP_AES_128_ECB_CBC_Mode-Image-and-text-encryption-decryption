# Project Overview #
This project is a C++ based encryption and decryption tool using AES-128 and OpenCV for both images and text. It implements two modes of operation for encryption:

AES-128 ECB (Electronic Codebook Mode)
AES-128 CBC (Cipher Block Chaining Mode)
The tool ensures secure handling of sensitive data by applying robust cryptographic methods.

![Screenshot 2025-01-14 154423](https://github.com/user-attachments/assets/9d06efe7-a324-4415-85da-ad46f98ea584)


# Features #
**1. Dual-Mode Encryption:**
AES-128 ECB: Encrypts data block by block without chaining, offering simplicity but with a potential for pattern exposure.
AES-128 CBC: Provides enhanced security by chaining blocks together, making it resistant to pattern analysis.

**2. Support for Images and Text:**
Images are encrypted and decrypted using OpenCV for processing pixel-level data.
Text is encrypted and decrypted as a sequence of bytes, ensuring secure communication or storage.

**3. Cross-Platform Compatibility:**
Built with C++ and OpenCV, ensuring efficiency and flexibility across various platforms.

# How It Works: #
**I. Encryption Process:**
1. .\compile.bat .\encimagtext.cpp ./encrypted.exe
2. .\compile.bat .\decimagtext.cpp ./decrypted.exe
3. Two EXE files will be generated
4. Double click encrypted.exe and run choose the image/text and choose the mode ECB or CBC

For images, OpenCV processes pixel data to encrypt the image matrix

For text, the string data is converted into blocks and encrypted


![lenna](https://github.com/user-attachments/assets/c35a2162-d9e3-4553-87d2-8f7f30296522)

5. The figure will be encrypted as shown below

![EncImageCBC](https://github.com/user-attachments/assets/fc3a3996-7dfe-4e13-ad16-d453fbf4b81a)

**II. Decryption Process:**

6. Now double-click on decrypted.exe choose the image/text
7. The encrypted data (text or image) is fed into the decryption function.
8. The same mode (ECB or CBC) and key used for encryption must be applied for successful decryption.
9. The decrypted text or image is reconstructed and displayed.

![DecryptedCBC](https://github.com/user-attachments/assets/e642a973-548a-47dc-a8e8-0b945ebba033)


**III. Security Parameters:**

Key Size -> 128 bits for both modes.

Initialization Vector (IV)-> Used for CBC mode to provide randomness in encryption.

# IV. Potential Applications: #

**Secure Communication:** Encrypt sensitive text messages or documents for safe transmission.

**Image Protection:** Securely share confidential or sensitive images by encrypting pixel data.

**Data Storage Security:** Protect stored text and image files from unauthorized access.

**Privacy in Cloud Sharing:** Safeguard personal or sensitive files when using cloud storage.

**Cryptographic Learning Tool:** Practical resource for understanding encryption techniques with OpenCV and C++.












