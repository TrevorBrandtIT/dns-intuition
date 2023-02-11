<p align="center">
<img src="https://i.imgur.com/CtGfsq8.png" alt="DNS Graphic"/>
</p>

<h1>Building Intuition with DNS</h1>
This tutorial covers experimenting with and gaining a better understanding of DNS.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- A-Record Exercise. Creating and pinging an A-Record.
- Local DNS Cache Exercise. Flushing and pinging.
- CNAME Record Exercise. Creating and pinging a CNAME Record.


<h2>Deployment and Configuration Steps</h2>

<p>
Welcome back to the second part in our AD tutorials. In this one, I'll assume that you have already finished the previous tutorial and that you've created all of the accounts using the PowerShell script.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log into both VMs as Jane Doe. From Client-1, try and ping "mainframe", notice that it doesn't work. Now nslookup mainframe from Client-1, it will tell you that mainframe doesn't exist. Now go to Server Manager in DC-1. Click on Tools -> DNS -> Forward Lookup Zones -> Right click -> New Host. Name it "mainframe" and set the IP Address to DC-1's IP. Now go back to Client-1 and try to ping mainframe again. Notice that it works. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
Continued <a href="https://github.com/TrevorBrandtIT/file-shares-and-permissions">here.</a> Thank you for following along!
</p>
<br />
