# 🖥️ IT Support Home Lab

<img width="1800" height="600" alt="IT Support Home Lab Banner" src="https://github.com/user-attachments/assets/4572df44-3ee7-4fcd-aee6-02d2bf0c2d69" />

---

## Overview

This project is a self-built virtual IT lab environment designed to simulate real-world help desk and IT support scenarios. Using VMware Workstation Pro, I deployed and configured Windows 11 and Ubuntu Linux virtual machines, then worked through a structured series of IT support tasks covering user account management, software troubleshooting, network diagnostics, and help desk ticketing.

The goal was to build demonstrable, hands-on experience with the tools, workflows, and problem-solving approaches used daily in IT Support, Service Desk, and Junior Infrastructure roles — and to document that process in a way that clearly communicates technical competence to recruiters and hiring managers.

---

## Goals

- Deploy and configure virtual machines using industry-standard virtualisation software
- Practise Windows user account administration, including account creation, privilege escalation, and lockout procedures
- Install, verify, repair, and remove software applications as part of application lifecycle management
- Diagnose and resolve network connectivity issues using command-line tools
- Set up and use a professional help desk ticketing system (Freshdesk) to simulate real support workflows
- Document all work clearly to demonstrate both technical and communication skills

---

## Technologies & Tools Used

| Tool / Technology | Purpose |
|---|---|
| VMware Workstation Pro | Virtualisation platform — hosting and managing VMs |
| Windows 11 Professional | Primary guest OS for all IT support tasks |
| Ubuntu Linux 22.04 | Secondary guest OS deployment |
| Freshdesk | Cloud-based help desk ticketing system |
| Windows Command Prompt | Network diagnostics (ipconfig, ping) |
| Local Users and Groups (lusrmgr.msc) | Windows user account management |
| Control Panel / Programs & Features | Software installation and removal |
| Markdown | Project documentation |

---

## What I Did

The project was structured across five phases, each targeting a different area of IT support competency.

**Phase 1 — Virtual Environment Setup:** I installed VMware Workstation Pro and deployed both a Windows 11 Professional and an Ubuntu Linux 22.04 virtual machine. I configured virtual hardware including RAM, CPU cores, and network adapters to create a stable lab environment.

**Phase 2 — User Account Management:** Working inside the Windows 11 VM, I used the Local Users and Groups tool to create user accounts (helpdesk1 and employee1), set and reset passwords, assign Administrator privileges, and simulate account lockout and unlock procedures.

**Phase 3 — Software Management & Troubleshooting:** I installed multiple applications including Google Chrome, Notepad++, and 7-Zip to practise software deployment. I then verified installations, performed removals, and simulated a repair scenario through Control Panel — replicating a common real-world support request.

**Phase 4 — Network Configuration & Troubleshooting:** I used ipconfig to retrieve IP configuration details (IPv4 address, subnet mask, default gateway, DNS) and used ping to test both local (127.0.0.1) and external (google.com) connectivity. I also configured and switched between NAT and Bridged network adapter modes in VMware to resolve a simulated internet connectivity issue.

**Phase 5 — Help Desk Ticketing System:** I set up a Freshdesk portal and created five realistic support tickets representing common IT issues. Each ticket was assigned a priority, linked to a contact, and worked through a resolution workflow — including documenting the troubleshooting steps and closing the ticket with resolution notes.

---

## Screenshots & Walkthrough

### Phase 1 — Virtual Environment Setup

**Screenshot 1: VMware Workstation with Windows 11 VM Running**

<img width="2048" height="1482" alt="VMware Workstation showing Windows 11 VM" src="https://github.com/user-attachments/assets/6448c427-b397-4a69-a874-4c7c4633d22f" />

VMware Workstation Pro with the Windows 11 x64 virtual machine powered on and displaying the desktop. The VM library panel on the left shows the machine listed under "My Computer". This confirms the virtualisation environment was successfully set up and the guest OS is operational.

**What this shows:** The lab environment was functional before any tasks began. Being able to deploy and run a VM in VMware Workstation demonstrates familiarity with hypervisor technology — a core skill for IT support and infrastructure roles.

---

**Screenshot 2: Windows 11 VM System Information**

