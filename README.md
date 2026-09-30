# NETWORKWALKS-B083-WK3-PASSWORD-CRACKING
Yes — for a GitHub README.md, you can copy this directly. I’ve kept it professional and based on the actual work you described.

Week 3 Password Cracking README
🔐 NETWORKWALKS-B083-WK3-PASSWORD-CRACKING
📌 Overview

Password Cracking is a cybersecurity technique used to test and recover passwords by systematically trying possible password candidates through methods such as dictionary and brute-force attacks.

As part of my Week 3 Cybersecurity Internship task at Networkwalks, I performed a hands-on password-cracking exercise using password-protected PDF files in an authorized lab environment.

The task involved two different approaches:

Module 1: Password Cracking using John the Ripper (JTR) & Johnny GUI
Module 2: Password Cracking using Networkwalks Hash Calculator & Password Cracker

The objective was to understand how password hashes are extracted, how wordlists are used in password recovery, and why strong passwords are important for security.

🎯 Objectives
Understand the fundamentals of password cracking.
Extract crackable hashes from password-protected PDF files.
Perform dictionary-based password attacks using wordlists.
Learn to use John the Ripper and Johnny GUI.
Explore Networkwalks Hash Calculator and Password Cracker.
Compare offline and browser-based password-cracking approaches.
Understand the importance of strong and secure passwords.
🛠️ Tools & Technologies
Category	Tools
Password Cracking	John the Ripper (JTR)
GUI	Johnny
Hash Extraction	PDF Hash Extractor / pdf2john
Online Tools	Networkwalks Hash Calculator
Password Recovery	Networkwalks Password Cracker
Attack Type	Dictionary / Wordlist Attack
Target	Password-Protected PDF
📂 Module 1 — John the Ripper & Johnny GUI
🔹 Process
Downloaded and configured John the Ripper and Johnny GUI.
Configured the john.exe path in Johnny.
Selected a password-protected PDF for testing.
Extracted the crackable PDF hash using a PDF hash extraction tool.
Saved the extracted $pdf$... hash into a text file.
Loaded the hash file into Johnny.
Started a wordlist-based password-cracking attack.
Successfully recovered the password.
Verified the recovered password by opening the protected PDF.
✅ Result

The password of the test PDF was successfully recovered using John the Ripper / Johnny.

📂 Module 2 — Networkwalks Hash Calculator & Password Cracker
🔹 Process
Selected the password-protected PDF file.
Opened the Networkwalks Hash Calculator.
Uploaded the PDF and generated its crackable hash.
Copied the complete hash value.
Opened the Networkwalks Password Cracker.
Entered the extracted hash.
Performed a dictionary attack using the available wordlist.
The tool identified the matching password.
Verified the recovered password by opening the PDF.
✅ Result

The password was successfully recovered using the Networkwalks Hash Calculator and Password Cracker.

📊 Comparison
Feature	John the Ripper + Johnny	Networkwalks Tools
Installation	Required	Browser-based
Interface	GUI	Web interface
Hash Extraction	PDF Hash Extractor	Hash Calculator
Attack Method	Wordlist-based	Dictionary-based
Wordlists	Customizable	Built-in
Flexibility	High	Limited
Setup	More configuration	Quick setup
🔑 Key Learnings
Understanding password-cracking fundamentals
Extracting crackable hashes from protected PDF files
Using John the Ripper (JTR) for password recovery
Working with Johnny GUI
Understanding dictionary and wordlist attacks
Using online hash calculation and password-cracking tools
Comparing offline and browser-based approaches
Understanding how weak passwords can be recovered through dictionary attacks
Recognizing the importance of strong password security
🛡️ Security Takeaways

This practical exercise demonstrated why weak and commonly used passwords can be vulnerable to dictionary-based attacks.

Recommended security practices include:

Use long and unique passwords.
Avoid commonly used or predictable passwords.
Use a password manager to generate unique passwords.
Enable multi-factor authentication where available.
Protect sensitive files with appropriate encryption and access controls.
📸 Screenshots

Screenshots demonstrating the different stages of the practical task are included in the repository.

Hash Extraction




John the Ripper / Johnny




Password Cracking




Successful Recovery




Update the image filenames above to match the screenshots in your repository.

📁 Repository Structure
NETWORKWALKS-B083-WK3-PASSWORD-CRACKING/
│
├── README.md
│
├── screenshots/
│   ├── hash-extraction.png
│   ├── johnny-cracking.png
│   ├── password-cracking.png
│   └── password-recovered.png
│
└── documents/
    └── task-report.pdf
