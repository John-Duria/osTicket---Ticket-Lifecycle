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

<h2>Tickets and Ticket Lifecycle in osTicket</h2>

INTAKE

   •	Creating Tickets
    
    • Navigate to the Ticket Creation Page:
    • Access the end-user osTicket URL: http://localhost/osTicket/.
    • Select Open a New Ticket.
    • Fill in the required details for the ticket:
        o	Ticket Title: Brief description of the issue.
        o	Ticket Details: Detailed description of the problem or request.
        o	Help Topic: Choose the relevant help topic (e.g., Business Critical Outage, Software Issue, Hardware Request).

Ticket Examples

A. Sev-A (1 hour, 24/7) - Entire Mobile/Online Banking System is Down

    o Title: "Urgent: Mobile/Online Banking System Down"
    o Details: "The entire mobile and online banking system is inaccessible."
    o Help Topic: Business Critical Outage

![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/4549e4e5-ddb9-4c57-80f1-3b964131596b)

B. Sev-B (4 hours, 24/7) - Accounting Department Needs Adobe Upgrade, Broken

    o Title: "Adobe Reader not working for Accounting Department"
    o Details: "The Adobe software in the accounting department is broken and needs an urgent upgrade."
    o Help Topic: Software Issue

![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/569c0137-3a72-4fa4-868f-50a22e621a28)

C. Sev-B/C (2 hours, Business Hours) - CFO’s Laptop Seems Slow

    o Title: "Hardware Refresh"
    o Details: "The CFO's laptop is experiencing slow performance."
    o Help Topic: Hardware Issue

![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/2ca723bd-fb4f-46f5-84d7-ab029e0385fc)

ASSIGNMENT AND COMMUNICATION

•	Triage Tickets Based on Priority and Severity:

    o As tickets are created, assign them to the appropriate teams or agents based on severity and department.
    o Monitor the ticket queue regularly to ensure high-priority tickets (Sev-A) are addressed promptly.
 
Ticket Examples

A. Sev-A (1 hour, 24/7) - Entire Mobile/Online Banking System is Down
 
![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/910b8d9c-04a0-4e4e-aaec-84d685b2618d)

B. Sev-B (4 hours, 24/7) - Accounting Department Needs Adobe Upgrade, Broken

![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/7cac39b1-742b-4d69-89cd-ee718a3e0396)

C. Sev-B/C (2 hours, Business Hours) - CFO’s Laptop Seems Slow

![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/977c2c2b-eccd-491a-8cd0-81fb9ea0e513)

WORKING THE ISSUE AND RESOLUTION 

•	Resolve and Close Tickets:

    o	After troubleshooting and resolving the reported issues, update the ticket status and add any necessary notes or comments.
    o	Communicate with users/customers to confirm issue resolution and close the ticket accordingly.

Ticket Examples

A. Sev-A (1 hour, 24/7) - Entire Mobile/Online Banking System is Down

![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/00d1d491-f308-4a53-aa61-fae89bbe9d21)

B. Sev-B (4 hours, 24/7) - Accounting Department Needs Adobe Upgrade, Broken

![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/4efb2d00-496b-44fd-851e-09c7e0cca564) 

C. Sev-B/C (2 hours, Business Hours) - CFO’s Laptop Seems Slow

![image](https://github.com/John-Duria/osTicket---Ticket-Lifecycle/assets/168502429/c9c8e0e6-a769-4052-b37a-b10df954f580)

