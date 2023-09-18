<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
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

- Configure Roles, Departments, Teams
- Allow anyone to create tickets
- Configure Agents (employees), Users (customers)
- Configure SLA (service level agreements)
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
1. Configure Roles

  First, go to the Admin Panel, then Agents, and finally Roles. We will create a role named Supreme Admin.
  
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
2. Configure Departments

  First, go to the Admin Panel, then Agents, and finally Departments. We will create a department named System Administrators.
  
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
3. Configure Teams

  First, go to the Admin Panel, then Agents, and finally Teams. We will create 2 teams named, Level I Support and Level II Support.
  
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
4. We will allow anyone to create a ticket

  First, go to the Admin Panel, then Settings, and then User Settings. We will make it so users are required to register and log in to create tickets.
  
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
5. Configure Agents (employees)

  First go to the Admin Panel, then Agents, and click on Add New. We will add two "employees" named, Jane and John.
  
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
6. Configure Users (customers)

  First, we will go to the Agent Panel this time. Then click on Users and Add New. We will add two "customers" named, Karen and Ken.
  
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
7. Configure SLA (Service Level Agreements)

  First, go to the Admin Panel, next Manage, and then SLA. We will create three severity levels. One being Sev-A. Make it so you want it resolved within an hour on a 24/7 time clock. 

  Next, create the second SLA, Sev-B. Require it to be resolved within 4 hours on a 24/7 time clock.

  Finally, create the third SLA, Sev-C. Require it to be resolved within 8 hours, but only during business hours, Monday through Friday 8 am - 5 pm.
  
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
8. Configure Help Topics

  First, go to the Admin Panel, Manage, and then Help Topics. Create four new help topics.
    - Business Critical Outage
    - Personal Computer Issues
    - Equipment Request
    - Password Reset
    
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Congrats, we've now finished our post-installation setup, completing all our objectives.
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
