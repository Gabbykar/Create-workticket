<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (22H2)

<h2>Ticket Lifecycle Stages</h2>

1. **Intake**
2. **Assignment and Communication**
3. **Working the Issue**
4. **Resolution**

<h2>Lifecycle Stages</h2>

<h3>1.) Create Tickets as End-Users</h3>

- **Scenario 1:** Create a ticket as an end-user with the following details:
  - **Subject:** "Entire mobile/online banking system is down"
  - **Details:** Describe the issue briefly (e.g., "The entire online banking system is down, preventing users from accessing their accounts.")

<p>
<img src="https://github.com/user-attachments/assets/90cc688e-ae33-4d39-8559-2e1f70224fbb"/>
</p>


</p>

<h3>3.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-A (1 hour, 24/7).
  - **Assigned To:** Online Banking Department.

<p>
<img src="https://github.com/user-attachments/assets/3b5e4149-00f7-444a-9d0e-54027902bdac"/>
</p>


<h3>5.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (jane)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

<p>
<img src="https://github.com/user-attachments/assets/05d1c084-05fb-4b40-9760-528e6086eca1"/>

</p>

<p>
<img src="https://github.com/user-attachments/assets/20c19493-380b-46d5-afe8-49c749ee9654"/>
</p>

<p>
<img src="https://github.com/user-attachments/assets/caa41ecf-a813-473e-94f2-c3a6cbccdfc2"/>
</p

<p>
<img src="https://github.com/user-attachments/assets/3cc3abbe-3390-44a8-b49a-24236d3fe785"/>
</p>
---

<h3>6.) Create Another Ticket as End-User</h3>

- **Scenario 2:** Create a ticket as an end-user with the following details:
  - **Subject:** "Accounting department needs Adobe upgrade, broken"
  - **Details:** Describe the issue briefly (e.g., "The Adobe software used by the accounting department is broken and needs an upgrade.")
 
<p>
<img src="https://github.com/user-attachments/assets/035020df-abc9-4d8b-a60d-17131de55589"/>
</p>

 
<p>

<h3>8.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-C (4 hours, 24/7).
  - **Department:** Support.
 
<p>
<img src="https://github.com/user-attachments/assets/1781c432-c4f9-4f6b-a418-5fb3f4aa5119"/>
</p>

<h3>9.) Work the Ticket to Completion</h3>
- Log in as **Help Desk Agent (john)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

<p>
<img src="https://github.com/user-attachments/assets/5c5b1089-6940-4a3b-8502-b448887101ba"/>
</p>

<p>
<img src="https://github.com/user-attachments/assets/01e76f18-5444-4c9c-9fef-21313b7496b7"/>
</p>

<p>
<img src="https://github.com/user-attachments/assets/8f9de769-5e8c-4aeb-ad8d-87041f06c33f"/>
</p>

<p>
<img src="https://github.com/user-attachments/assets/c6ee43f5-aea5-41fa-87b0-c7db6efb0a59"/>
</p>

<p>
<img src="https://github.com/user-attachments/assets/69673aae-a5e9-4008-9388-f3a6202c416a"/>
</p>

---

<h3>10.) Create a Final Ticket as End-User</h3>

- **Scenario 3:** Create a ticket as an end-user with the following details:
  - **Subject:** "CFO’s laptop will no longer turn on"
  - **Details:** Describe the issue briefly (e.g., "The CFO's laptop is not powering on, and it needs urgent attention.")
 
<p>
<img src="https://github.com/user-attachments/assets/0a5814c9-84d6-4948-8c13-cbe0fc41f131"/>
</p>

<h3>11.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.

<p>
<img src="https://github.com/user-attachments/assets/30705a5e-ae48-4509-8e2c-1e37333ef4e7"/>


<h3>12.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-B (4 hours, 24/7).
  - **Department:** Support.

<p>
<img src="https://github.com/user-attachments/assets/d519595c-8c45-4669-8965-79da317a99eb"/>
</p>

<h3>13.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (john)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

<p>
<img src="https://github.com/user-attachments/assets/de57757c-72e6-4f95-b270-47dffc4fb704"/>
</p>

<p>
<img src="https://github.com/user-attachments/assets/78f53308-f605-4bce-bb24-f412fde4381b"/>
</p>

<p>
<img src="https://github.com/user-attachments/assets/85b34785-062f-4b56-aae8-b314aab5b260"/>


</p>
---

<h2>Conclusion</h2>

By following these steps, you have successfully demonstrated the lifecycle of a ticket from intake to resolution within osTicket. This lab highlights the importance of ticket properties, proper assignment, and resolution processes in a help desk environment.
