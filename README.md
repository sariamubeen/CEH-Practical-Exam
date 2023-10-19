# CEH-Practical-Exam
# Mastering the CEH Practical Exam: A Comprehensive Resource

## Introduction

This README provides a comprehensive resource for those preparing to take the Certified Ethical Hacker (CEH) Practical exam. Despite initial reservations about sharing my experience, the numerous requests from my professional network have prompted me to offer a detailed account. The CEH Practical exam proved to be surprisingly manageable, and this resource aims to assist others in achieving a similar level of success.

## Exam Day Setup and Procedure

The CEH Practical exam is conducted remotely via GoToMeeting. No account is required, but you must ensure that your camera and microphone are fully functional. The proctor will perform a thorough inspection of your examination room to confirm the absence of any individuals and the removal of digital devices, including mobile phones and smartwatches.

Upon initiation, the proctor will gain access to your screen, granting you entry to the browser-based Parrot machine. A Windows-based machine is also accessible through Remmina on the Parrot machine.

## Exam Experience

Here are key insights from my CEH Practical exam experience:

1. **Optimize Nmap Scanning**: Make the most of Nmap for effective host discovery using the following command:


2. **Multiple Attempts**: Each question offers up to five attempts for confirmation, and you can also skip questions. This feature eases the pressure and allows for revisiting questions.

3. **Brute Force Assistance**: Wordlists for username and password brute forcing are provided, streamlining the process.

4. **Environmental Challenges**: My exam started at an unusual time, and despite a strong 100Mbps+ connection, lag was an issue. The small browser windows required a magnifier.

5. **Early Submission**: I completed the exam within an hour. Instead of repeatedly consulting the proctor, I had already verified my answers, which boosted my confidence.

6. **Result Confirmation**: After the exam, I checked my Aspen account and found that all my answers were correct.

## Essential Tools

Here is a list of essential tools for both Windows and Linux:

**For Windows:**

1. Wireshark
2. Hashcalc
3. Cryptool
4. Snow
5. OpenStego
6. Veracrypt

**For Linux:**

1. netdiscover
2. Nmap
3. Hydra
4. John
5. wpscan
6. sqlmap
7. ADB
8. Metasploit Framework (basic knowledge)

## Additional Resources

For further assistance and practice, explore these additional resources:

