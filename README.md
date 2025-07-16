# FUTURE_CS_01 – Web Application Security Testing

🔐 **Internship Task 1 – Future Interns (Cybersecurity Track)**  
This repository contains the vulnerability assessment of **OWASP Juice Shop** done as part of the cybersecurity internship with Future Interns.

## 🔧 Tools Used
- OWASP Juice Shop (online)
- Burp Suite (Community Edition)
- Chrome Developer Tools

## 🛡️ Vulnerabilities Identified
1. **Broken Authentication** – Admin login bypass using SQL injection
2. **Reflected XSS** – Alert triggered via search input
3. **Sensitive File Disclosure** – Access to `acquisitions.md` via FTP
4. **Insecure Session Tokens** – No HttpOnly flag on auth cookie

## 📝 OWASP Top 10 Mapping
- A01 – Broken Access Control
- A03 – Injection (XSS)
- A06 – Security Misconfiguration
- A07 – Identification & Authentication Failures


**Status:** ✅ Task 1 Completed  
**Submitted by:** B Haritheertha

