# Active Directory Fundamentals & Security Lab

This repository contains a **hands-on Active Directory (AD) lab** focused on **enterprise identity management**, **domain administration**, and **security misconfiguration awareness** from a **Blue Team / SOC perspective**.

All activities were performed in a **controlled lab environment** for educational and defensive purposes.

---

## 📁 Contents of This Repository

### 🔹 Active Directory Fundamentals Lab

This lab covers the **core concepts required to understand and manage Active Directory** in an enterprise environment.

**Topics Included:**
- Windows Server 2022 installation using VirtualBox
- Active Directory Domain Services (AD DS) setup
- Domain Controller promotion
- Organizational Units (OU) creation and structure
- User account creation and management
- Domain joining of client systems
- Basic DNS configuration for domain communication

**Files:**
- `AD task.pdf`
- `Learn Active Directory.docx`
- `ad_organizational_structure.png`

---

### 🔹 Active Directory Test Cases

This section documents **test cases used to validate AD functionality and configuration**.

**Focus Areas:**
- User authentication validation
- OU structure verification
- Policy and configuration consistency
- Domain join verification

**File:**
- `AD task Test cases.pdf`

---

### 🔹 Security Misconfiguration & Attacker Walkthrough  
*(Defensive Perspective)*

This lab demonstrates how **common Active Directory misconfigurations** can be abused by attackers and explains **why these weaknesses are dangerous** from a defensive standpoint.

The walkthrough is designed to help **SOC analysts and Blue Team professionals** understand attacker behavior in order to improve **detection, monitoring, and mitigation strategies**.

**Key Concepts Demonstrated:**
- Weak password policies
- Lack of Group Policy hardening
- AS-REP roasting risks
- SMB and shared folder permission abuse
- Lateral movement concepts
- Importance of centralized logging and monitoring

**File:**
- `How Attacker Walkthrough - Exploiting The Lab.pdf`

⚠️ *This walkthrough is strictly educational and conducted only in a lab environment. No production systems were involved.*

---

## 🛠️ Tools & Technologies Used

- Windows Server 2022  
- Active Directory Domain Services (AD DS)  
- VirtualBox  
- Windows DNS  
- Controlled attacker tools (lab only)

---

## 🎯 Learning Objectives

- Understand enterprise Active Directory structure and management
- Identify common AD security misconfigurations
- Learn how attackers exploit identity-based weaknesses
- Build defensive awareness for SOC and Blue Team roles
- Strengthen practical cybersecurity knowledge beyond theory

---

## ⚠️ Disclaimer

All demonstrations in this repository were conducted in **authorized lab environments** for **learning and defensive awareness purposes only**.  
Any misuse of these techniques outside permitted environments is **illegal and unethical**.

---

## 👤 Author

**Devarajan P M**  
Cybersecurity Practitioner | SOC & Active Directory Labs
