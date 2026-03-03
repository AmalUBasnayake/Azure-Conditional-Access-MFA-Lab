<p align="center">
  <img src="https://img.shields.io/badge/Microsoft-Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white">
  <img src="https://img.shields.io/badge/Security-Conditional%20Access-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/AZ--500-Aligned-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Entra%20ID-Identity-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Zero--Trust-Architecture-orange?style=for-the-badge">
</p>

<h1 align="center">🛡️ Azure Conditional Access – MFA Enforcement Lab</h1>

<p align="center">
  <strong>Zero Trust Identity Protection using Microsoft Entra ID</strong><br>
  Secure, test, and validate Multi-Factor Authentication (MFA) enforcement using Conditional Access.<br><br>
  AZ-500 Aligned • Enterprise Deployment Simulation • Identity Security Focus
</p>

---

## 📌 Executive Overview

This lab demonstrates the design and validation of a **Microsoft Entra ID Conditional Access policy** to enforce **Multi-Factor Authentication (MFA)** for a targeted user.

The implementation follows enterprise best practices by:

- Enforcing least privilege identity controls  
- Deploying policy in **Report-only mode** for safe testing  
- Validating impact before production rollout  
- Aligning with **Zero Trust architecture principles**

---

# 🏗️ Architecture Overview

<p align="center">
  <img src="screenshots/architecture-diagram.png" width="90%" alt="Azure Conditional Access Architecture">
</p>

<p align="center">
  <em>Figure 1 — Conditional Access acting as a Zero Trust enforcement layer between user identity and cloud resources.</em>
</p>

### 🔎 Architecture Flow

1. User initiates sign-in request  
2. Conditional Access policy evaluates conditions  
3. Grant Control triggers **Require MFA**  
4. MFA challenge is presented  
5. Access granted only after successful verification  
6. Sign-in event recorded in Entra ID logs  

Conditional Access functions as a **policy decision engine** protecting cloud identities from unauthorized access.

---

# 🎯 Lab Objectives

- Target a specific internal user  
- Enforce **Require Multi-Factor Authentication**  
- Deploy policy using **Report-only mode**  
- Validate configuration and status  
- Simulate enterprise-safe rollout strategy  

---

# 🛡️ Core Identity Security Concepts

- User-based targeting  
- Grant Controls (Require MFA)  
- Report-only safe deployment  
- Policy state management  
- Zero Trust identity enforcement  

---

# 📸 Implementation Evidence

---

## 1️⃣ Policy Creation – Specific User Targeting

<p align="center">
  <img src="screenshots/1-new-policy-specific-user.png" width="85%">
</p>

<p align="center">
  <em>Figure 2 — Creating Conditional Access policy targeting a specific internal user.</em>
</p>

---

## 2️⃣ Policy Configuration – Require MFA

<p align="center">
  <img src="screenshots/2-policy-overview.png" width="85%">
</p>

<p align="center">
  <em>Figure 3 — Configuring Grant Control to require Multi-Factor Authentication.</em>
</p>

---

## 3️⃣ Policy Status Verification

<p align="center">
  <img src="screenshots/3-policies-list-on.png" width="85%">
</p>

<p align="center">
  <em>Figure 4 — Policy enabled and visible in Conditional Access overview.</em>
</p>

---

## 4️⃣ Report-Only Mode Deployment

<p align="center">
  <img src="screenshots/4-report-only.png" width="85%">
</p>

<p align="center">
  <em>Figure 5 — Report-only mode enabled for safe evaluation before enforcement.</em>
</p>

---

# 🚀 Implementation Steps Summary

1. Created Conditional Access policy: **Enforce-MFA-Udayanga**  
2. Selected specific user under Assignments  
3. Configured Grant Control → Require MFA  
4. Set policy state to **Report-only**  
5. Enabled policy  
6. Verified status in dashboard  

---

# 🔐 Security Impact Analysis

### Without Conditional Access + MFA

- High credential compromise risk  
- Single-factor authentication weakness  
- Increased likelihood of account takeover  

### With Conditional Access + MFA

- Strong identity verification  
- Reduced attack surface  
- Zero Trust enforcement  
- Improved compliance posture  

MFA remains one of the most effective controls against identity-based attacks.

---

# 🎓 AZ-500 Certification Alignment

Supports:

- Secure identity & access  
- Configure Conditional Access  
- Implement MFA controls  
- Monitor identity security posture  

---

# 🧠 Key Takeaways

- Conditional Access is a policy-driven enforcement engine  
- Report-only mode enables safe enterprise deployment  
- Targeted rollout minimizes operational risk  
- Identity is the modern security perimeter  

---

# 👨‍💻 Author

**Amal Basnayake**  
Cloud Security • Identity Governance • Zero Trust Architecture  

🔗 LinkedIn: https://www.linkedin.com/in/amal-udayanga-basnayake  
🔗 GitHub: https://github.com/AmalUBasnayake  

---

<p align="center">
⭐ If this lab supported your Azure Security journey, consider starring the repository.
</p>