<img width="1228" height="889" alt="Windows 11 System Properties" src="https://github.com/user-attachments/assets/94347404-32b1-4edf-b549-e376c58624cf" />

Windows 11 system properties confirming the guest OS version and hardware configuration of the virtual machine.

**What this shows:** Verifying system information is a standard first step in any support engagement. Knowing where to check OS version, processor, and RAM is essential for troubleshooting compatibility issues and fulfilling software requirements.

---

### Phase 2 — User Account Management

**Screenshot 3: Local Users and Groups — Accounts Created**

<img width="1155" height="1032" alt="Local Users and Groups showing created accounts" src="https://github.com/user-attachments/assets/9b6ddc78-f207-4c34-b033-adcc9e4be210" />

The Local Users and Groups management console (lusrmgr.msc) showing the Users container within Computer Management. The panel confirms user accounts have been created inside the Windows 11 environment.

**What this shows:** User account creation and management is one of the most common tasks on a service desk. This demonstrates the ability to navigate Windows administrative tools and manage user lifecycles — directly relevant to onboarding, offboarding, and access management requests.

---

**Screenshot 4: Administrator Privileges Assigned to helpdesk1**

<img width="1155" height="1032" alt="Administrator privileges for helpdesk1" src="https://github.com/user-attachments/assets/b36cee4e-08e6-444f-8a63-769249b7564c" />

Account properties showing elevated privileges assigned to the helpdesk1 account, demonstrating user privilege management within a Windows environment.

**What this shows:** Privilege escalation and role-based access control are critical IT security concepts. Assigning the correct level of access — and knowing when not to over-provision — is a key responsibility in any IT support role.

---

### Phase 3 — Software Management & Troubleshooting

**Screenshot 5: Installed Applications Visible on Desktop and Taskbar**

<img width="1155" height="1032" alt="Installed applications on Windows 11" src="https://github.com/user-attachments/assets/c7cf709a-ca16-455f-9759-6f323d6ef73f" />

The Windows 11 desktop and taskbar showing Google Chrome, Notepad++, and 7-Zip successfully installed and accessible. All three applications were installed, verified, and confirmed to be working correctly.

**What this shows:** Software deployment is a routine IT support task. This screenshot demonstrates the ability to install and verify applications — a skill directly applicable to both manual and scripted software provisioning on end-user devices.

---

**Screenshot 6: Software Installation Verified — Multiple Applications Open**

<img width="1155" height="1032" alt="Multiple installed applications running" src="https://github.com/user-attachments/assets/be3a2eca-4ed9-4c64-b190-bbfe9ee4d267" />

Google Chrome, Notepad++, and 7-Zip all open simultaneously inside the Windows 11 VM, confirming successful installation and functionality of each application.

**What this shows:** Verifying that software works correctly after installation — not just that it appears in the programs list — is good practice and demonstrates thoroughness in a support context.

---

**Screenshot 7: Application Repair via Control Panel**

<img width="1155" height="1032" alt="Repairing application via Control Panel" src="https://github.com/user-attachments/assets/ac9038c6-b9e0-4c17-acf2-1d88442f2e10" />

The Programs and Features panel in Control Panel, used to access the repair function for a simulated corrupted application — replicating a real-world support scenario where an end user reports that a program is crashing or not loading correctly.

**What this shows:** Application repair through Windows installer is a standard first step before uninstalling and reinstalling software. This demonstrates a methodical troubleshooting approach rather than immediately escalating or reinstalling.

---

**Screenshot 8: Application Removal Confirmed**

<img width="1155" height="1032" alt="Application uninstalled via Control Panel" src="https://github.com/user-attachments/assets/613f1f0a-1e23-4810-9aeb-018a3bf6c994" />

Control Panel showing the updated installed applications list after an application was uninstalled — confirming the removal was completed successfully.

**What this shows:** Clean application removal is important for managing disk space, resolving software conflicts, and maintaining a healthy system. This is a frequent task in enterprise IT environments.

---

### Phase 4 — Network Configuration & Troubleshooting

**Screenshot 9: ipconfig Output — IP Configuration Retrieved**

<img width="1155" height="1032" alt="ipconfig output showing IP configuration" src="https://github.com/user-attachments/assets/daf60f57-d749-471c-84c5-06042b7f3c20" />

