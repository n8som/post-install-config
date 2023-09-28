<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

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

![image](https://github.com/n8som/post-install-config/assets/110139109/0d363112-6627-4eaa-b932-813d2c9013f2)

![image](https://github.com/n8som/post-install-config/assets/110139109/5698cd03-0526-4064-bd54-56895ad5d501)

![image](https://github.com/n8som/post-install-config/assets/110139109/b6923062-7d55-42ad-9598-b493bd624f93)

</p>
<br />

<p>
2. Configure Departments

  First, go to the Admin Panel, then Agents, and finally Departments. We will create a department named System Administrators.
  
</p>
<p>

![image](https://github.com/n8som/post-install-config/assets/110139109/3ad713c7-aee7-42e3-84f2-e4b2cc83d319)

</p>
<br />

<p>
3. Configure Teams

  First, go to the Admin Panel, then Agents, and finally Teams. We will create 2 teams named, Level I Support and Level II Support.
  
</p>
<p>

![image](https://github.com/n8som/post-install-config/assets/110139109/94808e0c-f2a3-42f6-ae05-23b277d07228)

</p>
<br />

<p>
4. We will allow anyone to create a ticket

  First, go to the Admin Panel, then Settings, and then User Settings. We will make it so users are required to register and log in to create tickets.
  
</p>
<p>

![image](https://github.com/n8som/post-install-config/assets/110139109/c0025313-4d2f-48a5-9443-315dd24af1e4)

</p>
<br />

<p>
5. Configure Agents (employees)

  First go to the Admin Panel, then Agents, and click on Add New. We will add two "employees" named, Jane and Jake.

  ![image](https://github.com/n8som/post-install-config/assets/110139109/7bde5291-aba2-46af-9d77-b6bc58c645f2)

  ![image](https://github.com/n8som/post-install-config/assets/110139109/21e09089-27a4-44b1-aeae-6be2289c3486)

  ![image](https://github.com/n8som/post-install-config/assets/110139109/bfb4c589-dbfd-41aa-a576-0a5e98ae3305)
  
</p>
<br />

<p>
6. Configure Users (customers)

  First, we will go to the Agent Panel this time.

  ![image](https://github.com/n8som/post-install-config/assets/110139109/7a00bcd9-e322-4dd5-8e11-f651fcc171b7)

  Then click on Users and Add New.

  ![image](https://github.com/n8som/post-install-config/assets/110139109/6b5a8944-8fd0-4c51-a566-a7e85bf65fda)

  We will add two "customers" named, Karen and Ken.

  ![image](https://github.com/n8som/post-install-config/assets/110139109/3c6fefd6-e9e3-4b5e-9f0e-440d82cf6433)

</p>
<br />

<p>
7. Configure SLA (Service Level Agreements)

  First, go to the Admin Panel, next Manage, and then SLA. We will create three severity levels. One being Sev-A. Make it so you want it resolved within an hour on a 24/7 time clock. 

  Next, create the second SLA, Sev-B. Require it to be resolved within 4 hours on a 24/7 time clock.

  Finally, create the third SLA, Sev-C. Require it to be resolved within 8 hours, but only during business hours, Monday through Friday 8 am - 5 pm.
  
</p>
<p>

![image](https://github.com/n8som/post-install-config/assets/110139109/fa013411-fae7-416b-8c77-b4936d4dcee9)

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

![image](https://github.com/n8som/post-install-config/assets/110139109/fd30aaab-47fb-4b26-94ed-f2172d23777a)

</p>
<br />

<p>
Congrats, we've now finished our post-installation setup, completing all our objectives.
</p>
<br />
