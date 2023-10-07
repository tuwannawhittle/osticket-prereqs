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

- Microsoft Azure Account:</b> You'll need an active Azure account to create a virtual machine.
- Azure Virtual Machine:</b> Create a virtual machine in your Azure account.
- Access to Azure Portal:</b> Login to the Azure Portal at portal.azure.com.
- Enable IIS
- Install Web Platform Installer
- Install MySQL and setup username and password
- Install Microsoft Visual C++ 2009 Redistributable Package
- Configure permissions and install osTicket

<h2>Installation Steps</h2>

<h3>Step 1: Create an Azure Virtual Machine</h3>

Login to Azure Portal:
- Go to portal.azure.com.
- Sign in with your Azure credentials.
  
Create a Virtual Machine:
- Click on "Create a resource" > "Virtual machine."
- Configure the virtual machine settings (size, OS, etc.).
- Create and configure a Network Security Group (NSG) to allow necessary ports (e.g., HTTP/HTTPS).

<h3>Step 2: Install and Configure osTicket</h3>
1. Connect to Your Virtual Machine:

  - Use Remote Desktop Protocol (RDP) to connect to your Azure Virtual Machine.

2. Install Required Software:
- Open PowerShell or Command Prompt on the virtual machine.
- Install required software components (e.g., Apache, MySQL, PHP) using package manager or download from official websites.

3. Download and Extract osTicket:
- Download the latest version of osTicket from the official website.
- Extract the downloaded file to the web server's root directory.

4. Configure Database:
- Create a MySQL database and user for osTicket.
- Import the osTicket database schema into the MySQL database.

5. Configure osTicket:
- Edit osTicket configuration files to set up the database connection and other settings.
- Access osTicket via a web browser and complete the web-based setup. 

<h3>Test and Verify</h3>
1. Test osTicket Installation:

- Access the osTicket portal in your web browser.
- Create a test ticket and verify its functionality.

2. Configure Email Integration (Optional):
- Integrate osTicket with an email server for ticket creation and replies via email.

Installation and configuration of osTicket on an Azure Virtual Machine is now complete. You now have a fully functional help desk ticketing system ready to streamline your customer support process.













