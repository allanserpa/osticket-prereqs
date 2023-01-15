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

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/k6ndpdY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br>
 <b>STEP 1:</b> Open up Control Panel and Install / Enable IIS in Windows WITH CGI
 World Wide Web Services -><br> Application Development Features -> [X] CGI <br><br>
 <b>STEP 2:</b> Download and Install <a href="https://drive.google.com/file/d/1RHsNd4eWIOwaNpj3JW4vzzmzNUH86wY_/view?usp=share_link">PHP Manager</a> for IIS <br><br>
 <b>STEP 3:</b> Download and Install the <a href="https://drive.google.com/file/d/1tIK9GZBKj1JyUP87eewxgdNqn9pZmVmY/view?usp=share_link">Rewrite Module</a> <br><br>
</p>
<br />

<p>
<img src="https://i.imgur.com/ImUS25H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br>
  <b>STEP 4:</b> Create the directory C:\PHP
</p>
<br />

<p>
<img src="https://i.imgur.com/7tIYNSy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br>
 <b>STEP 5:</b> Download <a href="https://drive.google.com/file/d/1snNMtLdCOpMtkCyD4mvl9yOOmvVIp9fP/view?usp=share_link">PHP 7.3.8</a> and unzip the contents into       C:\PHP<br><br>
 <b>STEP 6:</b> Download and Install <a href="https://drive.google.com/file/d/1s1OsGF3-ioO0_9LYizPRiVuIkb3lFJgH/view?usp=share_link">VC_redist.x86.exe</a><br><br>
 <b>STEP 7:</b> Download and Install <a href="https://drive.google.com/file/d/1_OWh9p7VQLcrB0q_V7qT8yHl0xo5gv7z/view?usp=share_link">MySQL 5.5.62</a>
 <br> - Typical Setup -> <br> - Launch Configuration Wizard (after install) -> <br> - Standard Configuration ->
</p>
<br />

<p>
<img src="https://i.imgur.com/kKibXmF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br>
 <b>STEP 8:</b> Open IIS as an Admin and Register PHP from within IIS<br><br>
 <b>STEP 9:</b> Reload IIS (Open IIS, Stop and Start the server)
</p>
<br />

<p>
<img src="https://i.imgur.com/iBeb7bW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br>
 <b>STEP 10:</b> Install osTicket v1.15.8
 <br> - Download osTicket from the Installation Files Folder
 <br> - Extract and copy “upload” folder to c:\inetpub\wwwroot
 <br> - Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”<br>
 <b>STEP 11:</b> Reload IIS (Open IIS, Stop and Start the server)
</p>
<br />

<p>
<img src="https://i.imgur.com/hqi3K4c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br>
 <b>STEP 12:</b> Go to sites -> Default -> osTicket
 <br> - On the right, click “Browse *:80”
</p>
<br />
