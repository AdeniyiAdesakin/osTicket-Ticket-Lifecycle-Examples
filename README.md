# osTicket Ticket Lifecycle: From Intake to Resolution

**Ticket Intake | Triage | Prioritization | Assignment | Communication | Resolution**

<p align="center">
  <img src="https://i.imgur.com/RPZ9Gws.png" width="800" alt="osTicket help desk interface">
</p>

## Project Overview

I used osTicket to manage a simulated support request through its complete lifecycle, from initial submission to final resolution and closure.

The ticket involved a user who could not open a company database application. I reviewed the request, assessed its business impact, updated its priority and SLA plan, assigned it to the appropriate support agent, communicated with the user, documented the resolution, and closed the ticket after access was restored.

This project demonstrates practical help desk skills in ticket triage, prioritization, ownership, customer communication, SLA management, resolution documentation, and closure.

## Business Scenario

An employee named Ken reported that the company database application crashed whenever he attempted to open it. Restarting the computer and reinstalling the application did not resolve the problem, and the employee needed access to continue working.

The request required prompt assessment, assignment, communication, troubleshooting, and documentation to restore access while maintaining a clear support record.

## Project Objectives

- Review and document an incoming support request.
- Assess the urgency and business impact of the issue.
- Apply the appropriate priority and SLA plan.
- Assign the ticket to a qualified support agent.
- Acknowledge the request and gather additional information.
- Investigate the reported symptoms and identify a solution.
- Confirm that access was restored.
- Record the resolution and close the ticket correctly.

## Skills Demonstrated

- Help desk ticket management
- Incident intake and triage
- Impact and urgency assessment
- Priority and SLA administration
- Ticket assignment and ownership
- Customer communication
- Troubleshooting documentation
- Resolution validation
- Ticket closure

## Ticket Summary

| Field | Details |
| --- | --- |
| Ticket number | `#691262` |
| Requester | Ken |
| Issue | Unable to open the company database application |
| Initial priority | Normal |
| Updated priority | Emergency |
| Updated SLA | Sev-A, 1-hour grace period |
| Assigned agent | Jane Doe |
| Help topic | Report a Problem |
| Final status | Resolved |
| Resolution | Application updated and user access restored |

## Ticket Lifecycle

`Intake → Triage → Prioritization → Assignment → Communication → Investigation → Resolution → Closure`

### 1. Ticket Intake

Ken submitted a ticket explaining that the company database application crashed whenever he attempted to open it. He had already restarted the computer and reinstalled the application, but the problem continued.

The request included:

- A clear description of the problem
- Troubleshooting steps already attempted
- The effect on the user’s ability to work
- A request for access to be restored

The ticket was recorded in osTicket as `#691262`.

<p align="center">
  <img src="https://i.imgur.com/j7DMLge.png" width="800" alt="Ticket 691262 displayed in the osTicket open-ticket queue">
</p>

### 2. Triage and Impact Assessment

I reviewed the reported symptoms and determined that the issue required urgent attention because the user could not access a business application needed for work.

During triage, I reviewed:

- The affected application
- The user’s description of the failure
- Troubleshooting steps already completed
- The operational impact of the lost access
- The support resources required to investigate the issue

### 3. Priority and SLA Configuration

The ticket was originally created with a **Normal** priority and the default SLA. Based on the business impact, the ticket was escalated to:

| Setting | Original value | Updated value |
| --- | --- | --- |
| Priority | Normal | Emergency |
| SLA plan | Default SLA | Sev-A |
| Grace period | 18 hours | 1 hour |

<p align="center">
  <img src="https://i.imgur.com/ow1lzJ2.png" width="800" alt="Changing ticket 691262 to the Sev-A SLA plan">
</p>

<p align="center">
  <img src="https://i.imgur.com/JfCbKIB.png" width="800" alt="Updating ticket 691262 from Normal to Emergency priority">
</p>

Applying the Sev-A plan established a shorter service window for the high-impact request.

### 4. Ticket Assignment

The ticket was assigned to Jane Doe so that a specific support agent was responsible for investigating the problem, communicating with the user, and documenting the outcome.

osTicket also provided the option to assign work to an individual agent or a support team, depending on the skills and collaboration required.

<p align="center">
  <img src="https://i.imgur.com/6VImid9.png" width="800" alt="Agent and team assignment options for ticket 691262">
</p>

### 5. Acknowledgement and User Communication

The user received an acknowledgement confirming that the issue was being reviewed. The response recognized the importance of restoring database access and requested additional information, including:

- The exact error message
- The application version
- Any recent operating-system or software changes
- Whether the database could be accessed from another device or by another method

This communication helped gather the information needed for further diagnosis while keeping the user informed.

<p align="center">
  <img src="https://i.imgur.com/qDEScnf.png" width="800" alt="Ticket history showing assignment, escalation, and communication with the user">
</p>

### 6. Investigation and Diagnosis

The reported symptoms and additional information were reviewed to determine why the application could not connect successfully.

The investigation focused on:

- Reproducing or confirming the reported failure
- Reviewing the application version
- Checking for recent system or software changes
- Confirming whether the problem affected only one device
- Identifying a safe way to restore access

The documented resolution showed that the database application required an update.

### 7. Solution Implementation and Validation

The application was updated, and the user’s access to the company database was restored.

Before closing the request, the outcome was validated by confirming that:

- The application opened successfully.
- The user could access the required database.
- The original problem no longer occurred.
- No additional assistance was required.

### 8. Resolution and Ticket Closure

The ticket status was changed to **Resolved**, and a final resolution summary was added:

<i> "The user’s database application was updated, and user now have access. Hence, this ticket has been resolved and will now be closed." </i>

The resolution note created a clear record of the action taken and the final outcome.

<p align="center">
  <img src="https://i.imgur.com/9gBRbd2.png" width="800" alt="Closing ticket 691262 with a Resolved status and resolution summary">
</p>

## Lifecycle Validation

I confirmed that:

- The user’s request was recorded as a support ticket.
- The issue description and prior troubleshooting steps were documented.
- The ticket priority was updated from Normal to Emergency.
- The SLA plan was updated from the default SLA to Sev-A.
- Ownership was assigned to a support agent.
- Communication with the user was recorded in the ticket thread.
- The implemented solution restored application access.
- A final resolution summary was entered.
- The ticket was closed with a Resolved status.

## Key Takeaways

This project demonstrated that effective ticket management involves more than changing a ticket’s status. Each stage creates accountability and ensures that users receive consistent support.

Accurate prioritization helps the support team focus on high-impact issues, SLA plans establish service expectations, assignment creates ownership, and clear communication keeps the user informed. Complete resolution notes also preserve useful information for future troubleshooting and knowledge sharing.

## Related Projects

- [osTicket Prerequisites and Installation](https://github.com/AdeniyiAdesakin/osTicket-Prerequisites-and-Installation)
- [osTicket Post-Installation Configuration](https://github.com/AdeniyiAdesakin/osTicket-Post-Installation-Configuration)

---

**Author:** [Adeniyi Adesakin](https://github.com/AdeniyiAdesakin)  
**LinkedIn:** [linkedin.com/in/adeniyiadesakin](https://www.linkedin.com/in/adeniyiadesakin/)
