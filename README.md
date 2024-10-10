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

- Windows 10</b> 

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

🔷 **As an End-User (Karen), Create a Ticket**

Karen, a bank branch manager, receives customer reports about the mobile/online banking application being inaccessible. To address this issue, she creates a ticket.

  -  In the Support Center (**http://localhost/osTicket**), select **"Open a New Ticket"**:
      - Fill out Contact Information.
      - Select Help Topic: *Report a Problem* 
     - In Ticket Details, briefly describe the issue: 
     *"My employees report users can't access the online banking portal. Those who can, cannot log in."*
      - Click "Create Ticket."

<table>
  <tr>
    <td><img width="200" height="150" alt="Screenshot 2024-10-09 at 9 26 05 PM" src="https://github.com/user-attachments/assets/37ba67b3-620b-4a50-9d1b-d2600b184ad0"></td>
    <td><img width="200" height="150" alt="Screenshot 2024-10-09 at 9 34 34 PM" src="https://github.com/user-attachments/assets/b5ef860a-b38c-47ae-9a34-ec88f076358e">
</td>
  <tr>
    <td>Support Center</td>
    <td>Karen Opens Ticket</td>
  </tr>
</table>

🔷 **As a Help Desk Agent (John), Review and Route the Ticket**

John, the Help Desk Agent, reviews Karen's ticket to assign it to the right team.
  - Login to the osTicket agent site **http://localhost/osTicket/scp/login.php** as agent John Doe.
  - Under **"Open Tickets"**, select Karen's ticket.
      - Review the ticket **Priority**, **Department**, and **SLA Plan** and adjust if needed.
        - Adjut the ticket **Priority** to *High*.
        - Set the SLA Plan to *Sev-A (1 hour, 24/7)* due to the critical nature.
        - Assign the ticket to the *Online Banking* department for resolution.
<table>
  <tr>
    <td><img width="200" alt="Screenshot 2024-10-10 at 9 59 37 AM" src="https://github.com/user-attachments/assets/8ef466df-fc1d-4780-b025-f71709239290">
</td>
    <td><img width="200" alt="Screenshot 2024-10-10 at 9 59 58 AM" src="https://github.com/user-attachments/assets/9b19a889-c4a5-46c8-a698-cdc6def47df5">
</td>
    <td><img width="200" alt="Screenshot 2024-10-10 at 10 53 41 AM" src="https://github.com/user-attachments/assets/54b0a3b6-b655-414c-890b-f2ffe17e3294">
</td>
    <td><img width="200" alt="Screenshot 2024-10-10 at 10 58 40 AM" src="https://github.com/user-attachments/assets/8c33cae8-9762-4aed-8673-6f4617e6cebe">
</td>
  <tr>
    <td>Help Desk Agent Login</td>
    <td>Ticket Dashboard</td>
    <td>Review Karen's Ticket</td>
    <td>Triage and Assign Ticket</td>
  </tr>
</table>

🔷 **As a Help Desk Agent (Jane), Resolve the Ticket**

Jane, a member of the Online Banking team, observes that a ticket has been assigned to the Online Banking team by John. Jane will assign the ticket to herself and work to resolve the ticket. 

  - Login to the osTicket agent site **http://localhost/osTicket/scp/login.php** as Jane Doe.
      - Assign the ticket to yourself and review the summary.
      - Observe the ticket thread.
      - Propose potential resolutions in the reply section, notifying Karen and John.
      - Once resolved, update the ticket status from *Open* to *Resolved*.

<table>
  <tr>
    <td><img width="200" alt="Screenshot 2024-10-10 at 11 03 10 AM" src="https://github.com/user-attachments/assets/b8b413de-cdee-4754-a0f9-68e7d6a14ccc"><img width="200" alt="Screenshot 2024-10-10 at 11 03 30 AM" src="https://github.com/user-attachments/assets/0c398eca-63ca-4706-8098-c384b6def918">
</td>
    <td><img width="200" alt="Screenshot 2024-10-10 at 11 04 38 AM" src="https://github.com/user-attachments/assets/d3cd684a-2d07-4a4c-b56f-abc91950692c"><img width="200" alt="Screenshot 2024-10-10 at 11 05 23 AM" src="https://github.com/user-attachments/assets/bab6a63d-87b9-4231-ac63-641cf01af5d2"><img width="200" alt="Screenshot 2024-10-10 at 12 22 02 PM" src="https://github.com/user-attachments/assets/04031358-48d0-42c0-8efe-b7cad5b0b8bc">
</td>
    <td><img width="400" alt="Screenshot 2024-10-10 at 12 22 16 PM" src="https://github.com/user-attachments/assets/a34107e2-27f8-4faf-94ed-5e7723de3ce1">
</td>
    <td><img width="200" alt="Screenshot 2024-10-10 at 12 29 29 PM" src="https://github.com/user-attachments/assets/48d87ad6-c406-497b-81db-4dcae771ce57"><img width="200" alt="Screenshot 2024-10-10 at 12 34 11 PM" src="https://github.com/user-attachments/assets/aa43886c-35d6-4d9b-8c45-de8dfdf39f35">
</td>
 <td><img width="200" alt="Screenshot 2024-10-10 at 12 35 20 PM" src="https://github.com/user-attachments/assets/eaead848-6fa4-4ec4-afbf-4075df80ebfe"><img width="200" alt="Screenshot 2024-10-10 at 12 35 51 PM" src="https://github.com/user-attachments/assets/43858d9d-0f20-46aa-a21e-123a6e7e567b">

</td>
  <tr>
    <td>Login and View the Ticket</td>
    <td>Claim the Ticket</td>
    <td>Ticket Thread</td>
    <td>Work the Ticket</td>
    <td>Resolve Ticket</td>
  </tr>
</table>
