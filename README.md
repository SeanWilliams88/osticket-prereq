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

Creating two virtual machines in microsoft azure

Installing osTicket on a virtual machine

Installing Active Directory on a virtual machine

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/cDcTGCp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To create virtual machines on Azure, follow these steps:

1. Sign in to the Azure portal using your Azure account.
2. Click on "Create a resource" and search for "Virtual Machine" in the search bar.
3. Select the desired virtual machine image from the available options, such as Windows or Linux distributions.
4. Choose the appropriate configuration for the virtual machine, including the size, storage, and networking options.
5. Specify the authentication method, such as SSH keys or passwords, to access the virtual machine.
6. Configure additional settings, such as availability options, monitoring, and auto-shutdown policies, according to your requirements.
7. Review the summary of your virtual machine configuration, and then click on "Create" to initiate the deployment process.
8. Azure will provision the virtual machine, which may take a few minutes. You can monitor the progress on the Azure portal.
9. Once the virtual machine is successfully created, you can connect to it using the provided access credentials or remote desktop protocols.
10. Manage and customize your virtual machine as needed, such as installing software, configuring network settings, and scaling resources.

Remember to consider factors such as security, performance, and cost optimization while configuring your virtual machines on Azure.
</p>
<br />

<p>
<img src="https://i.imgur.com/6BwflEQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To install osTicket on a virtual machine, follow these steps:

1. Start by setting up a virtual machine with your desired operating system (e.g., Windows or Linux) on a platform like Azure or VMware.
2. Access your virtual machine using remote desktop or SSH, depending on the operating system. This allows you to control and manage the virtual machine from your computer.
3. On the virtual machine, download the latest version of osTicket from the official website or a trusted source.
4. Once the download is complete, extract the osTicket files and copy them to a web server directory, such as /var/www/html for Linux or C:\inetpub\wwwroot for Windows.
5. Ensure that the necessary dependencies, such as a web server (e.g., Apache or Nginx), PHP, and a database (e.g., MySQL or PostgreSQL), are installed and properly configured on the virtual machine.
6. Create a new database for osTicket, and note down the database name, username, and password for future use.
7. Open a web browser on your computer and enter the IP address or hostname of the virtual machine to access the osTicket installation wizard.
8. Follow the on-screen instructions, providing the required information such as the database details, administrator email, and password.
9. Complete the installation process, and once finished, you should be able to access osTicket by visiting the virtual machine's IP address or hostname in a web browser.
10. Customize osTicket according to your needs, configure email settings for ticket notifications, and start using it to manage customer support requests.

Remember to secure your virtual machine and osTicket installation by using strong passwords, keeping your software up to date, and following best practices for system administration.
</p>
<br />

<p>
<img src="https://i.imgur.com/QJ7dYQP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To install Active Directory on a virtual machine, follow these steps:

1. Set up a virtual machine with Windows Server as the operating system on a platform like Azure or VMware.
2. Access the virtual machine using remote desktop or a similar method.
3. Open the Server Manager and click on "Add roles and features" to start the installation wizard.
4. Select "Active Directory Domain Services" as the role to install and follow the prompts to complete the installation.
5. After the installation, a configuration wizard will appear. Choose the option to "Promote this server to a domain controller."
6. Select the appropriate deployment type, such as adding a new forest or joining an existing forest.
7. Provide the desired domain name, such as "mycompany.local," and set the domain and directory services restore mode passwords.
8. Choose the appropriate domain controller options, such as DNS server and Global Catalog.
9. Review the summary and click on "Install" to begin the Active Directory installation and configuration process.
10. Once the installation is complete, the virtual machine will be configured as an Active Directory domain controller. You can now manage users, groups, and other domain-related settings.

Remember to plan and design your Active Directory deployment carefully, considering factors such as domain naming, replication, and security. It's also important to keep your Active Directory environment secure by implementing best practices, such as regular backups, monitoring, and strong password policies.
</p>
<br />