Command Prompt showing the output of ipconfig — displaying the Ethernet adapter's IPv4 address (192.168.1.18), subnet mask (255.255.255.0), and default gateway (192.168.1.254). The IPv6 address has been redacted for privacy.

**What this shows:** Reading and interpreting ipconfig output is a foundational network troubleshooting skill. IP address, subnet mask, and default gateway are the first things to check when diagnosing a connectivity issue — and this is one of the first things a help desk technician is taught.

---

**Screenshot 10: Ping Test — Local Loopback Successful**

<img width="1155" height="1032" alt="Ping loopback test successful" src="https://github.com/user-attachments/assets/f631847f-3c60-40c0-b614-f279278fe215" />

Command Prompt showing a successful ping 127.0.0.1 (local loopback) with 4 packets sent and 4 received — confirming the TCP/IP stack is functioning correctly on the VM.

**What this shows:** Pinging the loopback address is the first step in network troubleshooting — it confirms the NIC and TCP/IP stack are working before testing external connectivity. This demonstrates a structured, methodical diagnostic approach.

---

**Screenshot 11: Ping Test — External Connectivity Confirmed**

<img width="1155" height="1032" alt="Ping google.com successful" src="https://github.com/user-attachments/assets/689756c3-d853-4e8b-a48a-f30396e439f7" />

Command Prompt showing a successful ping google.com — 4 packets sent, 4 received, 0% packet loss — confirming full internet connectivity from the Windows 11 VM after the network adapter was reconfigured.

**What this shows:** A successful external ping confirms DNS resolution is working and that there is a valid route to the internet. This was the final step in verifying the fix for the simulated connectivity issue.

---

**Screenshot 12: Network Adapter Settings in VMware**

<img width="1365" height="1032" alt="VMware network adapter settings" src="https://github.com/user-attachments/assets/9de6cb0f-5267-4e9a-9b52-269523889b15" />

VMware Workstation network adapter configuration panel, used to switch between NAT mode and Bridged mode to resolve a simulated internet connectivity issue on the VM.

**What this shows:** Understanding the difference between NAT and Bridged networking in a virtualised environment is valuable for anyone supporting VMs in a business setting. Configuring virtual network adapters is a practical skill that translates directly to enterprise virtualisation platforms like VMware vSphere and Hyper-V.

---

### Phase 5 — Help Desk Ticketing System

**Screenshot 13: Freshdesk Portal — Ticket Queue**

<img width="1920" height="1032" alt="Freshdesk ticket list" src="https://github.com/user-attachments/assets/28a58e46-525e-4d99-83f1-3b6df81d7859" />

The Freshdesk help desk portal showing the ticket queue with five active support tickets: David Miller ("Printer not printing"), Sarah Jin ("Need Notepad++ installed"), Kevin Brown ("Computer running very slow"), Maria Lopez ("No internet connection"), and John Carter ("Cannot log into computer").

**What this shows:** Setting up and using a ticketing system is central to professional IT support work. This demonstrates the ability to manage a queue, prioritise tickets, and work within an ITSM (IT Service Management) framework — skills that are expected in every service desk role.

---

**Screenshot 14: Freshdesk — Open Ticket Being Worked**

<img width="1920" height="1032" alt="Freshdesk ticket detail view" src="https://github.com/user-attachments/assets/9144dfd0-2cbb-43fc-8bb8-1d6f9c616a91" />

A detailed view of an open ticket: "Cannot log into computer" raised by John Carter. The ticket shows the user description ("I forgot my Windows password and cannot log into my computer"), the assigned agent (Richard Ochei), priority (High), and status (Open). The reply/note interface is visible, ready for the technician to document the resolution steps.

**What this shows:** Working through a ticket — reading the issue, setting priority, assigning it to an agent, and documenting the response — mirrors the exact workflow used in real service desk environments. This demonstrates both technical and communication competency.

---

## Skills Demonstrated

