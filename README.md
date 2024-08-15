<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
  
![image](https://github.com/user-attachments/assets/04ca254a-7b20-4c46-9c7f-a29fe692d88f)
![image](https://github.com/user-attachments/assets/80e5d013-f164-4cbc-92a2-f6471f30c3d6)
![image](https://github.com/user-attachments/assets/e3bd6f24-0f1b-4461-9262-a529a7165078)
![image](https://github.com/user-attachments/assets/7a0d3fc7-0234-4768-bf26-e9af703a6341)



</p>
Use the following link to take you to the end user's osTicket page to create three tickets - http://localhost/osTicket/. The first ticket will be from Karen Smith, under the help topic "Business Critical Outage". The summary is Online Banking is Down and the text will read "There have been reports of customers getting a 404 error when trying to access online banking". The second ticket will be from Ken Smith under the help topic "Personal Computer Issues". The summary will be "Adobe reader not working" and the text will read "The accounting department is having issues with their adobe readers". The third ticket will be from Ken Smith under the help topic "General Inquiry". The summary is "When are we getting a hardware refresh" and the text will read "Our department is having issues with our tablets. They are running very slow and I'm curious as to when we're getting a hardware refresh".

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/8f6c7653-2e7e-4123-89cc-0d163657cdf0)
![image](https://github.com/user-attachments/assets/14a05f43-ea3d-4b5a-8bee-de4bb72aa3e5)

</p>
<p>
Log into osTicket with the account we created for Jane using the username and password you selected. In this case, the username is Jane-Doe. Once logged in, you will be able to see the tickets that were created. If you're not able to see the tickets, be sure Jane has access to the support department. 
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/72b42768-f0ff-4830-b91c-50cf72261a62)
![image](https://github.com/user-attachments/assets/bd67d6a7-b42c-430b-b1bf-a5ede5469a6a)
![image](https://github.com/user-attachments/assets/7cc82b1d-37d3-41ef-a168-a2858f47dd0f)
![image](https://github.com/user-attachments/assets/de404717-3641-456c-a565-9e2b636e499b)
![image](https://github.com/user-attachments/assets/08e5860e-e35b-41bb-921e-36ac1371bbcf)


</p>
<p>
Click the firt ticket we created (Online Banking is Down), and make a couple adjustments. Since it's a business impacting event, change the priority to emergency, change the department to System Administrators, assign it to Jane Doe, and change the SLA to SEV-A. Scroll down and reply "Working with system administrators to get mobile banking online". Go back to Tickets and you should see "Priority" and "Assigned To" filled out. Click on the ticket again and reply "Scott corrected a load balancer and resolved the issue. Mobile banking is running again". Be sure to set the Ticket Status to "Resolved" and click post reply. Once resolved, the ticket moves from open ticket to closed tickets and should no longer be displayed on the open ticket screen. 
</p>
<br />

![image](https://github.com/user-attachments/assets/393b807d-3b86-4e3e-98ce-9c131fc5c3d9)
![image](https://github.com/user-attachments/assets/c080d047-2aa1-489a-9412-b8ef70d61d28)
![image](https://github.com/user-attachments/assets/8bd70043-4139-4d05-b900-6b716c06f8aa)
![image](https://github.com/user-attachments/assets/d124679f-7f4e-409e-acd4-1e6c1f49c06b)

Next, click on the second ticket we created, Adobe Reader Not Working. Since it's affecting the entire accounting department, change the priority to high, change the SLA plan to SEV-B, and assign it to John Doe. While logged in as Jane, post the reply "Reassigned to SEV-B, changed priority level to high since it's affecting the whole accounting department. Reached out to John for a warm hand off". Log out of osTicket and log back in as John using the username John-Doe and the password you created when making his account. Now that you're logged in as John, click on the ticket assigned to you, reply "Your Adobe reader was upgraded last night. We downgraded them to the previous version for now and they are back up and running. For the time being, I will look into why the upgrade did not work on the accounting department's hardware", and change the ticket status to resolved. 

![image](https://github.com/user-attachments/assets/cb4f1bd6-4ece-43e7-93d4-4e6a11e42439)

![image](https://github.com/user-attachments/assets/94cfbd2f-23df-4875-8dfb-e429de460fc9)



Now that John no longer has any open tickets, log back in as Jane using the username Jane-Doe and the password you created when making her account, and click on the last ticket we made, "When are we getting a hardware refresh". Change the priority to low, assign it to Jane Doe, and change the SLA plan to SEV-C. Type the reply "Hardware refresh is slated for quarter 1. When you get a moment, send me an email and we can test the new units". Change the ticket status to resolved and close the ticket. This will clear out all 3 tickets that we have created. Practice making tickets, assigning the right priority, agent and SLA, and working the ticket as the agent assigned to it.

***Be sure to delete your virtual machines in Azure at the end of the tutorial so you don't have to pay for something you're not using***
