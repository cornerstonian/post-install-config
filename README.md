<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
Outline of the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Teams and Departments
- Configure Agents
- Configure SLA's (Service Level Agreements)
- Create Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/H9DTVz7.png" height="80%" width="80%"/>
</p>

- To configure roles, go to: Admin Panel > Agents > Roles. Add role. Name it and enable all ticket permissions.

<br />

<p>
<img src="https://imgur.com/ogWjh9v.png" height="80%" width="80%" />
</p>

- Go to Admin Panel > Agents > Departments, Name the department and select a manager.
- Click "Creat Dept".
- Next, go to Admin Panel -> Agents -> Teams.
- Select "Add team".
- Name it "Level II Support" and add member by clicking on "Members" tab.
- Go to Admin Panel > Settings > User Settings to make sure that the registration required box is not checked.

<br />

<p>
<img src="https://imgur.com/6ti0sw3.png" height="80%" width="80%" />
</p>

- Go to Admin Panel -> Agents and click "Add new agent".
- Create name and email.
- Press the set password button.
- Deselect the "Send the agent a password reset" box and create a password.
- Deselect the "require password change" box and press "set".
- Click on "Access" tab and select "System Administrators".
- Also select the created department. In extended access below, select the department and add "support" department as well.
- Next, click on "teams" tab and select the created team.
- Click "Create".
- Add another agent with limited permissions.
- To create users, go to Agent Panel > Users > and click on "Add user".
- Create name, email and password.
- Click "Add User".

<br />

<p>
<img src="https://imgur.com/WOJIkON.png" height="80%" width="80%" >
</p>

- Go to Admin Panel > Manage > SLA and click "add new SLA plan". 
- Place these settings for Sev-A: (1 hour, 24/7). 
- Sev-B will be (4 hours, 24/7)
- Sev-C will be (8 hours, Monday - Friday).

<br />

<p>
<img src="https://imgur.com/Yrn8D9e.png" height="80%" width="80%"/>
</p>

- Go to Admin Panel > Manage > Help Topics and click "Add help topic".
- Title the first one "Business Critical Outage", the second "Personal Computer Issues", the third "Equipment Request", and lastly "Password Reset".
- Log into the user portal of osTicket at: http://localhost/osTicket/.
- Use a created user to create tickets.


<br />

<h2 align="center"> OsTicket is now configured and ready for tickets. 🎉 </h2>
