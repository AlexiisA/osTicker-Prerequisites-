<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

Enable Information Services (IIS)
- Web Platform Installer
- Install my SQL
- Install C++ redistributable
- Configure Permissions & install osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.io/DYssBNB_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a Resource Group
</p>
<br />

<p>
<img src="https://i.imgur.io/lsArgQU_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a Windows 10 Virtual Machine (VM) with 2-4 Virtual CPUs When creating the VM, allow it to create a new Virtual Network (Vnet):
</p>
<br />

<p>
<img src="https://i.imgur.io/5Fis4yG_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Connect to your Virtual Machine with Remote Desktop
</p>
<br />
<p>
<img src="https://i.imgur.io/3qWltwZ_d.webp?maxwidth=640&shape=thumb&fidelity=medium"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
<p>
<img src="https://i.imgur.io/F0d05iK_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to the search bar at the bottom and look up Control Panel.
Click on "uninstall a program" under "Programs".
On the left sidebar, click on "Turn Windows Features on and off".
Scroll down until you find "Internet Information Services". Check the box to enable it.
Click on [+] next to IIS and it should open up other files under it. Click the [+] on "World Wide Web Services" and then click the [+] on Application Development Features. Scroll down until you find CGI and then check the box next to it.
Press OK and it should start installing IIS & CGI.
</p>
<br />
<p>
<img src="https://i.imgur.io/5Fis4yG_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install Web Platform Installer
</p>
<br />
<p>
<img src="https://i.imgur.io/kblbd5R_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
