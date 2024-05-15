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

- Log In
- Roles Configuration
- Departments Configuration
- Teams Configuration
- Ticket Creation Access
- Agent Configuration
- Users Configuration
- SLA Configuration
- Help Topics Configuration
  
<h2>Log In</h2>

<p>
<img src="https://i.imgur.com/husvoxy.png"/>
</p>
<p>
Log into Osticket with Username and Password. <br /> <br />
Select "Admin Panel". <br /> <br />
</p>
<br />

<h2> Roles Configuration </h2>

<p>
<img src="https://i.imgur.com/GH0qam7.png"/>
</p>
<p>
Select "Agents". <br /> <br />
Select "Roles". <br /> <br />
Select "+ Add New Role". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/3k1VU6Z.png"/>
</p>
<p>
Name: Select desired name, for this tutorial we will be using "Supreme Admin".
</p>
<br />

<p>
<img src="https://i.imgur.com/1pBA4II.png"/>
</p>
<p>
Check all the boxes for Tickets, Tasks, and Knowledgebase.
</p>
<br />

<p>
<img src="https://i.imgur.com/0fHpGTd.png"/>
</p>
<p>
Click "Add Role".
</p>
<br />

<p>
<img src="https://i.imgur.com/FCAuiTl.png"/>
</p>
<p>
"Supreme Admin" role has been successfully been added to roles. <br /> <br />
Select "Departments". <br /> <br />
</p>
<br />

<h2> Department Configuration </h2>
<p>
<img src="https://i.imgur.com/XOK7IbG.png"/>
</p>
<p>
Click "+ Add New Department"
</p>
<br />

<p>
<img src="https://i.imgur.com/KqKn25R.png"/>
</p>
<p>
Name: Select desired name, for this tutorial we will be using "System Administators".
</p>
<br />

<p>
<img src="https://i.imgur.com/CE0DzOM.png"/>
</p>
<p>
Select "Access". <br /> <br />
Select "Create Dept". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/rIdg3cC.png"/>
</p>
<p>
System Administators has been successfully added to Departments.
</p>
<br />

<h2> Teams Configuration </h2>
<p>
<img src="https://i.imgur.com/f39MxdQ.png"/>
</p>
<p>
Select "Teams". <br /> <br />
Select "+ Add New Team". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/S4Aebdm.png"/>
</p>
<p>
Name: Select desired name, for this tutortial we will be using "Level II Support".
</p>
<br />

<p>
<img src="https://i.imgur.com/twXrjKn.png"/>
</p>
<p>
Select "Members". <br /> <br />
Select "Create Team". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/DwKRt5Z.png"/>
</p>
<p>
Level II Support has been added to Team Group.
</p>
<br />

<h2> Ticket Creation Access </h2>
<p>
<img src="https://i.imgur.com/yzxtNNs.png"/>
</p>
<p>
Go to "Settings". <br /> <br />
Select "Users". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/RvV6kOj.png"/>
</p>
<p>
Select "User settings".
</p>
<br />

<p>
<img src="https://i.imgur.com/ystzTGM.png"/>
</p>
<p>
Uncheck "Registration Required". <br /> <br />
Click "Save Changes". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/vYs2WMg.png"/>
</p>
<p>
User Settings has successfully been updated.
</p>
<br />

<h2> Agent Configuration </h2>
<p>
<img src="https://i.imgur.com/MqFkdrR.png"/>
</p>
<p>
Go to "Agents".
</p>
<br />

<p>
<img src="https://i.imgur.com/lflkTD5.png"/>
</p>
<p>
Select "+ Add New Agent".
</p>
<br />

<p>
<img src="https://i.imgur.com/c2zg5n4.png"/>
</p>
<p>
Name: Select desired name, for this tutorial we will be using "Jane Doe". <br /> <br />
Email address: Select the desired email address, for this tutorial we will be using "jane.doe@easyit.com". <br /> <br />
Username: Select the desired username, for this tutorial we will be using "Jane.Doe". <br /> <br />
Select "Set Password". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/FDRzJld.png"/>
</p>
<p>
Uncheck "Send the agent a personal rest email". <br /> <br />
Create Password. <br /> <br />
Re-Enter Password. <br /> <br />
Uncheck "Require password change at next login". <br /> <br />
Select "Set". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/KraH8db.png"/>
</p>
<p>
Select "Access". <br /> <br />
Select Role as "Supreme Admin". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/TCKld6C.png"/>
</p>
<p>
Select "Teams". <br /> <br />
Select "Create". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/rasLB1n.png"/>
</p>
<p>
Jane Doe has successfully been added to the Agents Group. <br /> <br />
Select "+Add New Agent". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/cU9u8Z5.png"/>
</p>
<p>
Name: Select the desired name, for this tutorial we will be using John Doe. <br /> <br /> 
Email Address: Select the desired email address, for this tutorial we will be using "john.doe@easyit.com. <br /> <br /> 
Username: John.Doe. <br /> <br /> 
Select "Set Password". <br /> <br /> 
</p>
<br />

<p>
<img src="https://i.imgur.com/VAv8EHE.png"/>
</p>
<p>
Uncheck "Send the agent a password rest email". <br /> <br />
Create Password. <br /> <br />
Re-enter Password. <br /> <br />
Uncheck "Require password change at next login". <br /> <br />
Select "Set". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/RKs0DdY.png"/>
</p>
<p>
Select "Access". <br /> <br />
Select Role as "Supreme Admin". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/yWJ80Ri.png"/>
</p>
<p>
Select "Teams". <br /> <br />
Select "Create". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/0sUt6Lk.png"/>
</p>
<p>
John Doe has successfully been added to the Agents Group. <br /> <br />
A list of all the Agents are present at the Agents Home Page. <br /> <br />
</p>
<br />

