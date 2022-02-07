# CEH-Practical-Guide
This Repo will help you to prepare better for CEH - Practical Exam

### Exam Information 
 - Exam Title: Certified Ethical Hacker (Practical)
 - Number of Challenges: 20
 - Duration: 6 hours
 - Passing Score: 70% (14 Questions)
 ----------------------------------------------------------
 ### My Experince
 - If you are doing bug bounty hunting, then you are half way there.
 - NMAP and wordpress knowledge is really important.
 - Best part - Google searches are allowed (💥)
 - Cryptographic knowledge is important
 - SQL Injection plays a major role
 - Simple User Enumeration and OS Banner grabbing
 - Stegnography
 - RDP Connection
 ----------------------------------------------------------
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
 ----------------------------------------------------------
 ### Resources
 1. If you can pay then the best resource is ASPEN iLabs.
 2. VulnHub
 3. Tryhackme ( Different related rooms like crackthehash, wirectf, hydra, sqli)
 4. ASPEN iLabs YT video ( https://www.youtube.com/watch?v=ycZFk-GT5-I&list=PLrrgFyE6PtlaCixUxJPM0Y9Peye6iCewH )
  ----------------------------------------------------------
  ### Sample Questions
  1. Which username was tampered? ( You need to solving by comparing Hash values)
  2. Wordpress Username Enumeration!
  3. Retrieve Database names ( SQLi)
  4. How many machines are there? ( NMAP)
  5. Phone number of User X? ( Metasploit/Parameter Tampering)
  6. What is the hidden text in X.jpeg (STEGHIDE)
  7. Password crack for VCRYPT
  8. IP Address/ Version of Running windows Server.
   ----------------------------------------------------------
   ### Some of the commands used by me
  1. hydra -l root -P passwords.txt [-t 32] <IP> ftp [ https://securitytutorials.co.uk/brute-forcing-passwords-with-thc-hydra/]
  2. hydra -L usernames.txt -P pass.txt <IP> mysql
  3. hashcat.exe -m hash.txt rokyou.txt -O
  4. nmap -p443,80,53,135,8080,8888 -A -O -sV -sC -T4 -oN nmapOutput 10.10.10.10 [https://www.stationx.net/nmap-cheat-sheet/]
  5. wpscan --url https://10.10.10.10/ --enumerate u
  6. netdiscover -i eth0 [ https://www.100security.com.br/netdiscover ]
  7. john --format=raw-md5 password.txt [ To change password to plain text ]
  ----------------------------------------------------------
 ### Reach out in case of futher help
 Instagram: https://www.instagram.com/bug_xs/
 
 Thank you for reading!! 🙌🙌
