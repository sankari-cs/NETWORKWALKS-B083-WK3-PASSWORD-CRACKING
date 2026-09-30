# NETWORKWALKS-B083-WK3-PASSWORD-CRACKING
## PASSWORD CRACKING USING JOHN THE RIPPER AND NETWORKWALKS TOOL

## 📌 Overview

**Password cracking** is a cybersecurity technique used to recover or test the strength of passwords by systematically trying possible passwords through methods such as dictionary attacks and brute-force attacks. It is commonly used in authorized security testing to identify weak passwords and improve overall system security.

This repository documents the **Week 3 Project Tasks** completed as part of my Cybersecurity Internship at **Networkwalks**. The task focuses on password cracking of protected PDF files using two different approaches:

1. **Module 1** – Password Cracking with **John the Ripper (JTR) & Johnny GUI**
2. **Module 2** – Password Cracking with **Networkwalks Hash Calculator & Password Cracker**

Both approaches demonstrate how dictionary-based attacks can be used to recover weak passwords in an authorized lab environment.

---

## 🎯 Objective

- Understand how password hashes are extracted from protected files.
- Learn how dictionary/wordlist-based password cracking works.
- Use John the Ripper and Johnny GUI for password recovery.
- Explore Networkwalks Hash Calculator and Password Cracker.
- Compare offline and browser-based password-cracking approaches.
- Understand the importance of strong and secure passwords.

---

## 🛠️ Tools Used

| Task | Tools |
|------|-------|
| Module 1 | John the Ripper (JTR), Johnny GUI, PDF Hash Extractor |
| Module 2 | Networkwalks Hash Calculator, Networkwalks Password Cracker |

---

## 📂 Module 1 — Password Cracking with JTR

### Steps

1. Downloaded **John the Ripper** and **Johnny GUI** from the official Openwall sources.
2. Configured the path to `john.exe` in Johnny.
3. Extracted the crackable PDF hash using a PDF Hash Extractor.
4. Saved the extracted `$pdf$...` hash into a text file.
5. Loaded the hash file into Johnny.
6. Started a wordlist-based password-cracking attack.
7. Successfully recovered the password.
8. Opened the protected PDF using the recovered password to verify access.

---

## TASK 1

**TARGET:** My-Locked-PDF1.pdf

![PDF Hash Extraction](screenshots/task1-hash-extraction.png)

![Johnny Configuration](screenshots/task1-johnny-configuration.png)

![Password Cracking](screenshots/task1-password-cracking.png)

![Password Recovered](screenshots/task1-password-recovered.png)

---

## TASK 2

**TARGET:** My-Locked-PDF2.pdf

![PDF Hash Extraction](screenshots/task2-hash-extraction.png)

![Johnny Configuration](screenshots/task2-johnny-configuration.png)

![Password Cracking](screenshots/task2-password-cracking.png)

![Password Recovered](screenshots/task2-password-recovered.png)

---

## 📂 Module 2 — Password Cracking with Networkwalks Tools

### Steps

1. Selected the password-protected PDF file.
2. Opened the **Networkwalks Hash Calculator**.
3. Uploaded the PDF and generated its crackable hash.
4. Copied the complete `$pdf$...` hash.
5. Opened the **Networkwalks Password Cracker**.
6. Pasted the hash into the tool.
7. Ran the built-in dictionary attack using the available wordlist.
8. The tool identified the matching password.
9. Opened the PDF using the recovered password to verify access.

### Result

✅ **Password Cracked:** `password1`

---

## 🔑 Key Learnings

- Understanding the fundamentals of password cracking.
- Extracting crackable hashes from password-protected PDF files.
- Using **John the Ripper (JTR)** and **Johnny GUI** for password recovery.
- Working with dictionary and wordlist-based attacks.
- Using Networkwalks Hash Calculator and Password Cracker.
- Comparing offline and browser-based password-cracking approaches.
- Understanding how weak passwords can be vulnerable to dictionary attacks.
- Understanding the importance of strong passwords and secure authentication.

---

## 📸 Screenshots

Screenshots showing **hash extraction, wordlist attacks, and successful password recovery** are included in the `/screenshots` folder of this repository.

---

## ⚠️ Disclaimer

This project was performed in a **controlled academic lab environment** for educational purposes as part of a Cybersecurity Internship at Networkwalks.

Password-cracking techniques should only be used on files, systems, or accounts that you own or have **explicit authorization** to test.

---

## 👤 Author

**Sankari A.**  
B.Sc. Computer Science with Cyber Security  
PSGR Krishnammal College for Women, Coimbatore
