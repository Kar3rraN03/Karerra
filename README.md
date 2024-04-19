# <p align="center">
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

1. Configure Roles
  - Admin Panel -> Agents -> Roles
  - Supreme Admin
3. Configure Departments
   - Admin Panel -> Agents -> Departments
System Administrators
4. Configure Teams
  - Admin Panel -> Agents -> Teams
- Level I Support
- Level II Support
4.Allow anyone to create tickets
  - Admin Panel -> Settings -> User Settings
Registration Required: Require registration and login to create tickets 
5. Configure Agents (workers)
  - Admin Panel -> Agents -> Add New
  - Jane
  - John
6. Configure Users (customers)
  - Agent Panel -> Users -> Add New
  - Karen
  - Ken
7. Configure SLA
 - Admin Panel -> Manage -> SLA
 - Sev-A (1 hour, 24/7)
 - Sev-B (4 hours, 24/7)
 - Sev-C (8 hours, business hours)

8. Configure Help Topics
   - Admin Panel -> Manage -> Help Topics
 - Business Critical Outage
 - Personal Computer Issues
 - Equipment Request
 - Password Reset


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to the Admin Panel, then navigate to Agents and select Roles to configure roles, such as Supreme Admin.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To set up departments, access Admin Panel, go to Agents, and then choose Departments, like System Administrators..
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure teams by going to Admin Panel, selecting Agents, and then Teams, such as Level I Support and Level II Support.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow anyone to create tickets by going to Admin Panel, then Settings, and User Settings, and enable "Registration Required" to require registration and login for ticket creation.
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure agents, access Admin Panel, go to Agents, and click on Add New to add agents like Jane and John..
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure users by going to Agent Panel, selecting Users, and then Add New to add users like Karen and Ken.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Set up SLA (Service Level Agreements) by accessing Admin Panel, then Manage, and selecting SLA, with options like Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), and Sev-C (8 hours, business hours).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics by going to Admin Panel, then Manage, and selecting Help Topics, with categories like Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset.
</p>
<br />
