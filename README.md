<h1>Active Directory HomeLab</h1>


<h2>Description</h2>
Project consists of building an Active Directory Server and Client virtual environment from scratch. Virtual Box was used to create a Domain Controller Virtual Machine (DCLab) and a Client Virtual Machine (Win11) to work together through Active Directory. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Oracle Virtualbox</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2022</b> 
- <b>Windows 11</b> 

<h2>Program walk-through:</h2>

<p align="center">
Download Windows Server 2022 and Windows 11 from ISO file: <br/>
<img src="https://i.imgur.com/lZQShRE.png" height="80%" width="80%" alt="ISO File"/>
<br />
<br />
Set Virtual Machine OS and CPU: <br/>
<img src="https://i.imgur.com/bwbvrBq.png" height="80%" width="80%" alt="OS and CPU"/>
<br />
<br />
Set DCLab to Bridged Network Adapter: <br/>
<img src="https://i.imgur.com/CtuiE3f.png" height="80%" width="80%" alt="Bridged Adapter"/>
<br />
<br />
Set Windows11 to same Bridged Network Adapter: <br/>
<img src="https://i.imgur.com/xIWrhlX.png" height="80%" width="80%" alt="Bridged Adapter"/>
<br />
<br />
Install Server OS from ISO download file: <br/>
<img src="https://i.imgur.com/7F0CNcG.png" height="80%" width="80%" alt="OS and CPU"/>
<br />
<br />
Install Windows 11 OS from ISO download file: <br/>
<img src="https://i.imgur.com/0BmaXPJ.png" height="80%" width="80%" alt="OS and CPU"/>
<br />
<br />
Rename Domain Controller PC Name: <br/>
<img src="https://i.imgur.com/1xi2ay5.png" height="80%" width="80%" alt="OS and CPU"/>
<br />
<br />
Add Server Roles: <br/>
<img src="https://i.imgur.com/zvnVbWD.png" height="80%" width="80%" alt="Server Roles"/>
<br />
<br />
Create Root Domain Name:  <br/>
<img src="https://i.imgur.com/Mspi5JX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Help Desk user on Active Directory and Promote to Admin User:  <br/>
<img src="https://i.imgur.com/1obl7iO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
