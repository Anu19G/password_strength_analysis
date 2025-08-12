# Password Strength Analysis

## 📄 Overview
This project demonstrates the process of creating strong passwords, evaluating their strength, and testing them against common password-cracking techniques.  
It includes:
- Password generation and testing
- Improvement of weaker passwords
- Simulated dictionary and brute force attacks
- Practical demonstration of attack resistance

The analysis highlights why password length, complexity, and randomness are crucial for security.

---

## 🎯 Objective
Understand what makes a password strong, evaluate it using password strength tools, and test its resistance to:
- Dictionary attacks
- Brute force attacks

---

## 🛠 Tools & Environment
- **Operating Systems**: Windows, Kali Linux
- **Tools**:
  - [PasswordMeter.com](https://passwordmeter.com) – Password strength evaluation
  - John the Ripper – Dictionary attack simulation
  - Hashcat – Brute force attack simulation
  - PowerShell & `pwgen` – Password generation

---

## 📂 Files in This Repository
- `Password Strength Analysis.pdf` — Main report with methodology, screenshots, and results
- `windows_password_test.pdf` — PasswordMeter evaluation for Windows-generated password
- `kali_password_test.pdf` — PasswordMeter evaluation for Kali-generated password
- `kali_password_test_improved.pdf` — PasswordMeter evaluation for improved Kali password

---

## 📊 Key Findings
| Password Type        | Score | Complexity  | Attack Result      |
|----------------------|-------|-------------|--------------------|
| Windows Generated    | 100%  | Very Strong | Resistant          |
| Kali Generated       | 95%   | Very Strong | Slightly weaker due to no symbols |
| Improved Kali        | 100%  | Very Strong | Resistant          |
| Weak Example (Pass12)| N/A   | Weak        | Cracked in seconds |

---

## 🔐 Best Practices for Strong Passwords
1. Minimum **16 characters**
2. Mix **uppercase**, **lowercase**, **numbers**, and **symbols**
3. Avoid dictionary words & personal info
4. Place symbols randomly, not at predictable positions
5. Use a password manager for secure storage

---

## 📌 Conclusion
Long, complex, and unpredictable passwords significantly increase resistance against brute force and dictionary attacks. The improved Kali password demonstrated high resistance in both John the Ripper and Hashcat simulations.

---
