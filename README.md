<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Installation Setup</h1>
This tutorial outlines the post installation steps necessary to access osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Part 2: Post Installation Steps</h2>

- Configure Roles:
  - Access Admin Panel -> Agents -> Roles.
  - Set as Supreme Admin.

- Configure Departments:
  - Access Admin Panel -> Agents -> Departments.
  - Establish System Administrators.

- Configure Teams:
  - Access Admin Panel -> Agents -> Teams.
  - Set up Level I Support and Level II Support.

- Allow anyone to create tickets:
  - Access Admin Panel -> Settings -> User Settings.
  - Enable "Registration Required": Require registration and login to create tickets.

- Configure Agents (workers):
  - Access Admin Panel -> Agents -> Add New.
  - Add Jane and John.

- Configure Users (customers):
  - Access Agent Panel -> Users -> Add New.
  - Add Karen and Ken.

- Configure SLA:
  - Access Admin Panel -> Manage -> SLA.
  - Define Service Level Agreements:
    - Sev-A (1 hour, 24/7).
    - Sev-B (4 hours, 24/7).
    - Sev-C (8 hours, business hours).

- Configure Help Topics:
  - Access Admin Panel -> Manage -> Help Topics.
  - Set up categories such as Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset.
