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

- Configure Roles, Departments, and Teams within osTicket
- Allow anyone to create tickets (primarily users)
- Configure Agents (workers), Users (customers), and SLA (Service Level Agreement)
- Configure Help Topics
  
<h2>Configuration Steps</h2>

<h3>1.</h3> (Admin Panel -> Agents -> Roles),  Create a "Supreme Admin" and assign it all permissions

<h3>2.</h3> (Admin Panel -> Agents -> Departments),  Create a "System Administrator" department and keep all default settings

<h3>3.</h3> (Admin Panel -> Agents -> Teams),  Create 2 teams / 2 levels of support ( Level I Support & Level II Support)

<h3>4.</h3> (Admin Panel -> Settings -> User Settings), Enable "Require registration and login to create tickets"

<h3>5.</h3> (Admin Panel -> Agents -> Add New), Create two new agents: John and Jane

<h3>6.</h3> (Agent Panel -> Users -> Add New), Create two new users: Karen and Ken 

<h3>7.</h3>(Admin Panel -> Manage -> SLA) Create the folloing Service Level Agreements:

- Sev-A (1 hour, 24/7)
- Sev-B (4 hours, 24/7)
- Sev-C (8 hours, business hours)

<h3>8.</h3> (Admin Panel -> Manage -> Help Topics) Create the following help topics:

- Business Critical Outage
- Personal Computer Issues
- Equipment Request
- Password Reset





