# Security Assessment Findings Report

![image](https://github.com/user-attachments/assets/22da4a10-5b57-4a92-a038-005bec77e5c4)

This repository contains the report for a security assessment conducted by Ath Thahir Muhammad Isa Rahmatullah from **TCM Security**. The assessment was performed on the infrastructure of **Demo Company** and includes details about external penetration testing and identified vulnerabilities.

## Table of Contents

- [Overview](#overview)
- [Assessment Phases](#assessment-phases)
- [Findings](#findings)
- [Severity Ratings](#severity-ratings)
- [Recommendations](#recommendations)
- [Contact Information](#contact-information)

## Overview

The security assessment was performed from **Sep 13th, 2024 to Sep 19th, 2024**. It aimed to evaluate the external security posture of Demo Company’s infrastructure using the NIST SP 800-115 Technical Guide to Information Security Testing and Assessment and the OWASP Testing Guide (v4). 

## Assessment Phases

1. **Planning**: Gathering customer goals and rules of engagement.
2. **Discovery**: Scanning and enumeration to identify vulnerabilities.
3. **Attack**: Exploitation of vulnerabilities to test security.
4. **Reporting**: Documenting the findings and recommendations.

## Findings

![image](https://github.com/user-attachments/assets/5e30ab09-94f7-4c4a-934d-062c54a6c5c9)

![image](https://github.com/user-attachments/assets/965de1fe-1d41-4ec1-983a-af3eee3b16e0)

The following critical vulnerabilities were discovered during the external penetration test:
- **SQL Injection (Blind)**: Allowed attackers to extract sensitive data from the database.
- **Command Injection**: Exploited to gain unauthorized access.
- **File Upload**: Enabled the upload of malicious files that could be executed on the server.

Other vulnerabilities identified include:
- Cross-Site Request Forgery (CSRF)
- XSS Stored and Reflected
- JavaScript vulnerabilities

## Severity Ratings

- **Critical**: Exploitation is straightforward and usually results in system-level compromise.
- **High**: Exploitation is more difficult but can lead to loss of data or elevated privileges.
- **Moderate**: Vulnerabilities exist but are harder to exploit.
- **Low**: Non-exploitable vulnerabilities, but they reduce the attack surface.

## Recommendations

The report provides specific actions to mitigate the vulnerabilities:
- Implement **Multi-Factor Authentication (MFA)** to prevent unauthorized access.
- Restrict **login attempts** to prevent brute force attacks.
- Improve **password policies** to reduce predictability.
- Sanitize all inputs to prevent **SQL injection** and **command injection** attacks.

## Contact Information

For more information or to discuss the findings of this report, please contact:
