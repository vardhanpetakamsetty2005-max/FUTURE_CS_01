# FUTURE_CS_01

# Cyber Security Internship Task 1 – Vulnerability Assessment Report

## Task - 1: Vulnerability Assessment Report

This repository contains the deliverables for Task 1 of the Future Interns Cyber Security Internship, which involved performing a read-only vulnerability assessment on a publicly accessible web application.

The objective of this task was to identify potential security weaknesses through passive security analysis without performing any exploitation or disruptive testing.

---

## Target Website

https://demo.testfire.net

This website is intentionally vulnerable and commonly used for security training and vulnerability assessment practice.

---

## Assessment Scope

The assessment focused on identifying common web security issues using non-intrusive techniques.

### The following activities were included:

- Reconnaissance and domain information gathering
- Network port scanning
- Web application vulnerability detection
- HTTP header and cookie security analysis

### The following activities were intentionally excluded:

- Exploitation of vulnerabilities
- Authentication bypass attempts
- Denial-of-Service testing
- Data extraction or modification

---

## Tools Used

The assessment was conducted using the following security tools:

- Parrot OS – Security testing environment
- Nmap – Network scanning and vulnerability scripts
- OWASP ZAP – Web application vulnerability scanning
- Browser Developer Tools – Header and cookie analysis

---

## Key Security Findings

The vulnerability assessment identified several security weaknesses within the web application:

- Missing Content Security Policy (CSP)
- Missing Anti-Clickjacking Header
- Cookie Without HttpOnly Flag
- Cross-Domain (CORS) Misconfiguration
- Secure Pages Include Mixed Content
- Information Disclosure via Server Headers

These issues primarily relate to security misconfigurations and information disclosure, which could increase the attack surface of the application.

---

## Disclaimer

This assessment was conducted strictly for educational and training purposes as part of the Future Interns Cyber Security Internship program.

All testing was performed using passive, non-intrusive techniques without exploiting vulnerabilities.

---

## Author

**Vardhan**

Future Interns Cyber Security Internship – 2026
