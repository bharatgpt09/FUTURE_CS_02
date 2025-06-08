# FUTURE_CS_02
Social-Engineer Toolkit credential harvesting demonstration
# 🎯 Credential Harvesting Demo with Social-Engineer Toolkit (SET)

This repository documents a credential harvesting demonstration using the *Social-Engineer Toolkit (SET)* on Kali Linux. It showcases how attackers can clone a web login page and capture user credentials for educational and awareness purposes.

---

## 🔍 Overview

- *Tool Used*: SET (Social-Engineer Toolkit)
- *Attack Vector*: Credential Harvester via Website Cloning
- *Environment*: Kali Linux (local lab setup)
- *Target*: Cloned login page of a sample website

---

## ⚙ Features Demonstrated

- Cloning legitimate login portals
- Hosting phishing pages locally
- Capturing submitted credentials
- Logging and viewing harvested data

---

## 🧪 Steps Performed

1. *Launched SET* and selected:
   - 1) Social-Engineering Attacks
   - 2) Website Attack Vectors
   - 3) Credential Harvester Attack Method
   - 2) Site Cloner

2. *Provided Local IP* for hosting and *target URL* for cloning.

3. *Victim accessed* the malicious login page and entered credentials.

4. *Credentials captured* and stored in SET's log directory.

---

## 📷 Screenshots

| Terminal | Victim Login | Harvested Data |
|----------|--------------|----------------|
| ![SET Running](screenshots/harvester_run.png) | ![Victim Login](screenshots/browser_login.png) | ![Captured Credentials](screenshots/captured_creds.png) |

---

## 📁 Files Included

- report.md – Full write-up of the attack steps and outcomes.
- README.md – This file.
- screenshots/ – Folder containing demo images.
- logs/ (optional) – Sanitized logs of the attack (if applicable).

---

## ⚠ Disclaimer

> This project is intended *solely for educational and ethical hacking purposes* in a controlled lab environment. Unauthorized use of these techniques is *illegal* and *strictly discouraged*. Always conduct security testing with proper authorization.

---

## 📚 References

- [SET GitHub](https://github.com/trustedsec/social-engineer-toolkit)
- [Kali Linux Tools](https://tools.kali.org/information-gathering/set)
