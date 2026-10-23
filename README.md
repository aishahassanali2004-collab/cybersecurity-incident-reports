# Cybersecurity Incident Report: Website Defacement & Malware Injection

## Section 1: Attack Description & Network Protocols
* **Attack Type:** Brute Force Attack on Administrative Account
* **Protocols Affected:** HTTP / HTTPS (Port 80 / 443) and TCP connection attempts.

## Section 2: Incident Documentation
The attacker executed a brute force attack to gain access to the web host. After guessing the administrative credentials, they embedded a malicious JavaScript function into the website's source code. This script prompted visitors to download malware via a fake download link. The attacker then changed the admin password, locking out the host owner.

## Section 3: Remediation Recommendations
1. **Account Lockout Policy:** Automatically lock accounts after 3-5 failed login attempts to prevent automated brute-force guessing.
2. **Multi-Factor Authentication (MFA):** Force all administrative u---

## Project 3: OS Hardening & Security Risk Assessment

### Part 1: Selected Hardening Tools & Methods
1. **Patch Updates:** Regularly deploying software patches to update programs and operating systems, addressing known vulnerabilities before they can be exploited.
2. **Baseline Configuration:** Establishing a documented, secure set of specifications for the system to serve as a consistent foundation for all future builds, releases, and updates.
3. **Multi-Factor Authentication (MFA):** Implementing a robust security measure that requires users to verify their identity through two or more separate credentials before gaining system access.

### Part 2: Recommendation Analysis
Implementing OS hardening tools drastically reduces the attack surface by closing security gaps and fixing vulnerabilities within the system. Enforcing Multi-Factor Authentication (MFA) ensures that even if passwords are compromised, unauthorized actors cannot access corporate accounts. Together with secure baseline configurations, these methods provide a defense-in-depth approach that protects organizational data and secures future system builds.
sers to verify their identity through an app or SMS to stop unauthorized access even if credentials are stolen.
                                                                                                                                                                                                                                                               
