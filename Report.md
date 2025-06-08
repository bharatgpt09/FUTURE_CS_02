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
   2. Navigation:

Select: 1) Social-Engineering Attacks

Select: 2) Website Attack Vectors

Select: 3) Credential Harvester Attack Method



3. Site Cloning:

Choose: 2) Site Cloner

Enter IP: Your local IP (e.g., 192.168.x.x)

Target URL: http://example.com/login.php (or another test site)



4. Result:

SET clones the target page and hosts it locally.

Victims entering credentials are logged in plain text.
