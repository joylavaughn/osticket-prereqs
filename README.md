<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1: Create Virtual Machine in Azure/ Create an Azure Virtual Machine Windows 10, 4 vCPUs 
- Item 2: Install / Enable IIS in Windows WITH CGI 
- Item 3: Install osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/ZLPY1dt.png"
</p>
<p>
Azure virtual machines (VMs) can be created through the Azure portal. This method provides a browser-based user interface to create VMs and their associated resources. If you don't have an Azure subscription, create a free account before you begin. Sign in to the Azure portal at https://portal.azure.com
</p>
<br />

<p>
<img src="https://i.imgur.com/XFWmsaN.png" 
</p>
<p>
In Control Panel, click Programs and Features, and then click Turn Windows features on or off. Expand Internet Information Services, expand World Wide Web Services, expand Application Development Features, and then select CGI. Click OK. Click Close. The <cgi> element configures default settings for Common Gateway Interface (CGI) applications for Internet Information Services.
</p>
<br />

<p>
<img src="https://i.imgur.com/5zuTTD2.png"
</p>
<p>
To install osTicket, your web server must have PHP 8.x and MySQL 5.0 (or better) installed. osTicket comes with its own web-based installer to help guide you through the installation process without the frustration. While the installer provides step by step guide during the installation process, it’s important and helpful to have general knowledge about Web servers, PHP and MySQL.
</p>
<br />
