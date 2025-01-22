# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

1- Azure Virtual Machine

2- Windows IIS and Dependencies

3- PHP Environment

4- MySQL Database

<h2>Installation Steps</h2>

<img width="1127" alt="image" src="https://github.com/user-attachments/assets/807524e5-3d57-4db9-b9cb-ffe5c7b66c26" />

Install All necessary files like  PHP Manager for IIS, Rewrite Module, VC redist, MySQL

<img width="1126" alt="image" src="https://github.com/user-attachments/assets/3118fbb5-e226-4e23-b43a-fb191c6c754f" />

After installing files, create an account through SQL

<img width="1285" alt="image" src="https://github.com/user-attachments/assets/5215de8a-19d0-4bb2-87bf-e41d80fd146a" />

Then, register PHP from within IIS (PHP Manager -> C:\PHP\php-cgi.exe)

<img width="1124" alt="image" src="https://github.com/user-attachments/assets/61d84088-1daf-4adc-89ed-18dfc244c797" />

Then, copy upload file to “c:\inetpub\wwwroot” Within “c:\inetpub\wwwroot”, Rename “upload” to “osTicket”

<img width="1728" alt="image" src="https://github.com/user-attachments/assets/cf4445e8-2e82-42a9-a316-3bfdd84457e7" />

Fill in the info on the osTicket website

<img width="1728" alt="image" src="https://github.com/user-attachments/assets/43eb6548-9635-4be9-8062-cfd9e721b6d9" />

osTicket has been downloaded successfully.
