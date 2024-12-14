<p align="center">
![image](https://github.com/user-attachments/assets/dfa00ec3-dd4d-4f98-a726-8a2413fd0a4e)

![image](https://github.com/user-attachments/assets/cfc17c51-b39c-47c4-be95-4e5f2193cee8)

</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
  
![image](https://github.com/user-attachments/assets/35ed2ee0-61f2-40b8-b9d5-40e543960232)

Once logged in, click on the Admin Panel. Hover over "Agents" and click on "Roles" in the dropdown menu.

![image](https://github.com/user-attachments/assets/0a4e6631-3769-4a2d-a508-2fbdc8926024)

![image](https://github.com/user-attachments/assets/f1be395a-51f0-4efd-8e4d-5016329ef64c)
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

  
![image](https://github.com/user-attachments/assets/f1be395a-51f0-4efd-8e4d-5016329ef64c)

![image](https://github.com/user-attachments/assets/dfa00ec3-dd4d-4f98-a726-8a2413fd0a4e)

![image](https://github.com/user-attachments/assets/cfc17c51-b39c-47c4-be95-4e5f2193cee8)
</p>
<br />

<p>
Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments: SysAdmins Scroll Down and click on "Create Dept"

![image](https://github.com/user-attachments/assets/800de400-b713-4650-ac53-4bb73fa23098)



</p>
<p>
Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking
  
![image](https://github.com/user-attachments/assets/674bf63e-fe07-43b0-a09b-f681af226e8d)

![image](https://github.com/user-attachments/assets/ba473d1b-1134-4f6f-84c4-9a856517bb92)

</p>
<br />

<p>
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets 
  
![image](https://github.com/user-attachments/assets/dd2ec249-a992-4e4e-9a47-2431de3a4370)

  

</p>
<p>
Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)


![image](https://github.com/user-attachments/assets/27ca31ea-0330-433a-9425-0c3779741ab3)

![image](https://github.com/user-attachments/assets/c121180c-ed82-4538-949e-53fd19015996)

![image](https://github.com/user-attachments/assets/9b1c4c36-ff1a-4c00-bb92-e31eee6618e3)

![image](https://github.com/user-attachments/assets/feea6614-6e21-47fb-ad31-907e96827168)

![image](https://github.com/user-attachments/assets/344d42bc-9e3c-47bd-bdaa-279f002210c2)

Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken

![image](https://github.com/user-attachments/assets/4108f81f-b269-42ee-9da9-fb1e64018b53)
Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)


![image](https://github.com/user-attachments/assets/1ae05756-c177-4bda-a900-00ded20214af)

![image](https://github.com/user-attachments/assets/651a762e-7d0e-40c9-b48a-771995e86de2)

Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other
![image](https://github.com/user-attachments/assets/6d4c1731-0cca-40c7-8768-c25d9dbaad16)

![image](https://github.com/user-attachments/assets/78051ee8-bb0a-44f4-890a-743915b64542)

![image](https://github.com/user-attachments/assets/dcd882cd-9009-4dbb-8c0f-bf8253c806f6)
