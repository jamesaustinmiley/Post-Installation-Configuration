<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Configuration</h1>
This tutorial outlines the post-installation configuration of the open-source help desk ticketing system osTicket. OsTicket is used to manage both internal and external requests via e-mail, phone, or the company website. These requests are then converted into tickets that can be tracked and completed. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure 
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11 Pro</b> (25H2)

<h2>Configuration Steps</h2>

<p>
Log in to the osTicket ticketing system, using your Admin username and password from the osTicket installation earlier. This will allow you to act as a helpdesk administrator/analyst, handling end-user tickets through to completion or assigning them to the appropriate individuals or groups as needed. Once you log in, you will be able to act as Admin or as an Agent. As an Admin, you can configure settings on the backend of osTicket and route tickets to individuals or groups. Clicking on the Admin panel will take you to the System Settings and Preferences page. As an Agent, you will either work on a ticket to completion or pass it on to a higher level. Clicking on the Agent panel will take you to the Tickets page.
</p>
<p>
<img src="https://imgur.com/aS5uNc5.png" alt="Admin/Analyst Login"/>
</p>
<p>
<img src="https://imgur.com/dmh1tmr.png" alt="Administrator"/>
</p>
<p>
<img src="https://imgur.com/upedP3z.png" alt="Agent"/>
</p>
<br />

<p>
In osTicket, Roles define what an agent is allowed to do within the help desk. As an Administrator, you can manage the available roles and even add new ones. When adding a new role, you decide what an agent can do regarding tickets, tasks, and the knowledge base. Create a new role named Supreme Admin and give it full access.
</p>
<p>
<img src="https://imgur.com/dRNtDFL.png" alt="Add New Role"/>
</p>
<p>
<img src="https://imgur.com/Qg4BUK5.png" alt="Tickets"/>
</p>
<p>
<img src="https://imgur.com/HNzsUkY.png" alt="Tasks"/>
</p>
<p>
<img src="https://imgur.com/YtVsvGA.png" alt="Knowledgebase"/>
</p>
<p>
<img src="https://imgur.com/Ef4ad2D.png" alt="Supreme Admin"/>
</p>
<br />

<p>
In osTicket, Departments represent a specific group or responsibility area and control which agents handle which tickets in the help desk. Each ticket is typically assigned to a single department, which determines who can view, work on, and manage it. As an Administrator, you can manage the available departments and add new ones. When adding a new department, you configure the settings and decide which agents have access. Create a new department named SysAdmins. In Settings, ensure that SysAdmins is a Top-Level Department rather than a Support Department.
</p>
<p>
<img src="https://imgur.com/8yTOp5o.png" alt="Settings"/>
</p>
<p>
<img src="https://imgur.com/yaEHJpr.png" alt="Access"/>
</p>
<p>
<img src="https://imgur.com/LtgtN2Q.png" alt="SysAdmins"/>
</p>
<br />

<p>
In osTicket, Teams are specialized groups that can involve agents from multiple departments. A ticket can be assigned to a team instead of a single agent or department. As an Administrator, you can manage team information and members. Create a new team named Online Banking. 
</p>
<p>
<img src="https://imgur.com/v8Ekero.png" alt="Team"/>
</p>
<p>
<img src="https://imgur.com/WQqgex4.png" alt="Members"/>
</p>
<p>
<img src="https://imgur.com/qRSiwUF.png" alt="Online Banking"/>
</p>
<br />

<p>
In osTicket, Users are the clients/end-users who submit tickets. Agents are staff members who respond to tickets and work them to completion. As an Administrator, you can add new users and decide who gets to create tickets. Also, you can add new agents and manage their account, their level of access, their permissions, and what teams they are a part of. Add two new users (Karen and Ken) and two new agents (Jane and John). 
</p>
<p>
<img src="https://imgur.com/2i0qGnK.png" alt="Users Settings"/>
</p>
<p>
<img src="https://imgur.com/7s948qA.png" alt="New User"/>
</p>
<p>
<img src="https://imgur.com/hLGuElY.png" alt="Agent Account"/>
</p>
<p>
<img src="https://imgur.com/XCp3uOh.png" alt="Agent Access"/>
</p>
<p>
<img src="https://imgur.com/aWkkGj2.png" alt="Agent Permissions"/>
</p>
<p>
<img src="https://imgur.com/ThxCgHs.png" alt="Agent Assigned Teams"/>
</p>
<p>
<img src="https://imgur.com/BfiUNC3.png" alt="Agents"/>
</p>
<br />

<p>
In osTicket, Service Level Agreements determine how quickly an agent will respond to a ticket, how quickly the issue will be resolved, and whether the ticket will be worked only during business hours or 24/7. As an Administrator, you can add or edit SLA plans. Add three new SLA plans (Sev-A, Sev-B, and Sev-C).
</p>
<p>
<img src="https://imgur.com/xi33Sbr.png" alt="Sev-A"/>
</p>
<p>
<img src="https://imgur.com/FpNcl6d.png" alt="Sev-B"/>
</p>
<p>
<img src="https://imgur.com/XngAkYP.png" alt="Sev-C"/>
</p>
<p>
<img src="https://imgur.com/yJ31aas.png" alt="SLAs"/>
</p>
<br />

<p>
In osTicket, Help Topics are used to categorize tickets when users create them. They will select the help topic associated with their issue, which will route the ticket to the destination where it is most likely to be resolved. As an Administrator, you can add new help topics and edit existing ones. Add five new help topics (Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset, and Other).
</p>
<p>
<img src="https://imgur.com/Aq1exSm.png" alt="Business Critical Outage"/>
</p>
<p>
<img src="https://imgur.com/NwBj8jo.png" alt="Personal Computer Issues"/>
</p>
<p>
<img src="https://imgur.com/hYP2cqO.png" alt="Equipment Request"/>
</p>
<p>
<img src="https://imgur.com/nmh2tNW.png" alt="Password Reset"/>
</p>
<p>
<img src="https://imgur.com/vheWGL3.png" alt="Other"/>
</p>
<p>
<img src="https://imgur.com/FhjSDbN.png" alt="New Help Topics"/>
</p>
