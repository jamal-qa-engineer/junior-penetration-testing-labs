# junior-penetration-testing-labs


## Objective
This hands-on laboratory exercise from PortSwigger Web Security Academy focuses on identifying and exploiting SQL injection vulnerabilities in web applications. The primary objective is to demonstrate how improperly sanitized user input can be manipulated to bypass authentication mechanisms, extract sensitive data from backend databases, and compromise application security. 

Through this lab, I successfully exploited a SQL injection flaw in the application's login functionality by crafting malicious SQL queries that altered the intended logic of database commands. This practical exercise simulates real-world attack scenarios where attackers leverage SQL injection to gain unauthorized access to systems, retrieve confidential information, or modify database contents. The lab reinforced the critical importance of implementing secure coding practices, input validation, and parameterized queries to prevent SQL injection attacks in production environments.

## Skills Learned
1. Reconnaissance & Information Gathering
- Passive reconnaissance techniques (WHOIS, DNS, search engines)
- Active reconnaissance and enumeration
- Network scanning with Nmap
- Service and version detection
- Subdomain enumeration

2. Web Application Security
- Understanding the OWASP Top 10 vulnerabilities
- SQL Injection (SQLi) - detection and exploitation
- Cross-Site Scripting (XSS) - reflected, stored, and DOM-based
- Command Injection vulnerabilities
- Insecure Direct Object References (IDOR)
- Security misconfigurations
- Authentication and session management flaws
- File inclusion vulnerabilities (LFI/RFI)

3. Network Security
- Understanding network protocols (TCP/IP, HTTP, FTP, SMB, SSH)
- Network service exploitation
- Network traffic analysis
- Understanding firewall and IDS evasion techniques

4. Privilege Escalation

Linux privilege escalation techniques:
- SUID/SGID binaries
- Cron jobs exploitation
- Kernel exploits
- Sudo misconfigurations
- Path hijacking

Windows privilege escalation techniques:
- Service misconfigurations
- Registry exploits
- Token impersonation
- Scheduled tasks
- Unquoted service paths

5. Exploitation Frameworks
- Metasploit Framework fundamentals
- Module types (exploits, payloads, auxiliary, post)
- Payload generation with msfvenom
- Post-exploitation techniques
- Persistence mechanisms

6. Vulnerability Research
- Searching for public exploits (Exploit-DB, CVE databases)
- Understanding vulnerability disclosures
- Manual exploitation techniques
- Exploit modification and customization


## Tools Used
Reconnaissance
Nmap - Network scanning and enumeration
Gobuster/Dirbuster - Directory and file brute-forcing
Sublist3r - Subdomain enumeration
WHOIS - Domain information gathering
theHarvester - OSINT email and subdomain gathering

Web Application Testing
Burp Suite - Web application security testing platform
OWASP ZAP - Web application vulnerability scanner
SQLMap - Automated SQL injection exploitation
Nikto - Web server scanner
WPScan - WordPress vulnerability scanner

Exploitation
Metasploit Framework - Exploitation framework
msfvenom - Payload generator
Exploit-DB - Exploit database
SearchSploit - Local exploit database search

Post-Exploitation & Privilege Escalation
LinPEAS/WinPEAS - Privilege escalation enumeration scripts
Linux Smart Enumeration (LSE) - Linux privilege escalation checker
PowerUp - Windows privilege escalation checker
GTFOBins - Unix binaries exploitation reference

Networking
Netcat - Network utility for connections and file transfers
Wireshark - Network protocol analyzer
tcpdump - Command-line packet analyzer

Scripting & Automation
Python - Scripting and exploit development
Bash - Shell scripting for automation
PowerShell - Windows automation and post-exploitation


