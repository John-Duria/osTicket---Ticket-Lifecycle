<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

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

Tickets and Ticket Lifecycle in osTicket
1. Creating Tickets
•	Navigate to the Ticket Creation Page:
o	Access the end-user osTicket URL: http://localhost/osTicket/.
o	Select Open a New Ticket.
o	Fill in the required details for the ticket:
	Ticket Title: Brief description of the issue.
	Ticket Details: Detailed description of the problem or request.
	Department: Select the appropriate department (e.g., System Administrators, Accounting, IT Support).
	Help Topic: Choose the relevant help topic (e.g., Business Critical Outage, Software Issue, Hardware Request).
	Priority: Set the priority based on severity (e.g., Sev-A, Sev-B, Sev-C).

2. Ticket Examples
a. Sev-A (1 hour, 24/7) - Entire Mobile/Online Banking System is Down
•	Create Ticket:
o	Title: "Urgent: Mobile/Online Banking System Down"
o	Details: "The entire mobile and online banking system is inaccessible."
o	Department: System Administrators
o	Help Topic: Business Critical Outage
o	Priority: Sev-A (1 hour response, 24/7 coverage)

![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/4549e4e5-ddb9-4c57-80f1-3b964131596b)

b. Sev-B (4 hours, 24/7) - Accounting Department Needs Adobe Upgrade, Broken
•	Create Ticket:
o	Title: "Adobe Reader not working for Accounting Department"
o	Details: "The Adobe software in the accounting department is broken and needs an urgent upgrade."
o	Department: IT Support or Application Support
o	Help Topic: Software Issue
o	Priority: Sev-B (4 hours response, 24/7 coverage)

![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/569c0137-3a72-4fa4-868f-50a22e621a28)

c. Sev-B/C (2 hours, Business Hours) - CFO’s Laptop Seems Slow
•	Create Ticket:
o	Title: "Hardware Refresh"
o	Details: "The CFO's laptop is experiencing slow performance."
o	Department: IT Support
o	Help Topic: Hardware Issue
o	Priority: Sev-B/C (2 hours response during business hours)

![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/2ca723bd-fb4f-46f5-84d7-ab029e0385fc)

3. Triaging and Managing Tickets
•	Triage Tickets Based on Priority and Severity:
o	As tickets are created, assign them to the appropriate teams or agents based on severity and department.
o	Monitor the ticket queue regularly to ensure high-priority tickets (Sev-A) are addressed promptly.
Urgent: Mobile/Online Banking System Down
 
![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/910b8d9c-04a0-4e4e-aaec-84d685b2618d)

![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/00d1d491-f308-4a53-aa61-fae89bbe9d21)

Adobe Reader not working for Accounting Department

![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/7cac39b1-742b-4d69-89cd-ee718a3e0396)

![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/4efb2d00-496b-44fd-851e-09c7e0cca564) 

Hardware Refresh

![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/977c2c2b-eccd-491a-8cd0-81fb9ea0e513)

![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/c9c8e0e6-a769-4052-b37a-b10df954f580)

4. Ticket Lifecycle
•	Resolve and Close Tickets:
o	After troubleshooting and resolving the reported issues, update the ticket status and add any necessary notes or comments.
o	Communicate with users/customers to confirm issue resolution and close the ticket accordingly.

