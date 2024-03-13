<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket. Agent Layla will resolve tickets.<br />

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

<h2>Resolutions by Priority</h2>

We'll log in as the Agent Jane Doe and set the correct priority to the tickets as shown in the table below.


Help Topic  | Priority
------------- | -------------
Business Critical Outage  | Emergency
Personal Computer Issues  | High
Equipement Request        | Normal
Password Reset            | Least

Once you log in as Jane, you should see this with all priority set to normal. Let's take a look at the mobile online banking issue. 

![image](https://github.com/riquewill1977/osticket-lifecycle/assets/139101776/65dd4724-ef9d-4af7-b3d2-62a27a5915c5)

Update the the following on the ticket.


- Priority to Emergency
- Department to System Administrators
- Assigned to Jane Doe
- SLA Plan to SLA-A


![image](https://github.com/riquewill1977/osticket-lifecycle/assets/139101776/52be9ee3-2fc1-4dd8-8dc8-1af89d3c547d)

Scroll to the bottom of the ticket and post a reply stating that you'll be coordinating with the Sys Admin Team. 

Leave the ticket status as "open" and click post reply.

![image](https://github.com/riquewill1977/osticket-lifecycle/assets/139101776/f8fe1788-a976-4ecf-a427-c994e335720a)

We now see in the list of open tickets that the ticket now has a priority of "Emergency" and Assigned To "Jane Doe"

![image](https://github.com/riquewill1977/osticket-lifecycle/assets/139101776/c73de4de-3dd2-484a-ad3e-9096f1170939)

We can go back in and pretend that we took care of the ticket. Set the ticket to "resolved" and post.

![image](https://github.com/riquewill1977/osticket-lifecycle/assets/139101776/d9b473a1-e080-4cfd-8af4-5c1f4fd8cd60)

The ticket has now been removed from the list "Open" tickets to "Closed"

![image](https://github.com/riquewill1977/osticket-lifecycle/assets/139101776/7a766e10-0c36-49cc-a016-529c06e0a070)

Repeat the steps by assigning the correct priorities, department, assigned to and SLA plan to each ticket. 















