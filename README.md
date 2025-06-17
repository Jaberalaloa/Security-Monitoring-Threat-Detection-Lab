# Cybersecurity Labs – PreprLabs Portfolio

This repository showcases a series of hands-on cybersecurity projects completed through PreprLabs, a Government of Ontario-backed learning platform supported by AWS, Cisco, and Mozilla. Each lab focuses on a core area of cybersecurity, including penetration testing, server and web application hardening, SIEM-based monitoring, and threat detection.

---

## Projects Overview

### 1. Penetration Testing Challenge – SSL Vulnerability Scan
**Tools:** Kali Linux, Nikto  
**Objective:** Perform a penetration test on an SSL-enabled website.  
**Highlights:**
- Scanned `fantasy.premierleague.com` to identify missing security headers.
- Discovered missing `X-Frame-Options` and `X-Content-Type-Options`, exposing the site to clickjacking and MIME-sniffing attacks.
- Analyzed HTTP response headers and documented vulnerabilities with actionable recommendations.


---

### 2. Server Security Lab – Pre & Post SSL Hardening
**Tools:** Kali Linux, Nikto  
**Objective:** Set up a basic website, enforce SSL, and evaluate security improvements.  
**Highlights:**
- Identified issues such as missing `Strict-Transport-Security` and improper content encoding.
- Compared vulnerability reports before and after SSL enforcement.
- Provided detailed analysis and mitigation strategies based on scan output.


---

### 3. Cloud-Based WordPress Security – Monitoring & Testing
**Tools:** AWS EC2, WPScan, Nikto, CloudWatch  
**Objective:** Deploy WordPress on AWS, configure cloud monitoring, and conduct penetration testing.  
**Highlights:**
- Detected missing security headers, WP-Cron risks, and legacy header leaks.
- Set up CloudWatch and alarms for resource monitoring.
- Recommended WordPress security best practices and plugin management.


---

### 4. Web Application Firewall & 2FA Hardening
**Tools:** Wordfence, WPScan, Nikto, AWS EC2  
**Objective:** Harden WordPress login and server security with 2FA and firewall.  
**Highlights:**
- Mitigated vulnerabilities by configuring 2FA, HttpOnly cookies, and removing exposed `.ini` and log files.
- Fixed improper redirects, and integrated Wordfence firewall for real-time protection.
- Addressed previous scan findings and introduced new layers of defense.


---

## Skills Demonstrated

- Penetration Testing & Web Vulnerability Scanning
- Cloud Infrastructure (AWS EC2, CloudWatch)
- WordPress Security Configuration
- SIEM Concepts and Threat Mitigation
- Secure Server Configuration & HTTP Header Management
- Report Writing & Incident Documentation

---

## Notes

All penetration testing activities were performed in ethical environments on personal or publicly testable web assets, following responsible disclosure principles and PreprLabs guidelines.

---

## Contact

Feel free to reach out via GitHub or LinkedIn for collaboration opportunities or portfolio review.
