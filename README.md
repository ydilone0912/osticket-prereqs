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

1- You need to have a web server, such as Apache or Nginx, installed on your system to run osTicket.

2- You need to have an email server set up to send and receive emails.

3- osTicket can run on various operating systems, including Linux, Windows, and macOS.

4- To access osTicket's web-based interface, you need a modern web browser such as Google Chrome, Mozilla Firefox, or Microsoft Edge.

5- Overall, osTicket is easy to install and configure, but it's recommended to have some experience with web servers, PHP, and databases to get    the most out of it.

<h2>Installation Steps</h2>


1- Download osTicket: First, download the latest version of osTicket from the official website at https://osticket.com/download/.

2- Extract the files: Extract the downloaded osTicket archive to a directory on your web server.

3- Create a database: Create a new database on your MySQL or MariaDB server to store osTicket data. You can use the phpMyAdmin tool or command-line interface to create a database.

4- Edit the configuration file: Open the osTicket directory and locate the include/ost-config.php file. Copy this file to include/ost-config.php, and then edit the include/ost-config.php file to enter the database details and other settings for osTicket.

5- Set file permissions: Ensure that the include/ost-config.php file and the attachments directory have write permissions for the web server user. You can use the chmod command to set permissions.

6- Access the installation page: Open a web browser and navigate to the osTicket directory on your server, for example http://your-domain.com/osticket/upload/. You should see the osTicket installation page.

7- Follow the installation wizard: Follow the installation wizard instructions to configure osTicket. You'll need to enter your database details, email server settings, and other settings.

8- Set up the cron job: osTicket requires a cron job to handle automatic tasks such as email fetching, task scheduling, and more. Follow the instructions in the installation wizard to set up a cron job.

9- Login to osTicket: Once the installation is complete, log in to osTicket with the admin account you created during the installation process.


<h2>🤳Connect with me:</h2>

[<img align="left" alt="Josh | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="Josh | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="Josh | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]

[twitter]: (https://twitter.com/ydilone0912)
[instagram]: (https://www.instagram.com/gio0912/)
[linkedin]: linkedin.com/in/yovanny-dilone-3242a8247
