🔐 PBX System Penetration Testing & Password Cracking Lab
📚 Course: Information Security – Spring 2025
Institution: Cleveland State University
Student: Krutika Diwathe
Lab Folder: Lab3

🧠 Project Overview
This project simulates a real-world penetration testing scenario in a controlled lab environment, targeting a vulnerable PBX (Private Branch Exchange) administrative system. The lab demonstrates a full lifecycle attack including system setup, vulnerability analysis, brute-force attacks, and credential cracking.

🛠️ Tools & Technologies Used
Tool	Purpose
Kali Linux	Ethical hacking platform
Hydra	Brute-force password attacker
Cain & Abel	Windows password hash cracking
John the Ripper	Linux password cracking
msfvenom	Payload generation
netcat	Reverse/bind shell listener
Firefox Inspect Element	Credential harvesting

🧪 Key Activities
✅ Part 1: PBX Setup and Web Application Targeting
Deployed FreePBX system and Windows client in sandbox

Configured PBX system admin credentials

Intercepted HTTP login credentials using browser developer tools

✅ Part 2: Password Cracking
Used Cain to extract and crack LM and NTLM hashes from a Windows XP SAM file

Conducted dictionary attacks, brute-force, and rainbow table attacks

✅ Part 3: Malicious Binary Creation
Created bind and reverse shell payloads using msfvenom

Deployed via simulated phishing scenario on HTTP server

Gained unauthorized remote access to victim machine using msfconsole and netcat

✅ Part 4: Linux Hash Cracking
Dumped and cracked Linux /etc/shadow hashes using John the Ripper

📸 Screenshots
![image](https://github.com/user-attachments/assets/58b091e6-0b57-4031-920b-1844c8ff051d)

![image](https://github.com/user-attachments/assets/a3a6e38d-4db6-4cf0-b7fd-5bd4131dad77)

![image](https://github.com/user-attachments/assets/fce9e52c-22e6-48e2-8c46-8f9ce70f6039)

![image](https://github.com/user-attachments/assets/4ed60a49-ca9b-48c1-ace3-f03e540ea6e5)

![image](https://github.com/user-attachments/assets/f8ec30ab-e349-4bcb-a059-0c54761c045c)

![image](https://github.com/user-attachments/assets/32a4cf1e-80cf-40d1-a67d-30796487fff5)


⚠️ Disclaimer
All activities were performed in a controlled lab environment using explicitly permitted systems and virtual machines. This project is strictly for educational and ethical hacking purposes.
