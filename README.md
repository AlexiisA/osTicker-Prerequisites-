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

- Enable Information Services (IIS)
- Create A Resource Group & Virtual Machine
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

</p>
<br />

<p>
<img src="https://i.imgur.io/lsArgQU_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
 <p>
 Create a Windows 10 Virtual Machine (VM) with 2-4 Virtual CPUs When creating the VM, allow it to create a new Virtual Network (Vnet):
<img src="https://i.imgur.io/5Fis4yG_d.webp?maxwidth=640&shape=thumb&fidelity=medium" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Connect to your Virtual Machine with Remote Desktop
<br />
<p>
<img src="https://i.imgur.io/Kj8TsfY_d.webp?maxwidth=640&shape=thumb&fidelity=medium"height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
<p>
<img src="https://i.imgur.io/F0d05iK_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Install / Enable IIS in Windows
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
<img src="https://i.imgur.io/bzGoRLf_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install Web Platform Installer
</p>
<br />
<p>
<img src="https://i.imgur.io/kblbd5R_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.io/qv0B30o_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.io/jPOvCjI_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and install MySQL_5.5.62. The MySQL configuration wizard will pop up after installing the program.
 
 - Click on "Standard Configuration", then keep clicking "Next" until it asks you to create a password. Create a password that you can remember because we will need it! (The username is root and then your password!)
 - Click "Next" and then "Execute". It will take a bit to install everything but once it's done, click "Finish".
</p>
<br />
<img src="https://i.imgur.io/M2Q9IAu_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download VC_redist.x86
</p>
<br />

<p>
<img src="https://i.imgur.io/VPK0b4C_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<p>
<img src="https://i.imgur.com/6XVTT9h_d.webp?maxwidth=1520&fidelity=grand" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  </p>
<br />

<p>
<img src="https://i.imgur.io/w8i84Fu_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click “Install Now!
 Install osTicket v1.15.8</h3>
<br />
<p>
  Download osTicket (download from within lab files: link).
</p>
<p>
	Extract and copy the “upload” folder INTO c:\inetpub\wwwroot:
 <p>
	Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”:
	
</p>
	<img src="https://i.imgur.io/TiyrO0L_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="75%" width="100%" alt="PHP Manager"/>
 </p>
<p>
Reload IIS (Open IIS, Stop and Start the server)
 </p>
<p>
Go to sites -> Default -> osTicket:
	<img src="https://i.imgur.io/iDUGdSF_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="75%" width="100%" alt="PHP Manager"/>
<p>
  </p>
<br />
On the right, click “Browse *:80”:
<p>
<img src="https://i.imgur.io/3MjNnA8_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Enable Extensions in IIS: Note that some extensions are not enabled
 </p>
<p>
Go back to IIS, sites -> Default -> osTicket.

Double-click PHP Manager:
<p>
<img src="https://i.imgur.io/DlWrpWo_d.webp?maxwidth=640&shape=thumb&fidelity=medium" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Refresh the osTicket site in your browser, observe the changes
 
 </p>
<p>



  