| Skill Area | Specific Skills |
|---|---|
| Virtualisation | Deploying and managing VMs in VMware Workstation Pro |
| Operating Systems | Windows 11 administration, navigation, and configuration |
| User Management | Account creation, password resets, privilege assignment, lockout/unlock |
| Software Management | Installation, verification, repair, and removal of applications |
| Network Troubleshooting | ipconfig, ping, NAT vs Bridged networking, adapter configuration |
| Help Desk & ITSM | Ticket creation, prioritisation, assignment, and resolution in Freshdesk |
| Documentation | Technical write-up, structured phase-based project documentation |
| Problem Solving | Diagnosing and resolving simulated real-world IT issues |

---

## Challenges & Fixes

**Challenge 1 — VM Internet Connectivity (NAT Mode)**

When the Windows 11 VM was first configured in NAT mode, it had no internet connectivity despite showing a valid IP address from ipconfig. Pinging the default gateway succeeded, but external connections failed.

Fix: Switched the VMware network adapter from NAT to Bridged mode, which allowed the VM to obtain an IP address directly from the host network's router. After restarting the network adapter and re-running ping google.com, full external connectivity was confirmed with 0% packet loss.

Learning: Understanding the difference between NAT (the VM sits behind the host's IP) and Bridged (the VM acts as a separate device on the network) is essential knowledge for anyone supporting virtualised systems.

---

**Challenge 2 — Understanding Privilege Levels for User Accounts**

When setting up the helpdesk1 account, it was important to understand which group membership was appropriate. Adding a user to the Administrators group grants full system access, which is not always appropriate in a real environment.

Learning: In a production environment, the principle of least privilege should be applied. Helpdesk accounts should only have the access they need. This exercise highlighted the importance of role-based access control (RBAC) in enterprise environments.

---

**Challenge 3 — Repairing vs Reinstalling an Application**

When simulating a corrupted application scenario, the first instinct might be to uninstall and reinstall immediately. However, using the repair function through Programs and Features is the correct first step — it is faster, preserves user settings, and avoids unnecessary disruption.

Learning: A structured troubleshooting methodology (try the least invasive fix first) is more efficient and less disruptive than jumping straight to reinstallation or escalation.

---

## What I Learned

Working through this lab reinforced several important technical and professional lessons.

Virtualisation is a foundational skill in modern IT — understanding how to deploy, configure, and troubleshoot VMs is relevant to cloud, on-premises, and hybrid environments alike. The ipconfig and ping commands are often the fastest way to diagnose a network issue, and knowing how to interpret their output confidently is something every IT technician should be able to do. User account management — even at the local workgroup level — teaches the underlying concepts of Active Directory and identity management that appear in enterprise environments at scale.

Using Freshdesk showed how structured ticketing workflows improve communication and accountability in a support team. Even self-managing a queue of five tickets highlighted the importance of prioritisation and clear documentation. This project also reinforced that good documentation is a skill in itself: being able to explain what you did, why you did it, and what you learned is as valuable as the technical work.

---

## Future Improvements

- **Active Directory Lab:** Promote a Windows Server VM to a Domain Controller and join the Windows 11 VM to the domain — simulating a real enterprise environment with centralised user management.
- **Group Policy:** Apply GPOs (Group Policy Objects) to manage security settings, desktop restrictions, and software deployment across domain-joined machines.
- **Remote Desktop & Remote Support:** Configure and use RDP (Remote Desktop Protocol) to simulate remote support sessions — a core skill for service desk technicians.
- **Ticketing Automation:** Explore Freshdesk automation rules, SLA policies, and canned responses to simulate a more realistic high-volume support environment.
- **Linux Administration:** Expand the Ubuntu VM usage to practise command-line administration, user management, and basic networking on Linux — relevant for roles supporting mixed OS environments.
- **Monitoring & Alerting:** Introduce a basic monitoring tool (such as Zabbix or Nagios) to practise infrastructure visibility and alerting — relevant to junior infrastructure and NOC roles.

---

## Tools & Technologies Used

- **VMware Workstation Pro** — Virtualisation platform
- **Windows 11 Professional** — Primary guest OS
- **Ubuntu Linux 22.04** — Secondary guest OS
- **Freshdesk** — Help desk ticketing system
- **Command-line utilities** — ipconfig, ping
- **Local Users and Groups** — Windows user management console
- **Control Panel / Programs & Features** — Software management
- **Markdown** — Project documentation

---

*This project demonstrates practical, hands-on IT support skills directly applicable to entry-level help desk, service desk, and junior infrastructure roles.*
