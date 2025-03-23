<h1> Practice Creating Active Directory in Windows Server on VMWare Workstation Pro 17</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2> Project Summary</h2>
This was a hands-on project where I walked through setting up Active Directory from scratch on a Windows Server 2022 virtual machine. I installed the OS, promoted the server to a domain controller, created a domain, set up OUs for different regions and departments, and added user accounts and groups. The entire setup is fully functional and can be used as a base for more advanced Active Directory or network administration labs.
<br />

<h2> Active Directory Setup Using Windows Server 2022 in VMware Workstation Pro 17</h2>
For this project, I set up Active Directory on a Windows Server 2022 virtual machine using VMware Workstation Pro 17. The goal was to create a domain environment from scratch, build organizational units (OUs), and set up user accounts and groups — basically a foundational lab for anyone learning how to work with Active Directory.
<br />

<h2>Environments Used </h2>

- <b>VMWare Workstation Pro 17</b>
- <b>Windows Server 2022 ISO (63-bit, evaluation copy</b> 

<h2>Install Walk-through:</h2>

<p align="center">

![image](https://github.com/user-attachments/assets/0caf2a43-bde6-4804-ba69-402febe30b8d) 

Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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