<h2> Users Configuration </h2>
<p>
<img src="https://i.imgur.com/ERTIJkb.png"/>
</p>
<p>
Go to "Agents Panel".
</p>
<br />

<p>
<img src="https://i.imgur.com/b7Tji7v.png"/>
</p>
<p>
Select "Users".
</p>
<br />

<p>
<img src="https://i.imgur.com/gnaeztp.png"/>
</p>
<p>
Select "+Add User".
</p>
<br />

<p>
<img src="https://i.imgur.com/eXvMSKW.png"/>
</p>
<p>
Email Address: Select desired email address, for this tutorial we will be using "Karen.Palmer@easyit.com". <br /> <br />
Full Name: Select desired name, for this tutorital we will be using "Karen Palmer". <br /> <br />
Select "Add User". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/FOyWdDp.png"/>
</p>
<p>
Karen Palmer has successfully been created as a User.
</p>
<br />

<p>
<img src="https://i.imgur.com/M9gDb21.png"/>
</p>
<p>
Select "Users". <br /> <br />
Select "+ Add User". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/HFJXtgv.png"/>
</p>
<p>
Email Address: Select desired email address, for this tutorial we will be using "Ken.Jobs@ easyit.com". <br /> <br />
Full Name: Select desired name, for this tutorial we will be using "Ken Jobs". <br /> <br />
Select "Add User". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/zcz0Id0.png"/>
</p>
<p>
Ken Jobs has successfully been created as a User.
</p>
<br />

<p>
<img src="https://i.imgur.com/SnWKAeT.png"/>
</p>
<p>
All of the current Users have been added to the User Directory.
</p>
<br />

<h2> SLA Configuration </h2>
<p>
<img src="https://i.imgur.com/7cv22Ph.png"/>
</p>
<p>
Select "Admin Panel". <br /> <br />
Select "Manage". <br /> <br />
Select "SLA". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/DwG8CuG.png"/>
</p>
<p>
Select "+ Add New SLA Plan".
</p>
<br />

<p>
<img src="https://i.imgur.com/oPRkmJl.png"/>
</p>
<p>
Name: Select the desired name, for this tutorial we will be using "Sev A". <br /> <br />
Grace Period: Select the desired time, for this tutorial we will be using "1 (in hours)". <br /> <br />
Schedule: Select the desired schedule, for this tutorial we will be using "24/7". <br /> <br />
Select "Add Plan". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/HQ8TII2.png"/>
</p>
<p>
Sev A SLA Plan has been add to SLA Group. <br /> <br />
Select "+ Add New SLA Plan". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/Hmnn7ns.png"/>
</p>
<p>
Name: Select desired name, for this tutorial we will be using "Sev B". <br /> <br />
Grace Period: Select the desired time, for this tutorial we will be using "4 (in hours)". <br /> <br />
Schedule: Select the desired schedule, for this tutorial we will be using "24/7". <br /> <br />
Select "Add Plan". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/1BXDfJ5.png"/>
</p>
<p>
Sev B SLA Plan has been added to SLA Group. <br /> <br />
Select "+ Add New SLA Plan". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/oakKS56.png"/>
</p>
<p>
Name: Select the desired name, for this tutorial we will be using "Sev C". <br /> <br />
Grace Period: Select the desired time, for this tutorial we will be using "8 (in hours)". <br /> <br />
Schedule: Select the desired schedule, for this tutorial we will be using " Monday-Friday 8 am -5pm with US Holidays". <br /> <br />
Select "Add Plan". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/B9lDuNf.png"/>
</p>
<p>
Sev C has been added to the SLA group. <br /> <br />
All current SLA Plans are shown on the SLA Home Page. <br /> <br />
</p>
<br />

<h2> Help Topics Configuration </h2>
<p>
<img src="https://i.imgur.com/3GYfDz2.png"/>
</p>
<p>
Select "Help Topics". <br /> <br />
Select "+ Add New Help Topic". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/ZXwJDWq.png"/>
</p>
<p>
Topic: Select the desired topic name, for this tutorial we will be using "Business Critical". <br /> <br />
Select "Add Topic". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/q9LA2za.png"/>
</p>
<p>
Business Critical has been added to Help Topics Group. <br /> <br />
Select "+ Add New Help Topic". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/yAajVv8.png"/>
</p>
<p>
Topic: Select desired topic name, for this tutorial we will be using "Personal Computer Issues". <br /> <br />
Select "Add Topic". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/5bWn1mJ.png"/>
</p>
<p>
Personal Computer Issues has been added to the Help Topic Group. <br /> <br />
Select "+ Add New Help Topic". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/gptyxWl.png"/>
</p>
<p>
Topic: Select desired topic name, for this tutorial we will be using "Equipment Request". <br /> <br />
Select "Add Topic". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/uVb2JDm.png"/>
</p>
<p>
Equipment Request has been added to Help Topics Group. <br /> <br />
Select "Add New Help Topic". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/jNipYnz.png"/>
</p>
<p>
Topic: Select desired topic name, for this tutorial we will be using "Password Reset". <br /> <br />
Select "Add Topic". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/UvYalBg.png"/>
</p>
<p>
Password Reset has been added to Help Topic Group. <br /> <br />
All current Help Topics are shown on the Help Topics Home Page. <br /> <br />
Congratulations you have completed this tutortial! <br /> <br />
</p>
<br />


