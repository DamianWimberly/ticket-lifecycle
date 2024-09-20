<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial explores the lifecycle of a ticket in the open-source help desk system osTicket, from creation to resolution. It demonstrates how end users submit tickets and how the assigned roles from the previous tutorial can view, interact with, and manage tickets through the system.<br />


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

🔷 *As an End-User (Karen), Create a Ticket*

Karen, a branch manager, receives customer reports about the mobile/online banking application being inaccessible. To address this issue, she creates a ticket.

1. On the Support Center [link], select "Open a New Ticket."
2. Fill out Contact Information.
3. Select Help Topic: *Business Critical Outage*.
4. In Ticket Details, briefly describe the issue: 
   *"My employees report users can't access the online banking portal. Those who can, cannot log in."*
5. Click "Create Ticket."

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

🔷 *As a Help Desk Agent (John), Review and Route the Ticket*

John, the Help Desk Agent, reviews Karen's ticket to assign it to the right team.

1. Login to the osTicket analyst site [link].
2. Under "Open Tickets," select Karen's ticket.
3. Review the description and adjust Help Topic if needed.
4. Set the SLA Plan to *Sev-A (1 hour, 24/7)* due to the critical nature.
5. Assign the ticket to the *Online Banking* department for resolution.
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

🔷 *As a Help Desk Agent (Jane), Resolve the Ticket*

Jane, a member of the Online Banking team, is assigned the ticket by John and works to resolve it.

1. Login to the osTicket analyst site [link].
2. Assign the ticket to yourself and review the summary.
3. Propose potential resolutions in the reply section, notifying Karen and John.
4. Once resolved, update the ticket status from *Open* to *Resolved*.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
