# -python-security-projects
password lockout system and a login log analyzer. Built while moving from banking into cybersecurity and fraud risk.
# Python Cybersecurity Project

A security automation and analysis toolkit featuring a **Password Lockout System** and a **Login Log Analyzer**, built during a professional transition from banking into cybersecurity and fraud risk.

## 🚀 Features

### 1. Password Lockout System
* **Brute-Force Mitigation:** Tracks consecutive failed authentication attempts for user accounts.
* **Automated Lockout:** Temporarily locks accounts or enforces a cooldown period after reaching the maximum threshold of failed attempts.
* **Audit Logging:** Records security events and timestamped lockout triggers for compliance and monitoring.

### 2. Login Log Analyzer
* **Log Parsing:** Processes system and authentication logs to extract user login patterns, IP addresses, and timestamps.
* **Anomaly Detection:** Identifies suspicious activities such as credential stuffing indicators, high-frequency failed attempts, and unusual access hours.
* **Reporting:** Generates clear summary metrics for security analysts to review.

---

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Core Modules:** `logging`, `datetime`, `re` (Regular Expressions), file handling.

---

## 📂 Repository Structure
```text
├── login_log_analyzer.py      # Parses and analyzes authentication logs
├── password_lockout.py        # Manages user authentication and lockout states
└── README.md                  # Project documentation