⚠️ Disclaimer

This project was performed in a controlled academic lab environment as part of my Cybersecurity Internship at Networkwalks.

All password-cracking activities were conducted for educational purposes using test files. Password-cracking techniques should only be used on files, systems, or accounts that you own or have explicit authorization to test.

👩‍💻 Internship Information

Organization: Networkwalks
Task: Week 3 — Password Cracking
Domain: Cybersecurity & Ethical Hacking
Focus: Password Security, Hash Extraction, Dictionary Attacks & Password Recovery

# NETWORKWALKS-B083-WK3-PASSWORD-CRACKING
PASSWORD CRACKING USING JOHN THE RIPPER AND NETWORKWALKS TOOL

## 📌 Overview
**Password cracking** is a cybersecurity technique used to recover or test the strength of passwords by systematically trying possible passwords through methods such as dictionary attacks, brute-force attacks, and password-guessing techniques. It is commonly used in authorized security testing to identify weak passwords and improve overall system security. This repository documents the **Week 3 Project Tasks**, focusing on **password cracking** of a protected PDF file using two different approaches:

1. **Module 1** – Password Cracking with **John the Ripper (JTR) & Johnny GUI**
2. **Module 2** – Password Cracking with **Networkwalks Hash Calculator & Password Cracker (online tools)**

Both tasks aim to recover the password protecting the same PDF file and demonstrate how weak passwords can be cracked quickly using dictionary-based attacks.

---

## 🎯 Objective
- Understand how password hashes are extracted from protected files.
- Learn how dictionary/wordlist-based password cracking works.
- Compare an offline tool (JTR + Johnny) with an online browser-based tool (Networkwalks Hash Calculator + Password Cracker).
- Reinforce why strong, complex passwords are essential for security.

---

## 🛠️ Tools Used

| Task | Tools |
|------|-------|
| Module 1 | John the Ripper (JTR), Johnny GUI, Online Hash Crack (PDF Hash Extractor) |
| Module 2 | Networkwalks Hash Calculator, Networkwalks Password Cracker |


---

## 📂 Module 1 — Password Cracking with JTR

### Steps
1. Downloaded **John the Ripper** and **Johnny GUI** from the official Openwall sources.
2. Installed Johnny and set the path to john.exe under Settings.
3. Extracted the PDF's crackable hash using the online PDF Hash Extractor tool (pdf2john equivalent).
4. Saved the extracted hash (starting with $pdf$...) into a text file (hash1.txt).
5. Opened the hash file in Johnny and clicked **Start new attack**.
6. Johnny successfully cracked the password.
7. Opened the PDF using the cracked password to confirm access.
---
## TASK 1 
TARGET : My-Locked-PDF1.pdf

![Purpose](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING-ZENMAP/blob/54c6b779ac3bf0852ba6377de34b19660c16ee9e/ZENMAP%201.png)


![Purpose](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING-ZENMAP/blob/54c6b779ac3bf0852ba6377de34b19660c16ee9e/ZENMAP%201.png)

![Purpose](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING-ZENMAP/blob/54c6b779ac3bf0852ba6377de34b19660c16ee9e/ZENMAP%201.png)



![Purpose](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING-ZENMAP/blob/54c6b779ac3bf0852ba6377de34b19660c16ee9e/ZENMAP%201.png)
---
## TASK 2
TARGET : My-Locked-PDF2.pdf
![Purpose](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING-ZENMAP/blob/54c6b779ac3bf0852ba6377de34b19660c16ee9e/ZENMAP%201.png)


![Purpose](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING-ZENMAP/blob/54c6b779ac3bf0852ba6377de34b19660c16ee9e/ZENMAP%201.png)

![Purpose](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING-ZENMAP/blob/54c6b779ac3bf0852ba6377de34b19660c16ee9e/ZENMAP%201.png)



![Purpose](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING-ZENMAP/blob/54c6b779ac3bf0852ba6377de34b19660c16ee9e/ZENMAP%201.png)
---
## TASK 3
TARGET : My-Locked-PDF2.pdf
![Purpose](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING-ZENMAP/blob/54c6b779ac3bf0852ba6377de34b19660c16ee9e/ZENMAP%201.png)


![Purpose](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING-ZENMAP/blob/54c6b779ac3bf0852ba6377de34b19660c16ee9e/ZENMAP%201.png)

![Purpose](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING-ZENMAP/blob/54c6b779ac3bf0852ba6377de34b19660c16ee9e/ZENMAP%201.png)



