<p align="center">
<img img width="260" alt="image"  src="https://github.com/user-attachments/assets/528ec9aa-73b1-4f3e-ac90-eb661fec85ea" alt="Windows Imaging and Setup"/>
</p>

<h1><b>Windows-Imaging-and-Setup</b></h1>

<h2>Overview</h2>

This repository provides a step-by-step guide to installing Windows OS, configuring environments, and managing imaging workflows for a newly provisioned device using VirtualBox. While designed for general Windows setup, optional sections explore enterprise-level provisioning, including Windows Deployment Services (WDS), PowerShell scripting for automation, and Active Directory (AD) integration for those interested.

For **cloud-based VM deployment via Azure**, visit my related repository here: (https://github.com/victoriadeery/azure-computing-and-networking)

---

<h2>Environments, Technologies, and Features Used</h2>

- **VirtualBox** – Virtual Machine Environment for Windows Setup 
- **Windows Deployment Services (WDS)** – Enterprise Imaging & Provisioning  
- **Macrium Reflect / Clonezilla** – Imaging Tools for Backup & Restoration  
- **PowerShell Scripting** – Automation for OS Configuration
- **Active Directory (AD) & Group Policy (GPO)** – IT Management & Security  

---

<h2>Operating Systems Used</h2>

- **Windows 10/11 (64-bit)**  
- **Windows Server (for WDS Deployment - Optional)**

---

<h2>List of Prerequisites</h2>

- **VirtualBox or Azure** installed on your system
- **Windows ISO file** from [Microsoft](https://www.microsoft.com/en-us/software-download/windows10)
- **Imaging tools** (Macrium Reflect, Clonezilla, or WDS - optional)
- **PowerShell** (for automation tasks and configuration scripting)  
- **Network Configuration** (DHCP, DNS, Active Directory - optional)  

 ---
 
<h2>Tutorial</h2>

**1. Install VirtualBox**  
- Download [VirtualBox](https://www.virtualbox.org/) for Windows  
- Follow the installation steps and open the application  

**2. Download Windows ISO**  
- Get a **Windows installation file** from [Microsoft](https://www.microsoft.com/en-us/software-download/windows10)  
- Save it in an easily accessible location 

**3. Create a Virtual Machine**  
- Open VirtualBox and **set up a Windows VM**  
- Allocate **RAM, disk space**, and attach the ISO  

**4. Install & Configure Windows**  
- Follow the setup steps to **install Windows**  
- Add **drivers, updates, and perform initial configurations**  

**5. Practice Imaging & Enterprise Setup**  
- **Install imaging tools** like **Clonezilla, Macrium Reflect, or WDS**  
- **Create & restore system images to simulate real IT workflows**  
- **Configure networking (DHCP, DNS, IP settings)** for enterprise setups - **Set up Active Directory (optional)** for corporate provisioning  

---

<h2>Next Steps</h2>

- Deploy Windows using WDS for automated enterprise setups  
- Explore PowerShell scripting for system automation  
- Experiment with Active Directory & Group Policies for IT security 
