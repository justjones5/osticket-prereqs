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

- Created a Resource Group in Microsoft Azure
- Created a Windows 10 Virtual Machine (VM) with 2-4 Virtual CPUs in Microsoft Azure
- Installed Microsoft Remote Desktop
- Connected to Virtual Machine (VM) with Remote Desktop
- Installed/Enabled Internet Information Services (IIS)
- Installed Web Platform Installer
- Installed MySQL 5.5 instead of username and password
- Installed PHP Version 7.3.8
- Installed PHP Manager 1.5.0 for IIS 10
- Installed C++ 2009 Redistributable Package
- Configured Permissions and Installed osTicket
- After-Installation Configuraton of osTicket

<h2>Installation Steps</h2>

1.) Start by creating a virtual machine in the Azure portal. Set it up with Windows 10 Pro, version 22H2, and ensure the machine has at least 2 vCPUs and 16 GB of memory.

2.) After setting up your virtual machine, connect to it using its public IP address via the Remote Desktop Connection app.
</p>

![image](https://github.com/user-attachments/assets/32ec6199-8939-4a95-b513-cd61f96f14f9)

![image](https://github.com/user-attachments/assets/2be39f57-7418-41f3-8946-0e62d2afc783)

3.) After connecting to your virtual machine, open the Control Panel. Go to "Programs," then select "Turn Windows features on or off."


![image](https://github.com/user-attachments/assets/2a2ffe16-5730-469f-8c86-dbe2982a28f9)

![image](https://github.com/user-attachments/assets/405a6ac0-ba8b-4c4c-b670-8a39d260072d)

4) Installed and enabled Internet Information Services (IIS) on the virtual machine to set up a web server for hosting the osTicket application.


![image](https://github.com/user-attachments/assets/4cae2dbb-3f9e-46ad-8fae-98a1db1385e9)

![image](https://github.com/user-attachments/assets/ede638f9-7b28-455c-8963-9375eaf37a8d)

5.) Installed the Web Platform Installer, then installed MySQL and all x86 versions of PHP up to version 7.3. Also installed the required prerequisites: PHP version 7.3.8, PHP Manager 1.5.0 for IIS 10, and Microsoft Visual C++ 2009 Redistributable Package.

![image](https://github.com/user-attachments/assets/03bf4c98-4517-4b6c-ae4c-1ba5ed2f9f65)

![image](https://github.com/user-attachments/assets/51f70303-656c-4213-a030-25e7e516b601)

![image](https://github.com/user-attachments/assets/d14e81da-7dbd-45cd-a9f6-0cdb7fc6044a)

6) Installed osTicket and enabled essential extensions in IIS PHP Manager for osTicket functionality, including php_imap.dll, php_intl.dll, and php_opcache.dll.

![image](https://github.com/user-attachments/assets/3b627d5a-d68c-45e8-a373-fe72a0e0e06f)

![image](https://github.com/user-attachments/assets/2dffb4c8-c17e-47f0-a01f-0e7d903bf346)

7) Renamed ost-sampleconfig.php to ost-config.php (located at C:\inetpub\wwwroot\osTicket\include). Disabled all inherited permissions for ost-config.php and assigned new permissions to "Everyone."

![image](https://github.com/user-attachments/assets/b57cbc4c-c970-41bb-bc25-e56ceb1b7fd9)

![image](https://github.com/user-attachments/assets/68295bb7-d2fe-4fd1-9202-8b0ed9462c25)

![image](https://github.com/user-attachments/assets/294b5b16-3cae-46fb-8bf0-a96245788693)

8) Downloaded and installed HeidiSQL to set up the database connection. Created a new session and database in HeidiSQL to configure the database settings for completing the osTicket installation. Finalized the osTicket installation in the browser.

![image](https://github.com/user-attachments/assets/d7d1db15-71bc-487a-9878-2e487def0487)

![image](https://github.com/user-attachments/assets/a28d188f-4d77-4b6d-9244-1ebaac47b8ef)

![image](https://github.com/user-attachments/assets/0ab0c148-d19e-46fa-a730-ec5da1b3bafc)







