# Password Cracking Lab – John the Ripper & Networkwalks Tools

## 📌 Project Overview

This repository contains practical work on PDF Password Cracking performed as part of the **Networkwalks Cybersecurity Internship Lab**.

The project demonstrates two different methods of recovering passwords from password-protected PDF files using:

1. John the Ripper (JTR) with Johnny GUI.
2. Networkwalks Hash Calculator and Password Cracker.

## 🎯 Objectives

- Understand PDF password protection.
- Extract password hashes from encrypted PDF files.
- Learn how to use John the Ripper.
- Perform password recovery using Johnny GUI.
- Explore Networkwalks Hash Calculator and Password Cracker.
- Understand the basics of password-cracking techniques.

---

## 🔹 Practical 1: Password Cracking with John the Ripper (JTR)

### 🛠️ Tools Used

- John the Ripper
- Johnny GUI
- Online PDF Hash Extractor
- Windows PC

### 🔗 Useful Links

- [John the Ripper Official Website](https://www.openwall.com/john/)
- [John the Ripper Download](https://distro.ibiblio.org/openwall/projects/john/1.9.0/)
- [Johnny GUI](https://openwall.info/wiki/john/johnny)
- [Online PDF Hash Extractor](https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php)

### ⚙️ Steps Performed

1. Downloaded John the Ripper on Windows.
2. Downloaded and installed Johnny GUI.
3. Configured Johnny by selecting the `john.exe` file from the `run` folder.
4. Downloaded the password-protected PDF file.
5. Uploaded the PDF to the Online PDF Hash Extractor.
6. Extracted and copied the PDF hash.
7. Saved the hash in a text file named `hash1.txt`.
8. Opened Johnny GUI and loaded the hash file.
9. Started a new password-cracking attack.
10. Waited for the password recovery process to complete.
11. Used the recovered password to open the PDF file.

### 🏁 Captured Flags

```text
nw{cybersecurity_flag_captured_2608}

nw{networkwalks_flag_260821_1}

nw{networkwalks_persistence_jtr_270521}
```

---

## 🔹 Practical 2: Password Cracking with Networkwalks Tools

### 🛠️ Tools Used

- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Web Browser
- Windows Laptop

### 🔗 Useful Links

- [Networkwalks Lab](https://networkwalks.com/project-task-lab-password-cracking-with-networkwalks-tools/)
- [Networkwalks Hash Calculator](https://networkwalks.com/hash-calculator/)
- [Networkwalks Password Cracker](https://networkwalks.com/password-cracker/)

### ⚙️ Steps Performed

1. Downloaded the password-protected PDF file from the Networkwalks lab page.
2. Opened the Networkwalks Hash Calculator in a web browser.
3. Uploaded the locked PDF file to extract its hash.
4. Copied the complete hash value starting with `$pdf$`.
5. Opened the Networkwalks Password Cracker.
6. Pasted the extracted hash into the Password Cracker.
7. Started the password-cracking process.
8. Waited for the tool to find the matching password.
9. Retrieved the recovered password.
10. Opened the protected PDF using the recovered password.

### 🏁 Captured Flag

```text
nw{networkwalks_flag1_jtr_270521_1}
```

---

## 📚 Key Learnings

- Understanding PDF password protection.
- Extracting PDF hashes.
- Working with John the Ripper.
- Using Johnny GUI for password recovery.
- Using online hash extraction tools.
- Understanding hash-based password-cracking techniques.
- Learning practical cybersecurity tools and methodologies.

## 🧰 Technologies & Tools

| Tool | Purpose |
|---|---|
| John the Ripper | Password Cracking |
| Johnny GUI | Graphical Interface for JTR |
| Networkwalks Hash Calculator | PDF Hash Extraction |
| Networkwalks Password Cracker | Password Recovery |
| Windows | Operating System |

## 📝 Conclusion

Successfully completed both password-cracking practicals using John the Ripper and Networkwalks tools.

This hands-on experience helped me understand PDF hash extraction, password recovery techniques, and the practical use of cybersecurity tools.

## ⚠️ Disclaimer

This project is created for educational purposes as part of cybersecurity training. These techniques should only be used on files and systems that you own or have explicit permission to test.

---

**Internship:** Networkwalks Cybersecurity Internship  
**Domain:** Cybersecurity  
**Project:** Password Cracking Lab
