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

Configure Roles, Departments & Teams
Allow Users to Create Tickets
Configure Users
Configure SLA
Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src=![image](https://user-images.githubusercontent.com/117492330/210661764-1df650dd-6e4b-4c35-963d-618abd808b77.png)</p>
<p>
Log into the OsTicket browser and make sure you are on the "admin panel" (note if it shows "agent panel" up top then you are currently in the admin panel and vice versa) reference picture # 1. Click agents --> roles --> add new role --> create a "super admin" whom can do every task and has all permissions/access. This process will need to be repeated to perform the next two steps which are: configuring the departments & teams (create a "System Administrators department" & "level II Support team"). Please reference screenshots above.</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create two new test agents ("John Doe" and "Jane Doe")--> Assign John to "System Administrators" department with "Super admin" permissions level & add him to "Level II support" team. All of these options are located under the "access & Teams" tabs on the same agent screen. Next add "Jane Doe" the same way as previously completed for John Doe. Please reference pictures above that are in order.</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The last step is to configure "help topics". In this step you will create the help ticket names in OsTicketing for users to select when they are having specific issues. The tickets will also need to be assigned to a "department" along with a "SLA priority". You can even auto-assign that particular help desk ticket topic to a group like "Support level I" or level II depending on the severity. Ex: create ticket help topic titled "Network Outage" --> priority level "emergency" --> "Service level I" SLA plan --> sent to the "System Administrators" group --> auto-assigned to the "support team" or to an individual agent like John or Jane. This concludeds how to setup help desk support tickets from the admin level post Installation.</p>
