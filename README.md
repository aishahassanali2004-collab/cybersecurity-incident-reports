# Cybersecurity Incident Report: Website Defacement & Malware Injection

## Section 1: Attack Description & Network Protocols
* **Attack Type:** Brute Force Attack on Administrative Account
* **Protocols Affected:** HTTP / HTTPS (Port 80 / 443) and TCP connection attempts.

## Section 2: Incident Documentation
The attacker executed a brute force attack to gain access to the web host. After guessing the administrative credentials, they embedded a malicious JavaScript function into the website's source code. This script prompted visitors to download malware via a fake download link. The attacker then changed the admin password, locking out the host owner.

## Section 3: Remediation Recommendations
1. **Account Lockout Policy:** Automatically lock accounts after 3-5 failed login attempts to prevent automated brute-force guessing.
2. **Multi-Factor Authentication (MFA):** Force all administrative users to verify their identity through an app or SMS to stop unauthorized access even if credentials are stolen.
