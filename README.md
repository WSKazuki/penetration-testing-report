# Penetration Testing Project – VAPT Report

This repository contains the final **Vulnerability Assessment and Penetration Testing (VAPT)** project report.

- **Target Application:** Docker container `gabrielec/ptexam3`  
- **Environment:** Isolated Docker lab environment  
- **Tools Used:** Nmap, Gobuster, cURL, Netcat, SQL exploitation techniques  

## 📄 Report
The full project report is available here:  
## 🔑 Key Findings
- Command Injection → Reverse Shell access  
- Cross-Site Scripting (XSS)  
- SQL Injection (Login Bypass)  
- Database exposure through hardcoded credentials  
- Privilege escalation vectors (SUID binaries, cron jobs)  

## 🛠 Recommendations
- Sanitize and validate all inputs  
- Use prepared statements (parameterized queries)  
- Remove hardcoded credentials  
- Enforce least privilege for DB and OS accounts  
- Keep systems patched and audit regularly
