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
Log in to the osTicket ticketing system admin/analyst page, using your Admin username and password from the osTicket installation earlier. 
</p>
<p>
<img src="https://imgur.com/qlM9xap.png" alt="Admin/Analyst Link"/>
</p>
<p>
<img src="https://imgur.com/qbb1WUZ.png" alt="Admin/Analyst Login"/>
</p>
<p>
Switch from the Agent panel to the Admin panel. An Agent can only work tickets whereas an Administrator has full control over system configuration. 
</p>
<p>
<img src="https://imgur.com/tklh7u2.png" alt="Agent to Admin"/>
</p>
<br />

<p>
In osTicket, Roles define what an agent is allowed to do within the help desk. As an Administrator, you can manage the available roles and even add new ones. 
</p>
<p>
<img src="https://imgur.com/PEV6s2l.png" alt="Roles"/>
</p>
<p>
<img src="https://imgur.com/7dwoDGC.png" alt="Add New Role"/>
</p>
<p>
Add a new role, named Supreme Admin, and give it full permissions with regards to tickets, tasks, and the knowledgebase. 
</p>
<p>
<img src="https://imgur.com/XnxASEJ.png" alt="Supreme Admin"/>
</p>
<p>
<img src="https://imgur.com/0JwhLdH.png" alt="Tickets"/>
</p>
<p>
<img src="https://imgur.com/gbOHZUY.png" alt="Tasks"/>
</p>
<p>
<img src="https://imgur.com/gDJ1ymF.png" alt="Knowledgebase"/>
</p>
<p>
<img src="https://imgur.com/qnkSFoV.png" alt="New Role"/>
</p>
<br />

<p>
In osTicket, Departments represent a specific group or responsibility area and control which agents handle which tickets in the help desk. They are the primary way tickets are organized and assigned. As an Administrator, you can manage the available departments and add new ones. 
</p>
<p>
<img src="https://imgur.com/J58lOTJ.png" alt="Departments"/>
</p>
<p>
<img src="https://imgur.com/HkFnjFn.png" alt="Add New Department"/>
</p>
<p>
Create a new department named SysAdmins. In Settings, ensure that SysAdmins is a Top-Level Department rather than a Support Department.
</p>
<p>
<img src="https://imgur.com/y21Nl2W.png" alt="SysAdmins"/>
</p>
<p>
<img src="https://imgur.com/BDh7oWZ.png" alt="New Department"/>
</p>
<br />

<p>
In osTicket, Teams are specialized groups that can involve agents from multiple departments. As an Administrator, you can manage the available teams and add new ones. 
</p>
<p>
<img src="https://imgur.com/aoX6mOs.png" alt="Teams"/>
</p>
<p>
<img src="https://imgur.com/hqpS7iT.png" alt="Add New Team"/>
</p>
<p>
Create a new team named Online Banking. 
</p>
<p>
<img src="https://imgur.com/QkmZd3Z.png" alt="Online Banking"/>
</p>
<p>
<img src="https://imgur.com/CWWuWBj.png" alt="New Team"/>
</p>
<br />

<p>
In osTicket, Users are the clients/end-users who submit tickets. Allow all users to create tickets by unchecking the Registration Required box in the Users Settings section. 
</p>
<p>
<img src="https://imgur.com/ym1LG1i.png" alt="Users Settings"/>
</p>
<p>
In osTicket, Agents are staff members who respond to tickets and work them to completion. As an Administrator, you can manage agent accounts and add new agents.
</p>
<p>
<img src="https://imgur.com/0irM00R.png" alt="Agents"/>
</p>
<p>
<img src="https://imgur.com/WwXbi61.png" alt="Add New Agent"/>
</p>
<p>
Add Jane Doe as a new agent. 
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
