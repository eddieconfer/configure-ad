<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- I created a domain controller and vm on Microsoft Azure.
- I connected the vm to the domain controller
- I installed Active Directory on the domain controller.
- I then created ten thousand random users with powershell

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/zgzDMOj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I first created organizational units titled "_ADMINS" and "_EMPLOYEES". I also navigated through the "users" unit.
</p>
<br />

<p>
<img src="https://i.imgur.com/xSMdjK8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
My next step was to connect the vm to the domain.
</p>
<br />

<p>
<img src="https://i.imgur.com/WBlAmeH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The last step was to create ten thousand random users to test logining in to the vm as another user.
</p>
<br />
