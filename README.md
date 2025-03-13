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

<h2>List of Links</h2>

- Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 
- End Users osTicket URL:
http://localhost/osTicket 

<h2>Post Installation Steps</h2>

<p>
  
![Permissions](https://github.com/user-attachments/assets/97b23a7b-0990-4421-aac5-faa9a45b1524)

  
</p>
<p>
1. Configure Roles (Grouping Permissions)
Path: Admin Panel → Agents → Roles
Role: Supreme Admin

![Dept  Perms](https://github.com/user-attachments/assets/06cbcde9-f431-405f-b2bb-378493d1f043)

  
2. Configure Departments (Ticket Visibility)
Path: Admin Panel → Agents → Departments
Departments:
SysAdmins
Help Desk
Networking

![Teams Perms](https://github.com/user-attachments/assets/503be81e-f989-4dad-bfe3-3ec7b385b644)


4. Configure Teams (Cross-Department Collaboration)
Path: Admin Panel → Agents → Teams
Team: Online Banking (Pulls agents from different departments)

6. Allow Ticket Creation (User Registration Requirement)
Path: Admin Panel → Settings → User Settings
Action:
UNCHECK: "Unregistered users can create tickets"
Require registration and login to create tickets

![Agent](https://github.com/user-attachments/assets/2236f2e1-36b3-4322-8a86-a50ae1e0adda)


8. Configure Agents (Workers)
Path: Admin Panel → Agents → Add New
Agents & Departments:
Bob Loe → Dept: SysAdmins
Rick Lee → Dept: Support

10. Configure Users (Customers)
Path: Agent Panel → Users → Add New
Users:
Billy Ray,
Fernando

![SLA's](https://github.com/user-attachments/assets/23c4c2a7-1fb9-422b-8aa1-25029cf1b2a8)


12. Configure SLA (Service Level Agreements)
Path: Admin Panel → Manage → SLA
SLA Levels:
Sev-A → Grace Period: 1 hour, Schedule: 24/7
Sev-B → Grace Period: 4 hours, Schedule: 24/7
Sev-C → Grace Period: 8 hours, Schedule: Business Hours


![Help Topics](https://github.com/user-attachments/assets/dbcae106-6775-4160-ac4d-9769888f1952)


13. Configure Help Topics (User Ticket Categories)
Path: Admin Panel → Manage → Help Topics
Topics:
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other
</p>
<br />

<p>



</p>
<p>



</p>
<br />

