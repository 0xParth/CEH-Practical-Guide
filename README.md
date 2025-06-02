# CEH-Practical-Guide
This Repo will help you to prepare better for CEH - Practical Exam

### Exam Information 
 - Exam Title: Certified Ethical Hacker (Practical)
 - Number of Challenges: 20
 - Duration: 6 hours
 - Passing Score: 70% (14 Questions)
 ---------------------------------------------
 ### My Experience
 - If you are doing bug bounty hunting, then you are half way there.
 - NMAP and wordpress knowledge is really important.
 - Best part - Google searches are allowed (💥)
 - Cryptographic knowledge is important
 - SQL Injection plays a major role
 - Simple User Enumeration and OS Banner grabbing
 - Stegnography
 - RDP Connection
 ---------------------------------------------
 ### Tools that will help you to pass exam
 1. NMAP
 2. SQLMap
 3. Hydra
 4. Wireshark
 5. Veracrypt
 6. Hashcalc
 7. Dirb
 8. Steghide
 9. Searchsploit
 10. Hashcat
 11. John
 12. WPSCAN
 13. Rainbow crack ( This helped me to get my first 3 question answers! )
 14. Nikto
 15. Metasploit
 ---------------------------------------------
 ### Resources
 1. If you can pay then the best resource is ASPEN iLabs.
 2. VulnHub
 3. Tryhackme ( Different related rooms like crackthehash, wirectf, hydra, sqli)
 4. ASPEN iLabs YT video ( https://www.youtube.com/watch?v=ycZFk-GT5-I&list=PLrrgFyE6PtlaCixUxJPM0Y9Peye6iCewH )
  ---------------------------------------------
  ### Sample Questions
  1. Which username was tampered? ( You need to solving by comparing Hash values)
  2. Wordpress Username Enumeration!
  3. Retrieve Database names ( SQLi)
  4. How many machines are there? ( NMAP)
  5. Phone number of User X? ( Metasploit/Parameter Tampering)
  6. What is the hidden text in X.jpeg (STEGHIDE)
  7. Password crack for VCRYPT
  8. IP Address/ Version of Running windows Server.
   ---------------------------------------------
   ### Some of the commands used by me
  1. hydra -l root -P passwords.txt [-t 32] <IP> ftp [ https://securitytutorials.co.uk/brute-forcing-passwords-with-thc-hydra/]
  2. hydra -L usernames.txt -P pass.txt <IP> mysql
  3. hashcat.exe -m hash.txt rokyou.txt -O
  4. nmap -p443,80,53,135,8080,8888 -A -O -sV -sC -T4 -oN nmapOutput 10.10.10.10 [https://www.stationx.net/nmap-cheat-sheet/]
  5. wpscan --url https://10.10.10.10/ --enumerate u
  6. netdiscover -i eth0 [ https://www.100security.com.br/netdiscover ]
  7. john --format=raw-md5 password.txt [ To change password to plain text ]
 ---------------------------------------------
 
 ### About the Author

 **0xParth** is a passionate cybersecurity professional who brings together expertise in multiple domains:

 - **💻 Security Analyst** - Specializing in vulnerability assessment and security testing
 - **🏹 Bug Bounty Hunter** - Active participant in bug bounty programs
 - **👱‍💤 Community Leader** - Leading and contributing to the security community
 - **📷 YouTuber** - Creating educational content at [@BUGXS](https://youtube.com/@BUGXS)

 #### Connect with 0xParth:
 - **Instagram**: [@0xparth](https://instagram.com/0xparth)
 - **LinkedIn**: [/in/parthshu18](https://linkedin.com/in/parthshu18)
 - **Twitter**: [@0xparth](https://twitter.com/0xparth)
 - **Medium**: [@0xParth](https://medium.com/@0xParth)
 - **YouTube**: [@BUGXS](https://youtube.com/@BUGXS)

 #### Tech Stack:
 C, JavaScript, Python, Shell Script, Linux, Jira, Docker, Postman

 #### Other Projects by 0xParth:
 - **[CEH-Practical-Guide](https://github.com/0xParth/CEH-Practical-Guide)** - This Repo will help you to prepare better for CEH - Practical Exam (50 ⭐)
 - **[All-Bug-Dorks](https://github.com/0xParth/All-Bug-Dorks)** - Google dorks to find Bug Bounty Programs (1 ⭐)
 - **[API_Labs](https://github.com/0xParth/API_Labs)** - Creating API labs for Classes
 - **[Network_Scanner](https://github.com/0xParth/Network_Scanner)** - Network scanner utility
 - **[MAC_Changer](https://github.com/0xParth/MAC_Changer)** - This script will help you out to change your MAC Address temporarily!
 - **[takeoveer](https://github.com/0xParth/takeoveer)** - Subdomain takeover toolkit
 - **[0xParth](https://github.com/0xParth/0xParth)** - Config files for my GitHub profile
 - **[0xparth.github.io](https://github.com/0xParth/0xparth.github.io)** - Personal website
 - **RecIT** - Ultimate Recon Script 💥 (Private) - [📖 Detailed Guide](./RecIT-Project-Details.md)
 - **Recon-V2.0** - Backup to /Recon/V2.0 (Private)
 - **certsubs-corp** - Certsubs for Enterprise (Private)
 - **recon** - Reconnaissance tools (Private)
 - **hackathon** - Hackathon projects (Private)
 - **certsubs-app** - Certsubs for Bug Bounty Hunters (Private)
 - **pyRIT_Wrapper** - PyRIT wrapper utility (Private)
 - **allsubz** - All subdomains finder (Private)
 - **IntentClassifier** - Intent classification tool (Private)
 - **PromptGuard** - Prompt protection utility (Private)
 - **DocuCraft-AI** - AI-powered documentation tool (Private)
 - **credential-stuffing** - Credential stuffing testing (Private)

 ---------------------------------------------
 ### Reach out in case of further help
 Instagram: https://www.instagram.com/bug_xs/
 
 Thank you for reading!! 🙌🙌
