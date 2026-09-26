Here is the readable content of your Week 3 report:

WEEK 3 – PASSWORD CRACKING PROJECT

Cybersecurity Training / Practical Project Report
Internship – Week 3 Task
Submitted by: Gokul R

1. Project Overview

Week 3 focused on practical password-cracking techniques in an authorized cybersecurity training environment provided by NetworkWalks Academy.

The two mandatory modules were:

Password Cracking with John the Ripper (JTR)

Password Cracking with NetworkWalks Tools


2. Objectives

Understand the basic workflow of password cracking.

Extract a crackable hash from a password-protected PDF.

Use a wordlist to test candidate passwords.

Perform password recovery with John the Ripper.

Use the NetworkWalks hash calculator and password-cracking module.

Verify successful matches and capture training completion evidence.


3. Tools and Technologies

Kali Linux

John the Ripper (JTR)

RockYou wordlist

NetworkWalks Hash Calculator

NetworkWalks Password Cracker

Password-protected PDF test files


4. Module 1 – Password Cracking with JTR

The password-protected PDF test files were converted/extracted into a crackable PDF hash format using the NetworkWalks Hash Calculator.

The RockYou wordlist available in Kali Linux was then used with John the Ripper. JTR tested candidate passwords from the wordlist until a matching password was found.

4.1 Hash Extraction

Each locked PDF was uploaded to the NetworkWalks Hash Calculator, which produced a crackable PDF hash in pdf2john/hashcat-compatible format.

4.2 Wordlist Preparation

The RockYou wordlist was prepared in the Kali Linux wordlists directory:

/usr/share/wordlists/

Command:

sudo gzip -d /usr/share/wordlists/rockyou.txt.gz

4.3 JTR Result

John the Ripper was run against each extracted hash using the PDF format and RockYou wordlist.

JTR successfully found matches for all three supplied training hashes.

Recovered passwords shown in the report:

password1

password1

1qaz2wsx


5. Module 2 – Password Cracking with NetworkWalks Tools

The second module used the NetworkWalks training tools.

Each password-protected PDF was loaded into the hash calculator, which extracted a crackable PDF hash. The generated hash was then used with the NetworkWalks Password Cracker workflow.

The report records successful password recovery after a number of attempts.

6. Training Flags / Completion Evidence

The training platform displayed completion flags after each successful task, confirming that the modules were completed correctly.

7. Results

W3-PM1: Password Cracking with JTR — Completed successfully.

W3-PM2: Password Cracking with NetworkWalks Tools — Completed successfully.

PDF hashes were successfully extracted for the supplied lab files.

Wordlist-based password recovery was successfully demonstrated.

Training completion evidence was captured for both modules.


8. Learning Outcomes

Understood the relationship between a protected file, its hash, and password recovery.

Gained hands-on familiarity with John the Ripper.

Learned how a wordlist such as RockYou is used during password cracking.

Practiced reading cracking progress, attempts, and successful matches.

Learned a second workflow using a web-based cybersecurity training tool.

Improved practical documentation and evidence collection skills.


9. Security and Ethical Considerations

Password cracking must only be performed against systems and files for which explicit authorization has been provided.

This project used intentionally supplied training material within the NetworkWalks Academy lab environment. Real credentials, private hashes, or unauthorized targets must not be tested.

10. Conclusion

Week 3 provided practical experience with password-cracking workflows using both John the Ripper and NetworkWalks tools. The required modules were completed in the authorized training environment, and the workflow was documented with supporting evidence.
