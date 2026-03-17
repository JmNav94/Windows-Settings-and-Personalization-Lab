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
<img src="https://i.imgur.com/EfVkEYv.png" height="80%" width="80%" alt="ISO File"/>
<br />
<br />
Set Virtual Machine OS and CPU: <br/>
<img src="https://i.imgur.com/Efxi6wS.png" height="80%" width="80%" alt="OS and CPU"/>
<br />
<br />
Set DCLab to Bridged Network Adapter: <br/>
<img src="https://i.imgur.com/IuaqUcl.png" height="80%" width="80%" alt="Bridged Adapter"/>
<br />
<br />
Set Windows11 to same Bridged Network Adapter: <br/>
<img src="https://i.imgur.com/AwDAJ4K.png" height="80%" width="80%" alt="Bridged Adapter"/>
<br />
<br />
Add Server Roles: <br/>
<img src="https://i.imgur.com/zvnVbWD.png" height="80%" width="80%" alt="Server Roles"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
