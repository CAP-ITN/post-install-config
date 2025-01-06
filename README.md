# Post-Install-Config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket-Post-Install-Config</h1>
This tutorial outlines post instructions after installing.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 
- End Users osTicket URL:
http://localhost/osTicket 

<h2>Post Installation Steps</h2>

<p>
  
image here
  
</p>
<p>
onfigure Agent and User Panels
The Agent Panel is used for managing tickets and handling user inquiries, while the Admin Panel is used for system configuration and administrative tasks.

Configure Roles
Navigate to Admin Panel -> Agents -> Roles to create and assign roles, such as Supreme Admin, for grouping permissions.

Configure Departments
Go to Admin Panel -> Agents -> Departments to set up departments like SysAdmins, which define ticket visibility and workflow among teams.

Configure Teams
In Admin Panel -> Agents -> Teams, create teams like Online Banking that pull agents from different departments for better collaboration.

Allow Anyone to Create Tickets
Open Admin Panel -> Settings -> User Settings, uncheck "unregistered users can create tickets," and enable "Registration Required" to require user registration before ticket submission.

Configure Agents (Workers)
Navigate to Admin Panel -> Agents -> Add New and add agents such as Jane (SysAdmins Department) and John (Support Department) to manage support requests.

Configure Users (Customers)
Go to Agent Panel -> Users -> Add New and create user accounts for customers like Karen and Ken to allow them to submit tickets.

Configure SLA (Service Level Agreements)
In Admin Panel -> Manage -> SLA, configure response times for different priority levels:

Sev-A (1-hour grace period, 24/7 schedule)

Sev-B (4-hour grace period, 24/7 schedule)

Sev-C (8-hour grace period, business hours only)

Configure Help Topics
Navigate to Admin Panel -> Manage -> Help Topics and set up predefined help topics to categorize user tickets, such as:

Business Critical Outage

Personal Computer Issues

Equipment Request

Password Reset

Other


</p>
<br />

<p>

image here

</p>
<p>
input here
</p>
<br />

