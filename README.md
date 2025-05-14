# Security Project 1


<p align="center">
<img src="https://i.imgur.com/fDfy3qo.jpeg"/>
</p>

<h1>Install SQL Server Management System (SSMS)</h1>
Here we will install and set up SSMS on the Windows VM. This will provide another application for our honeypot to attract attacks. 

<h2>Environments and Technologies Used</h2>

- Windows 10 
- SQL Server Management System (SSMS)


<h2></h2>
 

<h2>Install SSMS</h2>

<br />


<p>
1.  In Azure Create 2 VMs - 1 Windows & 1 Linux.
</p>
<img src="https://i.imgur.com/QSn0enR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

  
[Click here to view instructions on how to create an Azure VM and access it using Remote Desktop](https://github.com/BryanEAtherton/Azure-Virtual-Machine)
</p>
<br />

<p>
2. Navigate to the Linux VM NSG and disable the Firewall by deleting the SSH inbound rule. 
<p>
<img src="https://i.imgur.com/CCWUnuQ.png" height="50%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/E7EQyPj.png" height="50%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p>
 3. Create a new rule to allow all traffic into the VM.
<p>
<img src="https://i.imgur.com/3NPTV98.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/8iTnSg6.png" height="50%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p>   
4. Repeat the process in step 2 for the Windows VM by deleting the RDP inbound rule.
<p>
<img src="https://i.imgur.com/vYFfEl4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
5. Repeat step 3 for the Windows VM and create a new rule to allow all traffic into the VM.
<p>
<img src="https://i.imgur.com/EoHjiaZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>

[Click here to return to the Security Project 1 Homepage](https://github.com/BryanEAtherton/Security-Project-1)
</p>





