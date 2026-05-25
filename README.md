AWS Break & Fix Lab

Always check in security group your ip for secureshell

since we used dynamic ip it will constantly change
match the ip 
or can set anywhere (0.0.0.0) for educational purpose 

1. NETWORK problem (can’t reach server)

symptom: timeout

meaning: traffic blocked before reaching EC2

→ check:

Security Group

IP address

instance running

2. SERVICE problem (server reachable, but not working)

symptom: connection refused / 502 / site down

meaning: server is reachable, but nginx/app is dead

→ check:

systemctl status nginx

port listening

3. ACCESS problem (login issue)

symptom: permission denied

meaning: SSH reached server, but authentication failed

→ check:

key file (.pem)

username

permissions

📌 Overview
This project demonstrates troubleshooting skills on an AWS EC2 instance by intentionally breaking and fixing common infrastructure issues.



🎯 Goal
Learn how to diagnose and fix:
- Service failures (Nginx)
- Network access issues (Security Groups)
- SSH connectivity problems



🧱 Skills Practiced
- Linux service management
- AWS Security Groups
- SSH troubleshooting
- Basic network debugging
- System recovery mindset

🧪 Labs Included
- Lab 1: Nginx service failure and recovery
- Lab 2: HTTP port blocked via Security Group
- Lab 3: SSH access failure simulation


🧠 Key Learning Outcome
Understanding how cloud infrastructure fails and how to systematically diagnose and fix issues.
