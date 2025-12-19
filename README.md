# Active Directory Password Reset & Account Unlock

**Area of Focus** Windows / Identity / Core Help Desk

---

## 📌 Project Overview

This project demonstrates **entry-level help desk Active Directory account recovery tasks** performed in a controlled Azure lab environment. These tasks represent some of the **most common identity-related issues** handled by technical support and junior systems administrators, including password expirations and account lockouts.

The objective of this project is to show a clear, secure, and repeatable workflow for restoring user access while following best practices.

---

## 🧠 Key Skills Demonstrated

* Identity verification concepts
* Active Directory user account recovery
* Password security enforcement
* Account lockout remediation
* Basic troubleshooting workflow
* Windows Server administration fundamentals

---

## 🛠️ Environments & Technologies Used

* Microsoft Azure (Sandbox Environment)
* Windows Server 2022
* Active Directory Domain Services (AD DS)
* Active Directory Users and Computers (ADUC)
* Remote Desktop Protocol (RDP)

---

## 💻 Operating Systems

* Windows Server 2022 (Domain Controller)
* Windows 10 (Client context for user access validation)

---

## ✅ Tasks Performed

* Created and configured a Windows Server virtual machine in Azure
* Installed and promoted Active Directory Domain Services
* Created a test user account
* Identified account access issues (password expiration / lockout)
* Reset a user password
* Unlocked a locked user account
* Enforced password change at next logon
* Verified account status after recovery

---

## 🔄 Account Recovery Workflow

1. Identify the user account experiencing access issues
2. Verify account status (locked or password expired)
3. Reset the user password as required
4. Unlock the account if locked
5. Enforce password change at next logon
6. Confirm the user can successfully sign in

This workflow mirrors real-world help desk procedures and emphasizes security and accountability.

---

## 📸 Screenshots & Explanations

### Azure Virtual Machine Deployment

<img width="975" height="510" alt="image" src="https://github.com/user-attachments/assets/8efc48a9-5ded-4f06-b406-39ee2399fba8" />
<img width="975" height="526" alt="image" src="https://github.com/user-attachments/assets/820e2d17-df2d-4ca9-aa0c-fe7c97425bed" />


*Shows successful deployment of the Windows Server VM used as the Domain Controller.*

### Active Directory Users and Computers (ADUC)
<img width="975" height="681" alt="image" src="https://github.com/user-attachments/assets/ce5d3182-725b-4cd5-8750-f32c39461028" />

*Demonstrates access to the ADUC console where user accounts are managed.*

### Reset Password Dialog
<img width="975" height="530" alt="image" src="https://github.com/user-attachments/assets/3cc0221e-be22-47c0-b7b9-e690a453b4cc" />

*Illustrates the password reset process for a user account within Active Directory.*

### Account Properties – Security Enforcement
<img width="975" height="605" alt="image" src="https://github.com/user-attachments/assets/44b34018-2c5a-46bf-801d-e985681c0023" />

*Shows the account settings used to unlock the account and require a password change at next logon.*

---

## 🎯 Outcome

The user account was successfully recovered using secure Active Directory practices. The account was unlocked, the password reset, and the user was required to create a new password at next logon, ensuring continued security compliance.

---

## 📚 What This Project Demonstrates to Employers

* Practical Active Directory experience
* Understanding of identity and access management fundamentals
* Ability to follow and document troubleshooting workflows
* Readiness for Help Desk, Desktop Support, or Junior Systems Administrator roles


