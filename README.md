<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket Logo"/>
</p>

<h1 align="center">osTicket – Phase 3: Ticket Lifecycle Demonstration</h1>

<p>
This lab demonstrates the complete lifecycle of a support ticket within <strong>osTicket</strong>, from initial creation through triage, escalation, resolution, and closure. The objective is to simulate real-world IT support workflows using SLAs, prioritization, and agent communication.
</p>

---

<h2>🎥 Video Demonstration</h2>

- ### <a href="https://www.youtube.com/watch?v=LfigAOzRHFs">YouTube: osTicket Tutorial (Phase 3/3 – Ticket Lifecycle Demonstration)</a>

---

<h2>🛠 Environments & Technologies Used</h2>

<ul>
  <li>Microsoft Azure (Virtual Machines)</li>
  <li>Remote Desktop Protocol (RDP)</li>
  <li>Internet Information Services (IIS)</li>
  <li>osTicket Help Desk System</li>
</ul>

---

<h2>💻 Operating Systems Used</h2>

<ul>
  <li>Windows 10 (21H2)</li>
</ul>

---

<h1>📌 Phase 3 Overview – Ticket Lifecycle</h1>

<p>
<strong>Goal:</strong> Demonstrate how osTicket manages support requests from intake to resolution, including ticket prioritization, SLA enforcement, agent assignment, escalation, and closure.
</p>

<p>
This phase focuses on operational workflows that mirror a real enterprise IT support environment.
</p>

---

<h2>Ticket Lifecycle: Intake Through Resolution</h2>

<p>
This phase walks through the full lifecycle of a ticket once it is submitted by an end user. Each stage reflects standard IT Service Management (ITSM) practices.
</p>

<ul>

  <li>
    <strong>Ticket Intake</strong>
    <p>
      A ticket is created by an end user through the osTicket user portal. The ticket includes a help topic, priority level, and description of the issue.
    </p>
    <ul>
      <li>User submits ticket via the end-user portal</li>
      <li>Ticket is automatically categorized using Help Topics</li>
      <li>Default SLA and priority are applied</li>
    </ul>
  </li>

  <li>
    <strong>Assignment & Communication</strong>
    <p>
      Once submitted, the ticket is routed to the appropriate department or team based on configuration from Phase 2.
    </p>
    <ul>
      <li>Ticket assigned to Level I or Level II support</li>
      <li>Agent reviews issue details</li>
      <li>Initial communication sent to the user</li>
    </ul>
  </li>

  <li>
    <strong>Working the Issue</strong>
    <p>
      The assigned agent investigates and works toward resolving the issue while providing updates as needed.
    </p>
    <ul>
      <li>Agent performs troubleshooting steps</li>
      <li>Internal notes added for documentation</li>
      <li>Status updated (Open → In Progress)</li>
    </ul>
  </li>

  <li>
    <strong>Resolution & Closure</strong>
    <p>
      Once the issue is resolved, the agent confirms the solution with the user and closes the ticket.
    </p>
    <ul>
      <li>Solution provided and verified</li>
      <li>Ticket marked as Resolved</li>
      <li>Ticket closed after confirmation</li>
    </ul>
  </li>

</ul>

---

<h2>Ticket Prioritization Using SLAs</h2>

<p>
Service Level Agreements (SLAs) ensure tickets are resolved within defined timeframes based on severity. This lab demonstrates SLA-driven prioritization and escalation.
</p>

<ul>

  <li>
    <strong>Sev-A – Cr
