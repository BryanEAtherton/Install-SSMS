# Security Project 1


<p align="center">
<img src="https://i.imgur.com/fDfy3qo.jpeg"/>
</p>

<h1>Install SQL Server Management System (SSMS)</h1>
Here we will install and set up SSMS on the Windows VM. This will provide another application for our honeypot to attract attacks. 

<h2>Environments and Technologies Used</h2>

- Windows 10 
- SQL Server Management System (SSMS)
- Windows Registry Editor
- Command Prompt


<h2></h2>
 

<h2>Install SSMS</h2>

<br />


<p>
1.  In the Windows VM Google search and download SSMS.
</p>
<p>
<img src="https://i.imgur.com/Ewq5BUP.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
  
<p>
2. Select the free download and open the file.
</p>
<p>
<img src="https://i.imgur.com/PovXdim.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

<p>
 3. Select Install, then Restart and allow the VM to restart.  You will need to RDP back into the VM when complete.
</p>
<p>
<img src="https://i.imgur.com/5kMc5bx.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/DsHYHDc.png" height="50%" width="40%" alt="Disk Sanitization Steps"/>
</p>

[Click here to view instructions on how to create an Azure VM and access it using Remote Desktop](https://github.com/BryanEAtherton/Azure-Virtual-Machine)

<br />

<p>   
4. RDP back into the Windows VM and open Windows Registry Editor.
</p>
<p>
<img src="https://i.imgur.com/2UpL70E.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

<p>
5. In Registry Editor, navigate to HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\EventLog\Security
</p>
<p>
<img src="https://i.imgur.com/ZMDyWIa.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p> 

<p>
6. Right Click on Security and select Permissions. 
</p>
<p>
<img src="https://i.imgur.com/P0xkDc2.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

<p>
7. Select Add... from the permissions window, type Network Service in the open field, click the Check Names box, then click Ok.
</p>
<p>
<img src="https://i.imgur.com/LdrGliY.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

<p>
8. Give Network Services Full control. highlight Network Services, check the Full Control box, click Apply, then click Ok.
</p>
<p>
<img src="https://i.imgur.com/AipzmId.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

<p>
9. We will need to configure SSMS using the command shown in the slide here. Highlight and copy this command line. These instructions are listed on the website shown in slide 2.
</p>
<p>
<img src="https://i.imgur.com/C7f87w2.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

<p>
10. Open the Windows VM Command Prompt and select Run as Administrator. Then pasete the command from the previous slide and press Enter.
</p>
<p>
<img src="https://i.imgur.com/MNrtrxg.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ACqnphb.png" height="50%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p>
11. If done correclty, a message will appear confirming the command was succesfully executed. Close Command Prompt.
</p>
<p>
<img src="https://i.imgur.com/kR8Ndq5.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

<p>
12. Open the SSMS App.
</p>
<p>
<img src="https://i.imgur.com/TbWDN2p.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>

<p> 
13. From the Authenticatin field select SQL Server Authenntification. Then login using the password we set on step 13 of the Install and configure SQL Server section.
</p>
<p>
<img src="https://i.imgur.com/V2u3zzX.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/p6P0cea.png" height="50%" width="40%" alt="Disk Sanitization Steps"/>
</p>

[Click here to view the install SQL Server section](https://github.com/BryanEAtherton/Install-SQL-Server/tree/main)
</p>

<p> 
14. Right-click the Windows VM and select Properties. Then select Security, check Both failed and successful logins, then click Ok. 
</p>
<p>
<img src="https://i.imgur.com/7lYUAoM.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/qmGOguA.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>

<p> 
15. Right-click the Windows VM and select Restart. Then verify the restart.
</p>
<p>
<img src="https://i.imgur.com/smRg7X3.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/nVW7zUy.png" height="50%" width="40%" alt="Disk Sanitization Steps"/>
</p>



[Click here to return to the Security Project 1 Homepage](https://github.com/BryanEAtherton/Security-Project-1)

<br />





