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

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure osticket roles (admin, helpdesk agent, etc)
- Configure department
- Configure service level aggreement (SLA)
- Configure help topic

<h2>Configuration Steps</h2>

<h4>Create an admin with highest level of permission then using the same process to create help desk agents</h4>

- Admin Panel -> Agents -> Roles
  
<br />

![os1](https://github.com/edem4963/post-install-config/assets/112492837/a94ae493-e5da-4a6c-8650-f31ecb6c582a)

<br />

<h4>Create different department for organizing the help ticket(accounting, legal, etc), or if the department has a specific service level agreement</h4>

- Admin Panel -> Agents -> Departments
  
<br />

![os2](https://github.com/edem4963/post-install-config/assets/112492837/3e6a8274-5497-42bf-b355-8a400be733f2)

<h4>Create a team of help desk agent. Teams are great for grouping help desk agent with similar level. For example, L1 agent for easy task and L4 for more difficult troubleshooting.</h4>

- Admin Panel -> Agents -> Teams
  
<br />

![os3](https://github.com/edem4963/post-install-config/assets/112492837/a8c39bcf-19c3-4f2d-983c-6b522fedf8df)

<br />

<h4>Create service-level agreement(SLA). The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed.</h4>

- Admin Panel -> Manage -> SLA

<br />

![os4](https://github.com/edem4963/post-install-config/assets/112492837/396d214b-5794-4193-a000-20bdea761b19)

<br />

<h4>Create help topics. Help Topics will help streamline your end-user’s help desk experience to ensure proper assignment and prompt response to the ticket.</h4>

- Admin Panel -> Manage -> Help Topics

<br />

![os5](https://github.com/edem4963/post-install-config/assets/112492837/857de770-98da-4995-ad43-2ce8f52a7c49)

<br />

<h2>Congrat!! Following the step above you have a basic understanding of the duties of a system administrator within osticket ecosystem.</h2>
