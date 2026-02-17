# 🛡️ Brute-Force Attacks: Security Testing Project

## 📄 Internship Overview
**Company:** InLighnX Global Pvt. Ltd.
**Role:** Ethical Hacking Intern
**Focus:** Authentication Security & Mitigation Strategies

---

## 🔍 Executive Summary
This project demonstrates simulated brute-force attacks against intentionally vulnerable services (Web Login & SSH) in a controlled lab environment. The goal was to demonstrate how weak authentication can be exploited and to provide actionable mitigation strategies to harden the infrastructure against automated attacks.

### 🛠️ Tools Used
- **Burp Suite (Intruder/Cluster Bomb):** Used for web-form credential testing.
- **Hydra:** Used for automated dictionary attacks against SSH and HTTP POST forms.
- **Kali Linux:** Primary testing environment.

---

## 🎯 Key Objectives Executed
1. **Web-Form Attack:** Simulated credential stuffing on a login form using Burp Suite Intruder to identify valid user sessions via response length analysis.
2. **Automated Brute-Force:** Utilized `hydra` with `http-post-form` mode to iterate through credential lists against web applications.
3. **SSH Security Testing:** Performed password guessing exercises against SSH services to validate weak password policies.

---

## 🛡️ Mitigation Recommendations
Based on the analysis, the following security controls were recommended in the final report:
- **Multi-Factor Authentication (MFA):** Enforce 2FA on all privileged accounts.
- **Account Lockout Policies:** Automatically lock accounts after 3-5 failed attempts.
- **Rate Limiting:** Implement WAF rules to block rapid authentication requests.
- **SSH Hardening:** Disable password-based SSH authentication; enforce key-based auth.

---

## 📂 Project Deliverables
- [View Full Internship Report (PDF)](InlighnX%20Report.pdf)
