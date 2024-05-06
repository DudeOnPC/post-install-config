<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 Pro, version 22H2 - Gen2

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles

- Configure Departments

- Configure Teams

- Allow anyone to create tickets

- Configure Agents (workers)

- Configure Users (customers)

- Configure SLA

- Configure Help Topics


<h2>Configuration Steps</h2>


**Configure Roles**
1. Admin Panel--> Agents--> Roles
2. Supreme Admin
   
![image](https://github.com/DudeOnPC/post-install-config/assets/167653474/64d79afc-5a6f-4934-aa2b-0ab8f3b67663)


**Configure Departments**
1. Admin Panel--> Agents--> Departments
2. System Administrators

**Configure Teams**
-Admin Panel--> Agents--> Teams
1.Level I Support
2.Level II Support


**Allow anyone to create tickets**
1. Admin Panel--> Settings--> User Settings
2. Registration Required: Require registration and login to create tickets 
Configure Agents (workers)
-Admin Panel--> Agents--> Add New
1. Jane
2. John


**Configure Users (customers)**
-Agent Panel--> Users--> Add New
1. Karen
2. Ken


**Configure SLA**
-Admin Panel--> Manage--> SLA
1. Sev-A (1 hour, 24/7)
2. Sev-B (4 hours, 24/7)
3. Sev-C (8 hours, business hours)


**Configure Help Topics**
-Admin Panel--> Manage--> Help Topics
1. Business Critical Outage
2. Personal Computer Issues
3. Equipment Request
4. Password Reset
