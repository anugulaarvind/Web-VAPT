# Web Application Vulnerability Assessment and Penetration Testing

## 📌 Project Overview

This project demonstrates a **Web Application Vulnerability Assessment and Penetration Testing (VAPT)** exercise performed against **OWASP Juice Shop** in an isolated local lab environment.

The assessment follows an **OWASP-based methodology** and focuses on understanding web application security through manual testing, HTTP traffic analysis, security testing tools, evidence collection, and professional reporting.

> ⚠️ **Disclaimer:** This project was performed only against a deliberately vulnerable application in a local, authorized lab environment. No unauthorized or public systems were tested.

---

## 🎯 Objectives

* Perform application mapping and reconnaissance
* Analyze HTTP requests and responses
* Test authentication and authorization controls
* Review input validation
* Test for common web application security weaknesses
* Analyze security headers
* Use automated scanners and manually verify results
* Document security findings with evidence
* Provide remediation recommendations
* Perform retesting where applicable

---

## 🧪 Target

| Item         | Details                 |
| ------------ | ----------------------- |
| Application  | OWASP Juice Shop        |
| Target URL   | `http://127.0.0.1:3000` |
| Environment  | Local Isolated Lab      |
| Tester       | Arvind                  |
| Testing Date | September 2026          |

---

## 🛠️ Tools Used

* **Burp Suite** — HTTP traffic interception and request analysis
* **OWASP ZAP** — Automated web security testing
* **Browser** — Application interaction and testing
* **cURL** — HTTP header and response analysis
* **Docker** — Local application deployment

---

## 🔍 Testing Methodology

The assessment followed this general workflow:

```text
Application Mapping
       ↓
HTTP Traffic Analysis
       ↓
Authentication Testing
       ↓
Authorization Testing
       ↓
Input Validation Testing
       ↓
Security Header Review
       ↓
Automated Scanning
       ↓
Manual Verification
       ↓
Evidence Collection
       ↓
Risk Assessment
       ↓
Remediation Recommendations
       ↓
Retesting
```

---

## 📋 Areas Tested

* Application mapping
* Authentication
* Authorization / Access Control
* Input validation
* Cross-Site Scripting (XSS)
* SQL Injection testing
* Session security
* Security headers
* Error handling
* Business logic
* Automated scanner results
* Manual verification

---

## 📂 Project Structure

```text
Project-1-Web/
│
├── README.md
├── .gitignore
│
├── screenshots/
│   ├── burp-http-history.png
│   ├── burp-request-response.png
│   ├── zap-results.png
│   ├── security-headers.png
│   └── testing-evidence.png
│
├── evidence/
│
├── report/
│   └── Project-1-Report.txt
│
└── notes/
    └── testing-notes.md
```

---

## 📸 Evidence

Screenshots and supporting evidence will be added to the `screenshots/` directory.



## 🔐 Safety and Authorization

This project was conducted in an **isolated local lab environment** using OWASP Juice Shop, a deliberately vulnerable training application.

Testing was limited to systems for which authorization was available.

**No real customer data, passwords, API keys, session cookies, or unauthorized target information should be uploaded to this repository.**

---

## 📚 Learning Outcomes

Through this project, I practiced:

* Web application security testing
* HTTP request/response analysis
* Burp Suite
* OWASP ZAP
* OWASP testing methodology
* Vulnerability verification
* Security evidence collection
* Risk explanation
* Remediation documentation
* Professional VAPT reporting

---

## 👤 Author

**Arvind**

B.Tech — Cyber Security

Aspiring Cybersecurity / VAPT Professional
