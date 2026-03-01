# 🖥️ IT Support Home Lab

![Project Banner](./screenshots/banner.png) <!-- Optional: create a simple banner image -->

**A virtual IT lab environment built to simulate real‑world help desk, system administration, and networking tasks.**  
This self‑directed project demonstrates hands‑on technical skills essential for entry‑level IT support and SOC analyst roles.

---

## 📋 Table of Contents
- [Executive Summary](#executive-summary)
- [Phase 1: Virtual Environment Setup](#phase-1-virtual-environment-setup)
- [Phase 2: User Account Management](#phase-2-user-account-management)
- [Phase 3: Software Management & Troubleshooting](#phase-3-software-management--troubleshooting)
- [Phase 4: Network Configuration & Troubleshooting](#phase-4-network-configuration--troubleshooting)
- [Phase 5: Help Desk Ticketing System](#phase-5-help-desk-ticketing-system)
- [Key Metrics & Achievements](#key-metrics--achievements)
- [Technical Skills Acquired](#technical-skills-acquired)
- [Lessons Learned](#lessons-learned)
- [Next Steps](#next-steps)
- [Tools & Technologies Used](#tools--technologies-used)

---

## 🎯 Executive Summary

> *Brief overview of the entire home lab project (2‑3 sentences)*

**Technologies used:** VMware Workstation, Windows 11, Ubuntu Linux, Freshdesk  
**Time period:** `[Start Date]` – `[End Date]`  
**Key focus areas:** Virtualization, user management, troubleshooting, networking, ticketing systems

---

## 🖥️ Phase 1: Virtual Environment Setup

### Objective
Built a virtual IT lab to simulate an enterprise IT environment.

### Implementation
- Installed VMware Workstation Pro
- Deployed Windows 11 virtual machine
- Deployed Ubuntu Linux virtual machine
- Configured system resources and virtual hardware

### Skills Demonstrated
- Virtualization technology
- Operating system installation
- Resource allocation and optimization

### Screenshots
![VMware Dashboard] <img width="2048" height="1482" alt="WindowsDesk" src="https://github.com/user-attachments/assets/6448c427-b397-4a69-a874-4c7c4633d22f" />
*Figure 1: VMware Workstation showing running VMs*

![Windows 11 System Properties](./screenshots/win11-sysprops.png)  
*Figure 2: Windows 11 VM system information*

---

## 👥 Phase 2: User Account Management

### Objective
Practice essential user administration tasks in a Windows environment.

### Tasks Completed
- Created user accounts (`helpdesk1`, `employee1`)
- Performed password resets and changes
- Elevated user privileges (Administrator rights)
- Implemented account lockout and unlock procedures

### Skills Demonstrated
- Active Directory concepts (on a workgroup level)
- User account lifecycle management
- Security best practices
- Windows user management tools

### Screenshots
![User Management Interface](./screenshots/user-management.png)  
*Figure 3: Local Users and Groups showing created accounts*

![Account Properties](./screenshots/account-properties.png)  
*Figure 4: Administrator privileges for helpdesk1*

---

## 📦 Phase 3: Software Management & Troubleshooting

### Objective
Demonstrate application lifecycle management and troubleshooting capabilities.

### Tasks Completed
- Installed multiple applications (Google Chrome, 7‑Zip, Notepad++)
- Verified successful installations
- Performed application removal
- Repaired a “corrupted” application (simulated)
- Resolved application launch failures

### Skills Demonstrated
- Software deployment
- Application troubleshooting
- Windows installer technology
- Problem documentation

### Screenshots
![Programs and Features](./screenshots/programs-features.png)  
*Figure 5: Installed applications list*

![Repair Operation](./screenshots/repair-operation.png)  
*Figure 6: Repairing an application via Control Panel*

---

## 🌐 Phase 4: Network Configuration & Troubleshooting

### Objective
Understand and troubleshoot network connectivity in a virtualized environment.

### Tasks Completed
- Retrieved IP configuration using `ipconfig`
- Identified default gateway and DNS servers
- Tested connectivity using `ping` commands
- Configured NAT and Bridged network modes
- Troubleshot network adapter issues
- Disabled/enabled network adapters

### Skills Demonstrated
- TCP/IP fundamentals
- Network troubleshooting methodology
- Command‑line networking tools
- Virtual network configuration

### Example Issue Resolution
> **Problem:** VM had no internet connectivity in NAT mode  
> **Solution:** Changed network adapter to Bridged mode, restarted VM, verified connectivity with ping test  
> **Outcome:** Full internet connectivity restored

### Screenshots
![ipconfig Output](./screenshots/ipconfig.png)  
*Figure 7: IP configuration before troubleshooting*

![Ping Test](./screenshots/ping-test.png)  
*Figure 8: Successful ping to google.com after fix*

![Network Adapter Settings](./screenshots/network-adapter.png)  
*Figure 9: Changing network adapter mode in VMware*

---

## 🎫 Phase 5: Help Desk Ticketing System

### Objective
Simulate real‑world IT support using a professional ticketing platform.

### Implementation
- Set up Freshdesk help desk portal
- Created organizational structure (departments, contacts)
- Generated 5 realistic support tickets
- Documented troubleshooting steps for each ticket
- Followed ticket resolution workflow
- Closed tickets with detailed resolution notes

### Sample Tickets Resolved
- Password reset request
- Software installation issue
- Network connectivity problem
- Application error (simulated)
- User access request

### Skills Demonstrated
- ITSM (IT Service Management) principles
- Ticket documentation best practices
- Customer communication
- Issue tracking and resolution

### Screenshots
![Freshdesk Dashboard](./screenshots/freshdesk-dashboard.png)  
*Figure 10: Freshdesk portal with ticket list*

![Ticket Example](./screenshots/ticket-example.png)  
*Figure 11: Detailed ticket with resolution notes*

---

## 📊 Key Metrics & Achievements

- **Virtual machines deployed:** 2 (Windows 11, Ubuntu Linux)
- **User accounts managed:** 4+
- **Applications installed/managed:** 3+
- **Network configurations tested:** 2 (NAT, Bridged)
- **Support tickets resolved:** 5
- **Total hands‑on hours:** `[X hours]`

---

## 💡 Technical Skills Acquired

### Operating Systems
- Windows 11 administration
- Ubuntu Linux basics
- Multi‑OS environment management

### Virtualization
- VMware Workstation
- VM configuration & resource management

### Networking
- TCP/IP fundamentals
- Network troubleshooting
- Command‑line tools (ipconfig, ping)

### Support Tools
- Ticketing systems (Freshdesk)
- Documentation practices
- Issue tracking & resolution

---

## 🎓 Lessons Learned

- **Documentation is critical:** Detailed notes made troubleshooting faster and created valuable reference material.
- **Systematic approach works:** Following methodical troubleshooting steps leads to faster problem resolution.
- **Virtualization is powerful:** Ability to create isolated test environments without affecting production systems.
- **Hands‑on practice matters:** Reading about IT concepts vs. actually implementing them are vastly different experiences.

---

## 🚀 Next Steps

- [ ] Implement an Active Directory domain environment
- [ ] Configure Group Policy Objects (GPO)
- [ ] Set up file sharing and permissions
- [ ] Practice PowerShell scripting for automation
- [ ] Explore monitoring and backup solutions
- [ ] Integrate a SIEM tool (like Splunk or Wazuh) for security monitoring

---

## 🛠️ Tools & Technologies Used

- **VMware Workstation Pro** – Virtualization platform
- **Windows 11 Professional** – Guest OS
- **Ubuntu Linux 22.04** – Guest OS
- **Freshdesk** – Help desk ticketing system
- **Command‑line utilities** – ipconfig, ping, etc.
- **Markdown** – Documentation

---

## 📬 Contact & Portfolio

**GitHub:** [Your GitHub Profile URL](https://github.com/yourusername)  
**LinkedIn:** [Your LinkedIn Profile URL](https://linkedin.com/in/yourprofile)  
**Portfolio:** [Your Website/Portfolio URL] *(optional)*

---

*This project documentation demonstrates practical IT support skills and readiness for entry‑level help desk, system administrator, or SOC analyst roles.*
