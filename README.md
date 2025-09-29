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
- Create Virtual Machine using Microsift Azure
- Install IIS in Windows with CGI
- Install osTicket files (PHP Manager, Rewrite Module, PHP 7.3.8)
- Install MySQL 5.5.62 in C:\PHP folder (created folder by you) Set username and password
- Open IIS as admin and install osTicket v1.15.8 within c:\inetpub\wwwroot folder
- Reload IIS server and enable extensions through sites -> Default -> osTicket -> PHP Manager -> Enable/disable extension
- Continue setting up osTicket then install HeidiSQL - Login using MySQL username and password
Congratulations! You've installed osTicket!

<h2>Installation Steps</h2>

<p>
<img width="1411" height="782" alt="image" src="https://github.com/user-attachments/assets/6b9b4ec1-dcee-4375-a744-5dff235df56f" />
<img width="1752" height="823" alt="image" src="https://github.com/user-attachments/assets/046325fb-fc85-4445-a892-c4eb1e1a4f40" /> 


</p>
<p>
Create a virtual machine in Microsoft Azure. Name the Virtual Machine as shown above. Use Windows Server or Windows 10. Use an image of 2-4 vCPUs. Create and write down Username and password to login to vm through Remote Desktop using the vm public IP address.
</p>
<br />
<img width="660" height="666" alt="image" src="https://github.com/user-attachments/assets/5cc0dae9-e05b-4170-b404-5f0b632d80b2" />
<img width="1073" height="711" alt="image" src="https://github.com/user-attachments/assets/33ebc715-ff1a-425d-b278-ead212c8f2e6" />
<img width="621" height="572" alt="image" src="https://github.com/user-attachments/assets/651dca08-ed32-4ca2-b60a-d79598b38bab" />

<p>
</p>
<p>
Install IIS with CGI along with osTicket installation files. When installing MySQL, make sure to write down username and password as this will be used later on in the installation process. Open IIS as admin and install osTicket. Reload the server and enable extensions needed for osTicket operation.
<br />

<p>
<img width="612" height="607" alt="image" src="https://github.com/user-attachments/assets/d0aa2de2-3475-445e-8802-4cd39a46dd45" />
 <img width="1077" height="665" alt="image" src="https://github.com/user-attachments/assets/e9a2ec57-5004-4fa8-988e-6276481d41ee" />
 
</p>
<p>
Finish setting up osTicket and install HeidiSQL. HeidiSQL will allow you to complete the full setup of osTicket. Use the MySQL username and password in HeidiSQL. Congratulations! You have set up osTicket.</p>
<br />
