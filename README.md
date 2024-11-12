# Active Directory Homelab: Part 1 🖥️

In this repository, I demonstrate my skills in setting up and configuring an Active Directory (AD) environment. The project focuses on establishing a functional Active Directory network to manage users, resources, and security within a Windows Server environment.

## Overview 🌍

In **Part 1** of this Active Directory series, I cover the following steps:

- Setting up a **Windows Server VM** and configuring Active Directory Domain Services (AD DS).
- Creating a new **Active Directory domain** and promoting the server to a **Domain Controller**.
- Joining a **Windows client VM** to the newly created domain.
- Creating **Organizational Units (OUs)** and **user accounts** in Active Directory.
- Testing domain functionality by logging into a Windows VM using Active Directory credentials.

This project demonstrates my ability to build and manage an Active Directory environment, laying the groundwork for future enhancements and automation.

## Table of Contents 📚

1. [Project Setup](#project-setup)
2. [Steps Completed](#steps-completed)
3. [Future Work](#future-work)

## Project Setup 🛠️

### Requirements 📝

To follow along with this project, you will need:

- A **Windows Server** VM to install and configure Active Directory Domain Services (AD DS).
- A **Windows client VM** to join to the Active Directory domain.
- Virtualization software (e.g., **VMware**, **Hyper-V**, or **VirtualBox**).
- Basic understanding of **Windows Server** and **Active Directory** concepts.

### Installation 🚀

1. **Set up a Windows Server VM**.
2. **Install Active Directory Domain Services (AD DS)** and promote the server to a Domain Controller.
3. **Create a new Active Directory domain**.
4. **Join a Windows client VM** to the newly created domain.
5. **Create Organizational Units (OUs)** and user accounts in Active Directory.

## Steps Completed ✅

1. **Windows Server VM Setup:**  
   - Installed and configured **Active Directory Domain Services (AD DS)** on a Windows Server VM.

2. **Domain Configuration:**  
   - Created a new **domain** and named it **MiguelK.local**.
   - Promoted the server to a **Domain Controller**.

3. **Windows VM Domain Join:**  
   - Joined a **Windows client VM** to the domain.
   - Configured **DNS settings** to ensure proper domain connectivity.

4. **Active Directory Management:**  
   - Created **Organizational Units (OUs)** to organize domain objects.
   - Added users to these OUs and tested domain login functionality.

## Future Work 🔮

In the next parts of this series, I will extend the Active Directory environment by:

- **Automating the creation of user accounts** and other objects using **PowerShell scripts**.
- **Restricting access and assigning privileges** between different user groups to demonstrate access control.
- **Enhancing security** by implementing **Group Policies** for stronger network and user management.
- **Integrating a Splunk server** with the Windows Server environment for **log management** and **security monitoring**.

---
