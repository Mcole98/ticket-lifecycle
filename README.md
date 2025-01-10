<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: From Intake to Resolution</h1>
This guide details the journey of a ticket from its creation to resolution using the osTicket help desk system.<br />

<h2>Technologies and Tools Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Protocol (RDP)
- Internet Information Services (IIS)

<h2>Operating System</h2>

- Windows 10 (22H2)

<h2>Stages of the Ticket Lifecycle</h2>

1. **Intake**
2. **Assignment and Communication**
3. **Working the Issue**
4. **Resolution**

<h2>Steps in the Lifecycle</h2>

<h3>1.) Creating Tickets as End-Users</h3>

- **Scenario 1:** As an end-user, create a ticket with the following details:
  - **Subject:** "Entire mobile/online banking system is down"
  - **Details:** Briefly describe the issue (e.g., "The entire online banking system is down, preventing users from accessing their accounts.")

<p>
<img src="https://i.imgur.com/Y6Xptx1.png" height="80%" width="80%" alt="Creating Ticket"/>
</p>

<h3>2.) Reviewing Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Review the ticket's properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.

<p>
<img src="https://i.imgur.com/LjDNXwD.png" height="80%" width="80%" alt="Reviewing Ticket Properties"/>
</p>

<h3>3.) Setting Ticket Properties</h3>

- Update the ticket with these properties:
  - **SLA:** Sev-A (1 hour, 24/7).
  - **Assigned To:** Online Banking Department.

<p>
<img src="https://i.imgur.com/cisoLqw.png" height="80%" width="80%" alt="Setting Ticket Properties"/>
</p>

<h3>4.) Verifying Ticket Permissions</h3>

- Log back in as **Help Desk Agent (john)**.
- Attempt to view or modify the ticket. Confirm if the changes are accessible or editable.

<h3>5.) Resolving the Ticket</h3>

- Log in as **Help Desk Agent (jane)**.
- Take ownership of the ticket, work on the issue, and resolve it.
- Mark the ticket as **Closed** once resolved.

<p>
<img src="https://i.imgur.com/9xTQiJv.png" height="80%" width="80%" alt="Resolving Ticket"/>
</p>

---

<h3>6.) Creating Another Ticket as End-User</h3>

- **Scenario 2:** As an end-user, create a ticket with the following details:
  - **Subject:** "Accounting department needs Adobe upgrade, broken"
  - **Details:** Briefly describe the issue (e.g., "The Adobe software used by the accounting department is broken and needs an upgrade.")

<p>
<img src="https://i.imgur.com/oOqE4OE.png" height="80%" width="80%" alt="Creating Ticket"/>
</p>

<h3>7.) Reviewing Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Review the ticket's properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.

<p>
<img src="https://i.imgur.com/jJBm8Pa.png" height="80%" width="80%" alt="Reviewing Ticket Properties"/>
</p>

<h3>8.) Setting Ticket Properties</h3>

- Update the ticket with these properties:
  - **SLA:** Sev-B (4 hours, 24/7).
  - **Department:** Support.

<p>
<img src="https://i.imgur.com/jeRS4dt.png" height="80%" width="80%" alt="Setting Ticket Properties"/>
</p>

<h3>9.) Resolving the Ticket</h3>

- Log in as **Help Desk Agent (john)**.
- Take ownership of the ticket, work on the issue, and resolve it.
- Mark the ticket as **Closed** once resolved.

<p>
<img src="https://i.imgur.com/v7cimS1.png" height="80%" width="80%" alt="Resolving Ticket"/>
</p>

---

<h3>10.) Creating a Final Ticket as End-User</h3>

- **Scenario 3:** As an end-user, create a ticket with the following details:
  - **Subject:** "CFO’s laptop will no longer turn on"
  - **Details:** Briefly describe the issue (e.g., "The CFO's laptop is not powering on and needs urgent attention.")

<p>
<img src="https://i.imgur.com/FF8TDmh.png" height="80%" width="80%" alt="Creating Ticket"/>
</p>

<h3>11.) Reviewing Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Review the ticket's properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.

<p>
<img src="https://i.imgur.com/BOIMfD3.png" height="80%" width="80%" alt="Reviewing Ticket Properties"/>
</p>

<h3>12.) Setting Ticket Properties</h3>

- Update the ticket with these properties:
  - **SLA:** Sev-B (4 hours, 24/7).
  - **Department:** Support.

<p>
<img src="https://i.imgur.com/5QIMpDf.png" height="80%" width="80%" alt="Setting Ticket Properties"/>
</p>

<h3>13.) Resolving the Ticket</h3>

- Log in as **Help Desk Agent (john)**.
- Take ownership of the ticket, work on the issue, and resolve it.
- Mark the ticket as **Closed** once resolved.

---

<h2>Conclusion</h2>

By following these steps, you have successfully demonstrated how a ticket progresses from intake to resolution within osTicket. This guide emphasizes the importance of ticket properties, proper assignment, and resolution processes in a help desk environment.
