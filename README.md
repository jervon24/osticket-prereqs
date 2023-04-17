<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>

This project outlines the installation of the prerequisities required to use OsTicketing system.

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>List of Steps and Prerequisites</h2>

- Enable Internet Information Services (IIS)  
- Install PHP Manager
- Install MYSQL
- Register PHP from within IIS
- Install OS-Ticket
- Install Heidi SQL


 All labs in my portfolio are created in Microsoft Azure. 
 

 <img src=https://i.imgur.com/fgP5riF.png/>
 
 The picture above displays the installation of Internet Information Services and CGI. CGI enables the installation of PHP Manager which is a back end web programming language to allow OS Ticket to run efficiently.


 <img src=https://i.imgur.com/N6HsCyC.png/>
 
 PHP Manager was then downloaded and installed. It allows for the installation of PHP from with IIS, Configuration of various PHP settings and to Enable or disable PHP extensions.
 
  <img src=https://i.imgur.com/U0Hm13C.png/>
     
  MY SQL server was download and installed. MY SQL is a database management system used for storing and manipulating data. In this case it is use to store information on clients, agents, tickets just to name a few.


 <img src=https://i.imgur.com/zBV2nmE.png/>
 
 PHP was then registered from within IIS. OS Ticket is now ready to be installed.
 

<img src=https://i.imgur.com/upKXohr.png/>

OS Ticket was then downloaded and extensions; php_imap.dll, php_intl.dll and php_opcache.dll were enabled in Internet Information Services manager to have OS Ticket fully operating.


<img src=https://i.imgur.com/od85aKB.png/>

Heidi SQL was downloaded and Installed. It allows to connect to the MYSQL server and setup a database that OS Ticket is going to use.

<img src=https://i.imgur.com/xWxJoIo.png/>

The image above shows the successfull installation of OS-Ticket after all of the required programs were downloaded and installed. 