1. **CEH Practical - LPT Master - CTF - Notes**: Comprehensive notes on CEH Practical and LPT Master exam topics available [here](https://blog.invid.eu/ceh-practical-lpt-master-ctf-notes/).

2. **GitHub Repositories**:
- [CyberSecurityUP/Guide-CEH-Practical-Master](https://github.com/CyberSecurityUP/Guide-CEH-Practical-Master)
- [Samson-DVS/CEH-Practical-Notes](https://github.com/Samson-DVS/CEH-Practical-Notes)
- [nirangadh/ceh-practical](https://github.com/nirangadh/ceh-practical)
- [Samsar4/Ethical-Hacking-Labs](https://github.com/Samsar4/Ethical-Hacking-Labs)
- [Rezkmike/CEH_Practical_Preparation](https://github.com/Rezkmike/CEH_Practical_Preparation)

## TryHackMe Resources

In addition to the above, engage with TryHackMe for valuable rooms and modules. Here are some of the most beneficial:

- [TryHackMe: Overpass 2 - Hacked](https://tryhackme.com/room/overpass2hacked)
- [TryHackMe: Linux Fundamentals](https://tryhackme.com/module/linux-fundamentals)
- [TryHackMe: Introduction to Offensive Pentesting](https://tryhackme.com/module/introduction-to-offensive-pentesting)
- [TryHackMe: Windows Fundamentals](https://tryhackme.com/module/windows-fundamentals)

Additionally, TryHackMe rooms covering various topics and tools will further enhance your skills:

- [Further Nmap](https://tryhackme.com/room/furthernmap)
- [Nmap 03](https://tryhackme.com/room/nmap03)
- [Nmap 04](https://tryhackme.com/room/nmap04)
- [John the Ripper 0](https://tryhackme.com/room/johntheripper0)
- [Hydra](https://tryhackme.com/room/hydra)
- [Crack The Hash](https://tryhackme.com/room/crackthehash)
- [Crack The Hash Level 2](https://tryhackme.com/room/crackthehashlevel2)
- [CCStego](https://tryhackme.com/room/ccstego)
- [Introduction to Networking](https://tryhackme.com/room/introtonetworking)
- [Protocols and Servers](https://tryhackme.com/room/protocolsandservers)
- [Protocols and Servers 2](https://tryhackme.com/room/protocolsandservers2)
- [Wireshark](https://tryhackme.com/room/wireshark)
- [OWASP Top 10](https://tryhackme.com/room/owasptop10)
- [Learn OWASP ZAP](https://tryhackme.com/room/learnowaspzap)
- [Introduction to Shells](https://tryhackme.com/room/introtoshells)
- [Pentesting Fundamentals](https://tryhackme.com/room/pentestingfundamentals)
- [RP: Metasploit](https://tryhackme.com/room/rpmetasploit)
- [EasyPeasyCTF](https://tryhackme.com/room/easypeasyctf)
- [Daily Bugle](https://tryhackme.com/room/dailybugle)
- [H4cked](https://tryhackme.com/room/h4cked)
- [Revenge](https://tryhackme.com/room/revenge)
- [OWASP Juice Shop](https://tryhackme.com/room/owaspjuiceshop)
- [Crack The Hash Level 2](https://tryhackme.com/room/crackthehashlevel2)

## Additional Commands

To bolster your CEH Practical preparation, consider these additional commands:

- `netdiscover -i eth0`: Network discovery using netdiscover.
- `nmap -p- 10.10.10.10 [Any IP]`: Scanning all ports with nmap.
- `nmap -p443,80,53,135,8080,8888 -A -O -sV -sC -T4 -oN nmapOutput 10.10.10.10`: In-depth port scanning with nmap.
- `gobuster -e -u http://10.10.10.10 -w wordlist.txt`: Directory brute-forcing with gobuster.
- `dirb http://10.10.10.10 wordlist.txt`: Directory brute-forcing with dirb.
- SQL Injections:
- `admin' --`
- `admin' #`
- `admin'/*`
- `' or 1=1 --`
- `' or 1=1#`
- `' or 1=1/*`
- `') or '1'='1 --`
- `') or ('1'='1 --`
- `',nickName=(SELECT group_concat(tbl_name) FROM sqlite_master WHERE type='table' and tbl_name NOT like 'sqlite_%'),email='`
- `',nickName=(SELECT sql FROM sqlite_master WHERE type!='meta' AND sql NOT NULL AND name ='usertable'),email='`

## Commands for Hydra, Searchsploit, Nmap, and More

Here are commands for tools like Hydra, Searchsploit, Nmap, and others:

- **Hydra**:
- `hydra -l root -P passwords.txt [-t 32] <IP> ftp`
- `hydra -L usernames.txt -P pass.txt <IP> mysql`
- `hydra -l USERNAME -P /path/to/passwords.txt -f <IP> pop3 -V`
- `hydra -V -f -L <userslist> -P <passwlist> rdp://<IP>`
- `hydra -P common-snmp-community-strings.txt target.com snmp`
- `hydra -l Administrator -P words.txt 192.168.1.12 smb t 1`
- `hydra -l root -P passwords.txt <IP> ssh`

- **Searchsploit**:
- `searchsploit "Linux Kernel"`
- `searchsploit -m 7618` (Paste the exploit in the current directory)
- `searchsploit -p 7618[.c]` (Show complete path)
- `searchsploit -- nmap file.xml` (Search vulnerabilities inside a Nmap XML result)

- **Nmap**:
- `nmap -sn 170.16.0.1/24 -oN nmap.txt`
- `nmap -O 170.16.0.1/24 -oN nmap-OS.txt`
- `namp -sC -sV -sS 170.16.0.20 -oN nmap-all.txt`

## Other Helpful Resources

For specific questions and challenges in CEH Practical, the following resources can be beneficial:

- **SQL Injection**: If you encounter questions related to SQL injection, refer to this GitHub repository for useful commands: [SQL Injection on GitHub](https://github.com/cmuppin/CEH/blob/main/SQL%20Injection).

- **Hash Cracking**: For questions related to hash cracking, this GitHub repository provides handy commands: [Cryptography on GitHub](https://github.com/cmuppin/CEH/blob/main/Cryptography).

- **Phonesploit**: If you need to exploit Android devices for a reverse shell, this GitHub repository contains helpful information: [Phonesploit on GitHub](https://github.com/cmuppin/CEH/tree/main/Android).

- **Vulnerabilities**: Familiarize yourself with common vulnerabilities and attack vectors, such as:
- SQL Injection
- IDOR (Insecure Direct Object Reference)
- Session Hijacking
- Command Injection
- File Upload Vulnerabilities
- Cross-Site Scripting (XSS)
- Parameter Tampering

## Expected Exam Questions

The CEH Practical exam typically includes questions and tasks related to the following:

- Understanding of attack vectors
- Network scanning to identify live and vulnerable machines
- OS banner grabbing, service, and user enumeration
- System hacking, steganography, steganalysis attacks, and covering tracks
- Identifying and using viruses, computer worms, and malware to exploit systems
- Packet sniffing
- Various web server and web application attacks, including directory traversal, parameter tampering, and XSS
- SQL injection attacks
- Different types of cryptography attacks
- Vulnerability analysis to identify security loopholes in the target organization's network, communication infrastructure, and end systems

## Final Thoughts

The CEH Practical exam provides an excellent opportunity to showcase your knowledge and skills in ethical hacking. With proper preparation and access to the right resources, success is well within your reach. By sharing my experience and these valuable resources, I hope to help others embark on their own successful journey to become a Certified Ethical Hacker. Wishing you the best of luck on your CEH Practical exam journey!
