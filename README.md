# Tech Biz Security: Ethical Hacking Internship

**18 hands-on tasks. 6 weeks. From "what is the CIA triad?" to a full penetration test with a root shell.**

Hi, I'm **Mah Noor**, a BS Information Technology student specializing in cybersecurity, working towards becoming a cybersecurity analyst. This repository is my complete record of the Tech Biz Security Ethical Hacking internship (August to September 2026). Every task has its own report with commands, screenshots and what I found.

---

## What I did

I started with the basics (how networks, Linux and the web work), built my own attack lab, and then moved step by step through the real phases of ethical hacking:

**Foundations → Lab setup → Recon → Scanning → Enumeration → Web attacks → Exploitation → Password attacks → Full pentest**

Everything was done in safe, legal lab environments: my own Kali Linux VM, Metasploitable 2, DVWA and TryHackMe rooms.

---

## All 18 tasks

| # | Task | What I did | Report |
|---|------|-----------|--------|
| 01 | Intro to Cybersecurity | CIA triad, hacker types, 5 phases of ethical hacking, pentest vs vulnerability assessment | [Report (docx)](reports/Task-01_Intro-to-Cybersecurity_Report.docx) |
| 02 | Networking Basics | IP and MAC addresses, ports, TCP vs UDP, OSI model, `ipconfig` | [PDF](reports/Task-02_Networking-Basics.pdf) |
| 03 | Kali Lab Setup | Kali Linux VM in VMware, verified with `whoami`, `ip a`, `apt update` | [PDF](reports/Task-03_Kali-Lab-Setup.pdf) |
| 04 | Linux Fundamentals | Navigation, files, `chmod`/`chown` permissions, installing tools with `apt` | [PDF](reports/Task-04_Linux-Fundamentals.pdf) |
| 05 | Networking Tools and Subnetting | `ping`, `traceroute`, `nslookup`, `netstat`, CIDR subnetting | [PDF](reports/Task-05_Networking-Tools-and-Subnetting.pdf) |
| 06 | Vulnerable Lab Setup | Metasploitable 2 and DVWA target, connected to Kali on an isolated network | [PDF](reports/Task-06_Vulnerable-Lab-Setup.pdf) |
| 07 | Passive Recon and OSINT | WHOIS, Google Dorking, theHarvester on a public domain | [PDF](reports/Task-07_Passive-Recon-OSINT.pdf) |
| 08 | *(report to be added)* | | |
| 09 | Enumeration | `smbclient`, `enum4linux`, banner grabbing on SMB, FTP and SSH | [PDF](reports/Task-09_Enumeration.pdf) |
| 10 | Vulnerability Scanning | Nmap `-sV` and NSE `vuln` scripts, mapping findings to CVEs | [PDF](reports/Task-10_Vulnerability-Scanning.pdf) |
| 11 | HTTP and Burp Suite | HTTP requests/responses, cookies, intercepting traffic with Burp Suite | [PDF](reports/Task-11_HTTP-and-Burp-Suite.pdf) |
| 12 | OWASP Top 10 | The 10 most common web vulnerabilities, real breach examples, TryHackMe rooms | [PDF](reports/Task-12_OWASP-Top-10.pdf) |
| 13 | SQL Injection | Exploiting SQLi on DVWA and how to fix it | [PDF](reports/Task-13_SQL-Injection.pdf) |
| 14 | Cross-Site Scripting (XSS) | Reflected and stored XSS on DVWA | [PDF](reports/Task-14_Cross-Site-Scripting.pdf) |
| 15 | Brute Force | Hydra with `rockyou.txt` against a login form, plus defenses | [PDF](reports/Task-15_Brute-Force-Hydra.pdf) |
| 16 | Metasploit | Exploited Samba (CVE-2007-2447) on Metasploitable 2 and got a root shell | [PDF](reports/Task-16_Metasploit.pdf) |
| 17 | Password Cracking | MD5, SHA-256, bcrypt, hashing vs encryption, John the Ripper | [PDF](reports/Task-17_Password-Cracking.pdf) |
| 18 | Capstone: Full Pentest | Recon, scanning, enumeration and exploitation of Metasploitable 2 in one report | [PDF](reports/Task-18_Capstone-Pentest.pdf) |

---

## Tools and platforms

Kali Linux · VMware · Nmap · enum4linux · smbclient · netcat · theHarvester · WHOIS · Burp Suite · DVWA · Hydra · Metasploit Framework · John the Ripper · TryHackMe

## What I learned

- **Think in phases.** Recon, scanning, enumeration and exploitation each answer a different question. Skipping one makes the next one weaker.
- **Open does not mean safe.** In my enumeration and scanning tasks, an anonymous SMB login and outdated services turned into real findings.
- **One old bug can mean full control.** The Samba CVE-2007-2447 exploit gave root access with no password, which showed me why patching matters.
- **Weak passwords fall fast.** Hydra and John the Ripper with a wordlist showed how quickly bad passwords break, and why bcrypt and rate limiting exist.
- **Web bugs are about trusting input.** SQL injection, XSS and brute force all work because an app trusts what the user sends.
- **Write it down.** Every task taught me to document steps, evidence and fixes so someone else can repeat my work.

---

## Note

All testing was done on intentionally vulnerable machines and training platforms I own or am allowed to use. This repository is for learning purposes only.

## Connect

Mah Noor · Aspiring Cybersecurity Analyst · BS IT (Cybersecurity)
