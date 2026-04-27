<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- mySQL

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1-Create VMs in Azure
- Item 2-Download OS-ticket
- Item 3-Create IIS Server
- Item 4-Create mySQL server
  

<h2>Installation Steps</h2>

<p>
<img width="1915" height="920" alt="image" src="https://github.com/user-attachments/assets/a6d07d39-ae4c-4b60-a512-f7cee0771fdf" />
</p>
<p>
Created Windows 10 VM in Azure that will be the client machine for the osTicket system. For detailed tutorial on VM creation see https://github.com/alawalke2606/create-vms/blob/main/README.md
</p>
<br />

<p>
<img width="1919" height="1037" alt="image" src="https://github.com/user-attachments/assets/116bd04c-bdcd-4e5a-8156-73dda107ae6a" />
</p>
<p>
Downloaded osTicket zipfile from link page. Extraced osTicket zipfile to desktop. 
</p>
<br />

<p>
<img width="725" height="584" alt="image" src="https://github.com/user-attachments/assets/9d01a257-7372-4278-b4f9-8b48e4a8dfd0" /> <img width="1917" height="1039" alt="image" src="https://github.com/user-attachments/assets/6649c07d-8475-40ef-94de-9dfaf8d6f77d" />
</p>
<p>
Installed the IIS server and verified that it was working correctly.
</p>
<br />

<p>
<img width="1903" height="1031" alt="image" src="https://github.com/user-attachments/assets/df0c9c35-d3ff-41f7-b47d-d5080a642d2e" /> <img width="1911" height="1028" alt="image" src="https://github.com/user-attachments/assets/41a5e91f-1a04-426f-b077-7960d7a73696" />
</p>
<p>
Installed the PHP Manager and Rewrite module for osTicket.
</p>
<br />

<p>
<img width="1910" height="1030" alt="image" src="https://github.com/user-attachments/assets/1d4c3034-1587-4fee-bb49-effe915090c4" />
</p>
<p>
Extracted PHP files to PHP folder. Installed VC_redistr.exe file.
</p>
<br />

<p>
<img width="1911" height="1046" alt="image" src="https://github.com/user-attachments/assets/d7b5d92e-3241-4921-b045-37f8e0f1e70b" />
</p>
<p>
Installed mySQL server to host information for the osTicket server.
</p>
<br />

<p>
<img width="1441" height="768" alt="image" src="https://github.com/user-attachments/assets/18efa63b-6a12-4c58-b574-aba7f543d4cc" />
</p>
<p>
Registered PHP from within IIS. Reloaded the ISS server.
</p>
<br />

<p>
<img width="1914" height="1037" alt="image" src="https://github.com/user-attachments/assets/9edae5dc-5da5-4eff-95e9-b3a1822cdbd2" />
</p>
<p>
Installed osTicket in ISS and browsed to website.
</p>
<br />

<p>
<img width="1349" height="705" alt="image" src="https://github.com/user-attachments/assets/98fc817d-cc86-425a-ac6c-1785b8eef3e7" />
</p>
<p>
Enabled PHP.imap and PHP.intl within ISS.
</p>
<br />

<p>
<img width="1914" height="1034" alt="image" src="https://github.com/user-attachments/assets/9b954368-9f9f-491a-8c02-c3e83efcd2c4" />
</p>
<p>
Configured ost-config.php and changed permissions to osTicket to make changes to configuration file.
</p>
<br />

<p>
<img width="1917" height="1039" alt="image" src="https://github.com/user-attachments/assets/68bb4712-213d-47fe-804b-61b7304f26fc" />
</p>
<p>
Set up osTicket admin user and help desk name with email that will receive tickets.
</p>
<br />

<p>
<img width="1914" height="1036" alt="image" src="https://github.com/user-attachments/assets/04fa49ff-67ce-4525-9661-670471547f7c" /> <img width="960" height="610" alt="image" src="https://github.com/user-attachments/assets/1b730531-3da1-4c0d-8af7-d9a659801d6a" />
</p>
<p>
Created new SQL session that connected to osTicket and created a new database called "osTicket"
</p>
<br />

<p>
<img width="829" height="430" alt="image" src="https://github.com/user-attachments/assets/b6ae3807-1c37-4f01-a9a3-7a6d911bcea0" /> <img width="838" height="681" alt="image" src="https://github.com/user-attachments/assets/592d359b-7e50-4a03-9a4f-cd9c4b7622e2" />
</p>
<p>
Finished setting up database in osTicket broswer. Completed install of osTicket.
</p>
<br />

<p>
<img width="1536" height="441" alt="image" src="https://github.com/user-attachments/assets/d843747f-71bc-4e07-87c4-52043005beb8" />
</p>
<p>
Admin homepage of osTicket.
</p>
<br />

<p>
<img width="1401" height="629" alt="image" src="https://github.com/user-attachments/assets/ae6a89a6-cbde-4ebc-985c-6199f2d71dcb" />
</p>
<p>
End user ticket creation page.
</p>
<br />


