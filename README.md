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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA

Download and Install all of the configuration objectives from the Installation Files

<h2>Configuration Steps </h2> 
<p>
<img src="https://i.imgur.com/A1SB9Lr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
Admin Panel -> Agents -> Roles -> Supreme Admin
  
*Roles - Permissions - check off all boxes for permissions, 
tasks and knowledgebases, save changes.*

</p>
<br />


<p>
<img src="https://i.imgur.com/C5ULwan.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Admin Panel -> Agents -> Departments -> System Administrators

*Admin Panel, Agents, Departments, once there Add new Department,
adjust settings, "System Administrators", SLA default leave on. Save changes.*
</p>
<br />

<p>
<img src="https://i.imgur.com/vXP6Xag.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
Admin Panel -> Agents -> Teams
Level I Support
  
Level II Support Or
  
Create new Team
  
*Allow anyone to create tickets-
Admin panel, Users, Settings, (make sure you uncheck "Require registration and login to create tickets)*

</p>
<br />

<p>
<img src="https://i.imgur.com/J028tSX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
Agents - Admin Panel, Agents, Add new, ex. Jane Doe or John Doe., create username for both
agents, create password (remember to write now your credentials so you dont forget) uncheck
require password change at login and hit set. 

</p>
<br />


<p>
<img src="https://i.imgur.com/nvSkd2Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
Users - Agent Panel, Users, Add new user, create email and fill in full name.

</p>
<br />



<p>
<img src="https://i.imgur.com/9hxEwnf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
Admin Panel -> Manage -> SLA
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)

</p>
<br />


<p>
  
<3>Configure Help Topics</h3>
  
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset


</p>
<br />
