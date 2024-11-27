# Ransomware Simulation Project
This project demonstrates how ransomware works by simulating its behavior in a controlled environment. It is intended solely for educational purposes to understand the mechanisms and the risks of ransomware, and to provide insights into its prevention and mitigation.

## 1. Overview
Ransomware is a type of malware that encrypts files and demands payment for their decryption. This project was developed for the academic report "How to Make Ransomware?".

## 2. Project Structure
Documentation:
Includes the memory report detailing the ransomware's structure and functions.
Code:
ransomware.py: Simulates encryption/decryption of files.
keys_generator.py: Generates RSA public/private key pairs for the encryption process.
Simulation Labs:
Demonstrates the ransomware's functionality in different environments (e.g., Ubuntu, Kali).

## 3. Key Features
Encryption Techniques:
Combines AES (symmetric) and RSA (asymmetric) algorithms.
File Targeting:
Identifies files with specific extensions (pdf, docx, jpg, etc.).
Verification Mechanism:
Ensures the decryption key matches before restoring files.
Logging:
Tracks all operations in a log file for debugging and educational purposes.

## 4. Disclaimer
This project is not intended for malicious use. Misuse of this code may violate laws and ethical guidelines. It is designed for learning purposes only, under controlled conditions.

## 5. Execution Instructions
Setup:
Install Python 3.x.
Ensure required libraries are installed (cryptography).
Running the Ransomware Simulation:
Generate RSA keys using keys_generator.py.
Run the ransomware simulation:
bash
Copiar código
python ransomware.py
To decrypt, provide the private key when prompted.

## 6. Educational Objectives
This project explores:

What ransomware is and how it operates.
Encryption techniques used in real-world attacks.
Safe handling and ethical considerations of cybersecurity research.

## 7. License
This project is open for academic use only. Unauthorized commercial or malicious use is strictly prohibited.
