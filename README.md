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
![image](https://github.com/user-attachments/assets/23b06a27-87a0-427b-85dd-f6ae3f08621a)

![image](https://github.com/user-attachments/assets/58b3b650-c66b-45bb-a0ea-04aafdc9d396)

![image](https://github.com/user-attachments/assets/9f6e42f7-4dde-4218-b5b8-e6664b4708ae)

![image](https://github.com/user-attachments/assets/b1e10537-1365-462b-ba19-8e2de564c982)

![image](https://github.com/user-attachments/assets/62c6bf1d-a7f5-467e-8be0-28ef2fc462d3)

⚠️ Disclaimer
All activities were performed in a controlled lab environment using explicitly permitted systems and virtual machines. This project is strictly for educational and ethical hacking purposes.
