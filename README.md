<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket Software

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Logging into both Admin and Agent Portal
- Configuring Roles
- Configuring Departments
- Configuring Teams
- Configuring Agents and Users
- Configuring SLA and Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/9O0w0t7.png" height="1000%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
With osTicket fully configured, we can use the url http://localhost/osTicket/scp/login.php to get to the admin/analyst login page. You will need to use the email and password used when setting up the admin portion of osTicket. This page is where you will set up your roles, departments, teams, agents, users, and SLA and help topics.
</p>
<br />

<p>
<img src="https://imgur.com/rtzXO2w.png" height="1000%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To start setting up our roles, we will navigate to "Admin Panel", then to "Agents", and finally to "Roles". This is where we can see what each of our default roles are allowed to do and create new roles that have permission to do specific tasks that we may choose. In this section I made a role named "Supreme Admin" whick has every permission and access option selected.
</p>
<br />

<p>
<img src="https://imgur.com/NDPGznm.png" height="1000%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For setting up Departments, navigate to the "Departments" section within the Admin Panel. This section is used for ticket visibility so that tickets can be designated to proper departments and organized/handled accordingly. I made a department named SysAdmins to demonstrate how adding a new department would look.
</p>
<br />

<p>
<img src="https://imgur.com/gTc9HRL.png" height="1000%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure Teams, navigate to the "Teams" section at the top of the screen. This section would be used to create a new group of people who are all from different departments. I have made a team named "Online banking" to demonstrate that visually. 
</p>
<br />

<p>
<img src="https://imgur.com/j2KJyJX.png" height="1000%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
For creating new Agents (workers), navigate to the "Agents" section  of the admin panel and select "Add New". For the sake of this demonstration, I am creating a user named Jane Doe and placing her in the SysAdmins department, the Online Banking team, and giving her Supreme Admin access.
</p>
<br />

<p>
<img src="https://imgur.com/bDRa11j.png" height="1000%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After configuring Agents, we will want to configure Users that will be sending trouble tickets to the ticketing system. These are the tickets that would be worked by agents of a specifified department in a real world scenario. Navigate to the "Agent Panel" then "Users", then select "Add Users". I have added both Ken and Karen as Users.
</p>
<br />

<p>
<img src="https://imgur.com/j2KJyJX.png" height="1000%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we will configre the SLA (Service Level Agreements). This is a priority/time frame system for how tickets will be handled. Different organizations will have different SLA set in place to guide Agents on the order and time frame in which to handle tickets as they are received. To configure them we will go to the Admin Panel, then select "Manage", then "SLA". Pictured above, I have added 3 different SLA plans labelled SEV-A, SEV-B, and SEV-C (from highest severity to lowest).
</p>
<br />

<p>
<img src="https://imgur.com/54TOz9c.png" height="1000%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally we will create Help Topics. These are essentailly categories that users will add to their ticket to help agents get a quick understanding of what the ticket pertains to. As seen above, I have added a multitude of help topics that can be attached to future touble tickets in order to speed up the solution.
</p>
<br />

