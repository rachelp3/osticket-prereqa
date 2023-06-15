<p align="center">
<img src=" https://imgur.com/a/v5AAVwY " alt="osTicket logo"/>
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

- Remote Desktop Connection
- IIS installation
- Files Installation
- PHP Manager
- osTicket Launch

<h2>Installation Steps</h2>

<p>
<img <a href="https://imgur.com/CiNBH09"><img src="https://i.imgur.com/CiNBH09.png" title="source: imgur.com" /></a>
</p>
<p>
Create a virtual resource group and a virtual machine to begin and copy the public IP address for the virtual machine. Next, open the Remote Desktop Connection application to log into the virtual machine.
</p>
<br />

<p>
<img <a href="https://imgur.com/uA6gACg"><img src="https://i.imgur.com/uA6gACg.png" title="source: imgur.com" /></a>
</p>
<p>
On the virtual machine, IIS will need to be installed so osTicket will run properly. Select IIS and expand the folder for more folders to select such as World Wide Web Services, CGI under Application Development feat., and Common HTTP features.
</p>
<br />

<p>
<img <a href="https://imgur.com/6h0m3C5"><img src="https://i.imgur.com/6h0m3C5.png" title="source: imgur.com" /></a>
</p>
<p>
Begin to download and install multiple files that include PHP Manager, Rewrite module, PHP 7.3.8, VC_redist.x86.exe, and MYSQL_5.5.62. For each file, select "download anyway" when prompted.
</p>
<br />

<p>
<img <a href="https://imgur.com/T82etkt"><img src="https://i.imgur.com/T82etkt.png" title="source: imgur.com" /></a>
</p>
<p>
Open IIS as an Admin and navigate to the PHP manager to register PHP with IIS and restart the application.

</p>
<img <a href="https://imgur.com/ibPUyTc"><img src="https://i.imgur.com/ibPUyTc.png" title="source: imgur.com" /></a>
</p>
<p>
Install osTicket and copy the "upload" folder to c:\inetpub\wwwroot renaming it "osTicket". Return to IIS, navigate to sites> default sites > osTicket. Then click browse *80 to see the successful installation of osTicket.
  
<a href="https://imgur.com/jT2jHgH"><img src="https://i.imgur.com/jT2jHgH.png" title="source: imgur.com" /></a>
