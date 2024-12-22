# Home-Lab-Running-Active-Directory



## Objective

The objective of building the Home-Lab-Running-Active-Directory project is to create a controlled environment where you can learn and practice Active Directory (AD) management and network administration skills. This involves setting up a virtual machine to host Active Directory, configuring domain controllers, and using PowerShell scripts for tasks like user management. It's a hands-on way to gain practical experience in AD setup, domain management, and network functionalities


### Skills Learned

- Active Directory Setup: Learn how to install and configure Active Directory Domain Services.
- User and Group Management: Practice creating and managing user accounts, groups, and organizational units.
- Group Policy Management: Develop skills in creating and applying Group Policies to control user and computer settings.
- DNS Configuration: Understand how to set up and manage DNS within an Active Directory environment.
- Security Best Practices: Implement security measures like account lockout policies, password policies, and role-based access control.
- Network Configuration: Gain experience in configuring network settings and managing network services.
- PowerShell Scripting: Automate administrative tasks using PowerShell scripts.
- Replication Management: Learn how to manage and troubleshoot Active Directory replication.
- Backup and Recovery: Develop skills in backing up and restoring Active Directory data.
- Troubleshooting: Enhance your problem-solving skills by diagnosing and resolving common Active Directory issues.

### Tools Used
- VirtualBox
- Windows Server
- Windows 10/11
- Nmap
- PowerShell

## Steps
<p align="center">
1.download windows 10 ISO: <br/>
<br />
<img src="1.download windows 10 ISO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
2.Download windows Server 2019 ISO: <br/>
<br />
<img src="2.Download windows Server 2019 ISO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
3.Download VirtualBox extension pack: <br/>
<br />
<img src="3.Download VirtualBox extension pack.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
4.Install extension pack: <br/>
<br />
<img src="4.Install extension pack.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
5.config windows server VM: <br/>
<br />
<img src="5.config windows server VM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
6.config Network adapters: <br/>
<br />
<img src="6.config Network adapters.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
7.installing windows server 2019 ISO: <br/>
<br />
<img src="7.installing windows server 2019 ISO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
8.installing guest additions: <br/>
<br />
<img src="8.installing guest additions.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
9.configuring network adpaters: <br/>
<br />
<img src="9.configuring network adpaters.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
10.Renaming PC: <br/>
<br />
<img src="10.Renaming PC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
11.Assigning internal network IP Address: <br/>
<br />
<img src="11.Assigning internal network IP Address.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
12.Installing Active directory domain services: <br/>
<br />
<img src="12.Installing Active directory domain services.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
13.post deployment configuration: <br/>
<br />
<img src="13.post deployment configuration.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
14.verifying prerequisite : <br/>
<br />
<img src="14.verifying prerequisite .png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
15.creating dedicated domain account: <br/>
<br />
<img src="15.creating dedicated domain account.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
16.creating new user: <br/>
<br />
<img src="16.creating new user.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
17.promoting new user to admin: <br/>
<br />
<img src="17.promoting new user to admin.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
18.installing RAS NAT on domain server : <br/>
<br />
<img src="18.installing RAS NAT on domain server .png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
19.routing and remote access: <br/>
<br />
<img src="19.routing and remote access.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
20.installing DHCP: <br/>
<br />
<img src="20.installing DHCP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
21.DHCP SCOPE: <br/>
<br />
<img src="21.DHCP SCOPE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
22.DHCP IP Address range: <br/>
<br />
<img src="22.DHCP IP Address range.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
23.DHCP Lease duration: <br/>
<br />
<img src="23.DHCP Lease duration.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
24.checking if scope was successfully created: <br/>
<br />
<img src="24.checking if scope was successfully created.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
25.turning off security configuration for smoother browsing: <br/>
<br />
<img src="25.turning off security configuration for smoother browsing.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
26.create account script: <br/>
<br />
<img src="26.create account script.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
27.running poweshell as administrator: <br/>
<br />
<img src="27.running poweshell as administrator.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
28.setting execution policy to unrestricted: <br/>
<br />
<img src="28.setting execution policy to unrestricted.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
29.changing powershell directory to locate script: <br/>
<br />
<img src="29.changing powershell directory to locate script.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
30.powershell creating users: <br/>
<br />
<img src="30.powershell creating users.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
31.confirming that 1000 users were created: <br/>
<br />
<img src="31.confirming that 1000 users were created.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
32.Creating client using windows 10 iso: <br/>
<br />
<img src="32.Creating client using windows 10 iso.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
33.installing windows VM <br/>
<br />
<img src="33.installing windows VM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
34.Assigning host default gateway: <br/>
<br />
<img src="34.Assigning host default gateway.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
35.changing PC name and joining domain: <br/>
<br />
<img src="35.changing PC name and joining domain.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />


