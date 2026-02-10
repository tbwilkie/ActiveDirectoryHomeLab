<h1>Active Directory Home Lab</h1>

 ### [YouTube Demonstration](https://youtu.be/yPUKnArW0NQ)

<h2>Description</h2>
Project consists of creating a virtual network in VMWare Workstation that consists of an Active Directory Domain Server with DHCP and remote access for domain connected devices, and a Windows 10 virtual machine. Utilizing PowerShell and a script, I add new users in bulk to active directory with ease. Then I demonstrate how a new user with their account credentials can then access a domian connected device, in this case our Windows 10 virtual machine.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Active Directory</b>
- <b>PowerShell</b> 


<h2>Environments Used </h2>

- <b>Windows Server 2022</b> (21H2)
- <b>Windows 10 Pro</b> (22H2)

<h2>Active Directory walk-through:</h2>

<p align="center">
Diagram providing high-level overview of the virtual network: <br/>
<img src="https://i.imgur.com/1bCn34E.png" height="80%" width="80%" alt="Diagram"/>
<br/>
<br/>
Creating Virtual Machines (Domain Controller and Client): <br/>
<img src="https://i.imgur.com/9meuBoG.png" height="40%" width="40%" alt="Domain Controller"/>  <img src="https://i.imgur.com/kViNEdU.png" height="42%" width="42%" alt="Client"/>
<br />
<br/>
Adding server roles (Active Directory Domain Services, DHCP Server, DNS Server, Remote Access): <br/>
<img src="https://i.imgur.com/uqRqOXD.png" height="80%" width="80%" alt="Server Roles and Features"/>
<br />
<br />
Configuring DC Network Interface Cards (NICs):  <br/>
<img src="https://i.imgur.com/1bCEDn6.png" height="40%" width="40%" alt="Internal NIC"/>  <img src="https://i.imgur.com/VEoyWe2.png" height="40.5%" width="40.5%" alt="External NIC"/>
<br />
<br />
DHCP Scope to create pool of IP addresses for devices connecting to the domain: <br/>
<img src="https://i.imgur.com/m0vtwpS.png" height="80%" width="80%" alt="DHCP Scope"/>
<br />
<br />
DNS Server:  <br/>
<img src="https://i.imgur.com/fhKyfn5.png" height="80%" width="80%" alt="DNS Server"/>
<br />




<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
