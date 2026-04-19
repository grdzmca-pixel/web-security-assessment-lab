# 🔐 Web Application Security Assessment & Privilege Escalation Lab

## 📌 Overview
This project demonstrates how insecure session management and weak authentication mechanisms in a web application can lead to privilege escalation and account compromise.

The lab simulates a vulnerable web environment where different security levels can be manipulated, allowing an attacker to gain unauthorized access to higher-privileged accounts.

---

## 🛠️ Lab Environment
- Virtual Machine (Reavers Lab)
- Web application hosted locally
- Firefox browser with Cookie Manager
- Postman for request manipulation

---

## 🎯 Objectives
- Identify security weaknesses in a web application  
- Exploit session and authentication vulnerabilities  
- Perform privilege escalation  
- Simulate brute-force attacks  

---

## 🚨 Vulnerabilities Identified
- Insecure session management  
- Improper access control  
- Weak authentication mechanisms  
- No brute force protection  

---

## ⚔️ Exploitation Techniques

### 🔹 Privilege Escalation via Cookies
User privilege was modified by manipulating cookie values.

### 🔹 Credential Discovery
Application messages revealed valid credentials.

### 🔹 Brute Force Attack
Postman was used to automate login attempts and identify valid credentials.

---

## 📊 Impact
An attacker could gain unauthorized access to privileged accounts and compromise the system.

---

## 🛡️ Security Recommendations
- Secure session handling  
- Implement MFA  
- Enforce server-side validation  
- Add brute force protection  

---

## 🚀 Skills Demonstrated
- Web security testing  
- Privilege escalation  
- Session manipulation  
- Basic attack simulation  
