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



<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/cvTKt9C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once i created my virtual machine " windows server 2022" i log into remote desktop with my public Ip adress for windows server. Once everything loads up, go to server manager and on the dashboard select "server Roles" and click active directory domain services, add features and go with the installation process.
</p>
<br />

<p>
<img src="https://i.imgur.com/wCDdY49.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When active directory is installed, now im going to promote my Virtual machine as a Domain controller, So to do that i im going to setup a new Forest as my "Mydomain.com"
</p>
<br />

<p>
<img src="https://i.imgur.com/gcNBPiM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once everything is setup, What i will do now is remote desktop in my other virtual machine "windows 10 pro" and will join the domain "windows server 2022" that i created. 
</p>
<br />
