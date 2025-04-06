# Desktop Operating System Case Project  
### Case Project: Implementing Windows 11 on VMware with Enterprise Configuration Tasks  

## Overview  
This is a **hands-on case project** completed as part of the **Desktop Operating Systems** course at **George Brown College**. The project involved setting up a Windows 11 virtual machine in VMware Workstation and performing a series of system administration tasks to simulate a real-world enterprise IT environment.

## Objective  
The goal of this project was to develop foundational skills in configuring, managing, and securing a Windows 11 operating system in a virtualized environment. Tasks included VM setup, user provisioning, local policy enforcement, storage configuration, PowerShell scripting, and security settings.

## Scenario  
As a system administrator, I was assigned to prepare and configure a Windows 11 environment for an internal company workstation. Using VMware Workstation, I installed and customized the operating system to meet the organization’s IT policies, security standards, and user access requirements.

## Tasks Covered  

### **Task 1: Installing Windows 11 in VMware Workstation**  
- Installed Windows 11 on VMware Workstation  
- Named the virtual machine: `MonilParmar-101486688`  

### **Task 2: Creating a Provisioning Package**  
- Used Windows Configuration Designer to create a provisioning package  
- Created a local administrator account:  
  - Username: `MonilAdmin`  
  - Password: `P@ssw0rd`  

### **Task 3: Configuring Local Security Policies**  
- Enabled User Account Control (UAC) prompt  
- Configured screen to dim when UAC appears  

### **Task 4: Customizing Start Menu and Taskbar**  
- Pinned Microsoft News app to Start Menu  
- Exported customized Taskbar layout using PowerShell  

### **Task 5: Static IP Configuration with PowerShell**  
- Assigned static IP: `192.168.168.101/24`  
- Removed secondary IP address to avoid conflicts  

### **Task 6: Creating a Storage Space**  
- Created two virtual hard disks (VHDs)  
- Configured a 2-way mirror storage space for data redundancy  

### **Task 7: Setting Folder Permissions**  
- Created a folder named `File Share`  
- Set NTFS permissions:  
  - Authenticated Users → Read-only  
  - Administrators → Full Control  

### **Task 8: Sharing Folder with Network Permissions**  
- Shared the `File Share` folder  
- Network share permissions configured:  
  - Everyone → Read  
  - Administrators → Full Control  

### **Task 9: Installing Microsoft Whiteboard**  
- Installed Microsoft Whiteboard from the Microsoft Store  

### **Task 10: Configuring File History**  
- Enabled File History on the storage space  
- Configured to retain data backups for 30 days  

---

## Tools and Technologies Used  
- **VMware Workstation**  
- **Windows 11 Operating System**  
- **Windows Configuration Designer**  
- **PowerShell**  
- **Local Group Policy Editor (gpedit.msc)**  
- **Microsoft Store**  
- **File Explorer and Storage Spaces Utility**  
- **Taskbar Configuration via XML and PowerShell**  
- **File History Backup Settings**

---

## Notes  
- All configuration steps were tested and verified on a Windows 11 virtual machine.  
- Screenshots were captured for each completed task to support documentation and grading.  
- This project reflects core competencies in desktop OS administration aligned with industry standards.

---

## Contact  
If you have any questions or would like to know more about this project, feel free to reach out at:  
📧 **monilparmar27@gmail.com**  
