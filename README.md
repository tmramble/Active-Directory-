# Active-Directory-
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy Active Directory within Azure Compute](https://www.youtube.com/watch?v=lzHRxxSmQXc)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1 Ensure connectivity between the Client and Domain Controller, and install Active Directory.
- Step 2 Create an Admin and Normal User Account in AD (Active Directory). Then join Client to your domain (mydomain.com)
- Step 3 Setup Remote Desktop for non-administrative users on Client
- Step 4 Create a bunch of users and attempt to log into Client with one of the users.

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://github.com/AndreRobinsonCC/configure-ad/assets/133404844/48106144-f4c1-4e92-875c-82981711652d" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Connectivity between the Client and Domain Controller.

  
<br />

<p>
<img src="https://github.com/AndreRobinsonCC/configure-ad/assets/133404844/f3032d98-3794-4717-b023-0f4bc3e72003" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Client joined to Domain.
</p>
<br />

<p>
<img src="https://github.com/AndreRobinsonCC/configure-ad/assets/133404844/779baa3d-e851-43ad-a4eb-4b6cd6ffa1ff" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Users created and ready to login to Client.
</p>
<br />