![Purpose](https://github.com/KanishkaManikandan5/NETWORKWALKS-B083-WK2-PENETRATION-TESTING-ZENMAP/blob/54c6b779ac3bf0852ba6377de34b19660c16ee9e/ZENMAP%201.png)


---

## 📂 Module 2 — Password Cracking with Networkwalks Tools

### Steps
1. Downloaded the locked PDF file (My Locked PDF1.pdf).
2. Opened the **Networkwalks Hash Calculator** and uploaded the PDF.
3. The tool extracted a hashcat/pdf2john-compatible hash ($pdf$...).
4. Copied the full hash value.
5. Opened the **Networkwalks Password Cracker** (dictionary attack tool).
6. Pasted the hash and ran the built-in wordlist attack (100 passwords).
7. The tool matched and displayed the cracked password.
8. Opened the PDF using the recovered password to confirm success.

### Result
✅ **Password Cracked:** password1

---

## 🔑 Key Learnings
- Password-protected files store passwords as **hashes**, not plaintext.
- Hashing is a **one-way function**; cracking relies on trying candidate passwords (dictionary/wordlist attacks) and comparing hashes, not reversing them.
- A short, common password like password1 can be cracked within seconds/minutes.
- Both offline (JTR/Johnny) and online (Networkwalks) tools achieve the same result — the offline tool offers more flexibility (custom wordlists, rules), while the online tool is faster to set up with no installation.
- Strong passwords (12+ characters, mixed case, numbers, symbols) drastically increase cracking time and are essential for real-world protection.

---

## 📸 Screenshots
Screenshots of each step (hash extraction, wordlist attack in progress, and successful crack) are included in the /screenshots folder of this repository.

---

## ⚠️ Disclaimer
This project was performed in a **controlled academic lab environment** for educational purposes only, as part of a Cybersecurity & Ethical Hacking course. Password cracking techniques should only be used on systems/files you own or have explicit authorization to test.

---

## 👤 Author
**Kanishka M**
Final Year B.Sc. Computer Science (Cyber Security)
PSGR Krishnammal College for Women, Coimbatore like this onnly want 

Yes — you want the same format and structure, just cleaned up and suitable for your Week 3 GitHub README.md. I would also remove the repeated incorrect Zenmap links and use proper screenshot placeholders.

NETWORKWALKS-B083-WK3-PASSWORD-CRACKING README
NETWORKWALKS-B083-WK3-PASSWORD-CRACKING
PASSWORD CRACKING USING JOHN THE RIPPER AND NETWORKWALKS TOOL
📌 Overview

Password cracking is a cybersecurity technique used to recover or test the strength of passwords by systematically trying possible passwords through methods such as dictionary attacks, brute-force attacks, and password-guessing techniques. It is commonly used in authorized security testing to identify weak passwords and improve overall system security.

This repository documents the Week 3 Project Tasks, focusing on password cracking of protected PDF files using two different approaches:

Module 1 – Password Cracking with John the Ripper (JTR) & Johnny GUI
Module 2 – Password Cracking with Networkwalks Hash Calculator & Password Cracker

Both tasks demonstrate how dictionary-based attacks can be used to recover weak passwords in an authorized lab environment.

🎯 Objective
Understand how password hashes are extracted from protected files.
Learn how dictionary/wordlist-based password cracking works.
Use John the Ripper and Johnny GUI for password recovery.
Explore Networkwalks Hash Calculator and Password Cracker.
Compare offline and browser-based password-cracking approaches.
Understand the importance of strong and secure passwords.
🛠️ Tools Used
Task	Tools
Module 1	John the Ripper (JTR), Johnny GUI, PDF Hash Extractor
Module 2	Networkwalks Hash Calculator, Networkwalks Password Cracker
📂 Module 1 — Password Cracking with JTR
Steps
Downloaded John the Ripper and Johnny GUI from the official Openwall sources.
Installed Johnny and configured the path to john.exe under Settings.
Extracted the PDF's crackable hash using a PDF Hash Extractor (pdf2john equivalent).
Saved the extracted hash, starting with $pdf$..., into a text file (hash1.txt).
Opened the hash file in Johnny.
Started a new wordlist-based attack.
Johnny successfully recovered the password.
Opened the PDF using the recovered password to confirm access.
TASK 1

TARGET: My-Locked-PDF1.pdf













TASK 2

TARGET: My-Locked-PDF2.pdf













TASK 3

TARGET: My-Locked-PDF2.pdf













📂 Module 2 — Password Cracking with Networkwalks Tools
Steps
Downloaded the locked PDF file (My Locked PDF1.pdf).
Opened the Networkwalks Hash Calculator and uploaded the PDF.
The tool extracted a PDF hash in $pdf$... format.
Copied the complete hash value.
Opened the Networkwalks Password Cracker.
Pasted the hash into the password-cracking tool.
Ran the built-in dictionary attack using the available wordlist.
The tool matched and displayed the password.
Opened the PDF using the recovered password to confirm successful access.
Result

✅ Password Cracked: password1

🔑 Key Learnings
Understanding the fundamentals of password cracking.
Extracting crackable hashes from password-protected PDF files.
Using John the Ripper (JTR) and Johnny GUI for password recovery.
Working with dictionary and wordlist-based attacks.
Using Networkwalks Hash Calculator and Password Cracker.
Comparing offline and browser-based password-cracking approaches.
Understanding how weak and commonly used passwords can be vulnerable to dictionary attacks.
Understanding the importance of strong passwords and secure authentication.
📸 Screenshots

Screenshots showing hash extraction, tool configuration, wordlist attacks, and successful password recovery are included in the /screenshots folder of this repository.

⚠️ Disclaimer

This project was performed in a controlled academic lab environment for educational purposes as part of a Cybersecurity & Ethical Hacking internship.

Password-cracking techniques should only be used on files, systems, or accounts that you own or have explicit authorization to test.

👤 Author

Sankari A.
B.Sc. Computer Science with Cyber Security
PSGR Krishnammal College for Women, Coimbatore

give the code for readme 

Copy everything below directly into your README.md file:

# NETWORKWALKS-B083-WK3-PASSWORD-CRACKING
## PASSWORD CRACKING USING JOHN THE RIPPER AND NETWORKWALKS TOOL

## 📌 Overview

**Password cracking** is a cybersecurity technique used to recover or test the strength of passwords by systematically trying possible passwords through methods such as dictionary attacks, brute-force attacks, and password-guessing techniques. It is commonly used in authorized security testing to identify weak passwords and improve overall system security.

This repository documents the **Week 3 Project Tasks**, focusing on **password cracking of protected PDF files** using two different approaches:

1. **Module 1** – Password Cracking with **John the Ripper (JTR) & Johnny GUI**
2. **Module 2** – Password Cracking with **Networkwalks Hash Calculator & Password Cracker**

Both tasks demonstrate how dictionary-based attacks can be used to recover weak passwords in an authorized lab environment.

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
2. Installed Johnny and configured the path to `john.exe` under Settings.
3. Extracted the PDF's crackable hash using a PDF Hash Extractor (`pdf2john` equivalent).
4. Saved the extracted hash, starting with `$pdf$...`, into a text file (`hash1.txt`).
5. Opened the hash file in Johnny.
6. Started a new wordlist-based attack.
7. Johnny successfully recovered the password.
8. Opened the PDF using the recovered password to confirm access.

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

## TASK 3

**TARGET:** My-Locked-PDF2.pdf

![Hash Extraction](screenshots/task3-hash-extraction.png)

![Hash File](screenshots/task3-hash-file.png)

![Password Cracking](screenshots/task3-password-cracking.png)

![Successful Recovery](screenshots/task3-password-recovered.png)

---

## 📂 Module 2 — Password Cracking with Networkwalks Tools

### Steps

1. Downloaded the locked PDF file (`My Locked PDF1.pdf`).
2. Opened the **Networkwalks Hash Calculator** and uploaded the PDF.
3. The tool extracted a PDF hash in `$pdf$...` format.
4. Copied the complete hash value.
5. Opened the **Networkwalks Password Cracker**.
6. Pasted the hash into the password-cracking tool.
7. Ran the built-in dictionary attack using the available wordlist.
8. The tool matched and displayed the password.
9. Opened the PDF using the recovered password to confirm successful access.

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
- Understanding how weak and commonly used passwords can be vulnerable to dictionary attacks.
- Understanding the importance of strong passwords and secure authentication.

---

## 📸 Screenshots

Screenshots showing **hash extraction, tool configuration, wordlist attacks, and successful password recovery** are included in the `/screenshots` folder of this repository.

---

## ⚠️ Disclaimer

This project was performed in a **controlled academic lab environment** for educational purposes as part of a Cybersecurity & Ethical Hacking internship.

Password-cracking techniques should only be used on files, systems, or accounts that you own or have **explicit authorization** to test.

---

## 👤 Author

**Sankari A.**  
B.Sc. Computer Science with Cyber Security  
PSGR Krishnammal College for Women, Coimbatore
