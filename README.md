# osticket-prereqs
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

- Create an Azure Virtual Machine and login with Remote Desktop
- Download the osTicket instalation files and unzip it onto your desktop, 
- Install and enable osTicket-instalation files onto your remote desktop
- open IIS as an admin  
- continue setting up osTicket int the browser

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Using the username and password, I login to the azure virtual machine with remote desktop. Within the VM osTicket download the osTicket-Instalation-Files.zip and unzip it onto my desktop.(Before you install ont eh browser Install and enabel IIS in Windows WITH CGI)
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From the OTNF folder install PHP Manager, rewrite Module, and MySQL5.5.62(launche Configuration WIzard after install with the username and password).Open IIS as an Admin and Register PHP from within IIS install osTicket into the browser.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On the IIS default enable extention (imap,intl, and opache) rename ost-config.php to sampleconfig. Assign permissions(disable inheritance and give new permissions to all) Continue to set up osTicket int the browser with the mySQL database.
</p>
<br />
