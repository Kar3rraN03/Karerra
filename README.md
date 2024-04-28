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
<img src="https://i.imgur.com/6h3Yli3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the admin panel, navigate to Agents and then Roles. Create a role called "Supreme Admin" to manage all aspects of the system.
</p>
<br />

<p>
<img src="https://i.imgur.com/cEOOd1I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure additional roles like "System Administrators" for managing departments and teams.
</p>
<br />


<p>
<img src="https://i.imgur.com/YwDbECq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/dDiXX1U.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Within the Agents section of the admin panel, go to Teams. Create teams such as Level I Support and Level II Support to assign agents to specific support levels and responsibilities.
</p>
<br />


<p>
<img src="https://i.imgur.com/0sU3rAg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the admin panel, under Settings and User Settings, enable the option for anyone to create tickets without registration.
</p>
<br />


<p>
<img src="https://i.imgur.com/FQAbQii.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/YhjaKzm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the Agents section of the admin panel, add new agents like Jane and John to handle ticket assignments and resolutions.
</p>
<br />

<p>
<img src="https://i.imgur.com/tujAd5w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/iLf3ZAJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the Agent Panel, access Users and add new customers like Karen and Ken who will interact with the system to submit tickets and seek assistance
</p>
<br />

<p>
<img src="https://i.imgur.com/pCbPMrf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/XxLe70b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/Ne4Lqun.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Navigate to Manage and then SLA in the admin panel. Set up Service Level Agreements (SLAs) such as Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), and Sev-C (8 hours, business hours) to define response and resolution times for different ticket priorities.
</p>
<br />


<p>
<img src="https://i.imgur.com/ns9Etrr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/4Slci7v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/xpfDPLD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/6k5fn6k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
In the admin panel, under Manage and Help Topics, create topics like Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset. These topics will help categorize and prioritize incoming tickets based on their nature and urgency.
</p>
<br />


