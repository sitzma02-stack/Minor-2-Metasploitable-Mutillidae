# Minor 2 Project: Metasploitable & Mutillidae II

## Student Details
- Name: Siddhima Sharma
- Project: Minor 2
- Topic: Metasploitable Setup & Mutillidae II Fix
- Platform: VMware (Windows)

---

## Project Objective
The objective of this project is to:
- Install and configure Metasploitable
- Create a new user inside Metasploitable
- Fix the Mutillidae II database error
- Verify the application running successfully in browser
- Understand vulnerable web applications and security basics

---

## Tools & Technologies Used
- Metasploitable 2
- VMware Workstation
- Apache Web Server
- MySQL Database
- Mutillidae II (OWASP)
- Linux Terminal
- Web Browser

---

## Step 1: Metasploitable Setup
Metasploitable virtual machine was installed and configured using VMware on Windows OS.
After booting, all services such as Apache and MySQL started successfully.

📸 Screenshot: Metasploitable boot screen

---

## Step 2: Login to Metasploitable
Default credentials were used to login:
- Username: msfadmin
- Password: msfadmin

📸 Screenshot: Login screen

---

## Step 3: User Creation
A new user named **siddhima** was created using the following command:

```bash
sudo adduser siddhima
