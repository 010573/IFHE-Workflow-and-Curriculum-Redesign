# Task 1: Investigation of a College Workflow

## Topic Selected

Club Event Approval Request Process

## Investigation Status

Hypothetical Walkthrough (Permission-Based Access Not Available)

This report does not claim to represent the actual ICFAI/IFHE process. Since direct observation and formal access to administrative workflows were unavailable, this analysis uses a hypothetical process for academic purposes.

---

# 1. Process Discovery

## How the Process Was Studied

No institutional records, staff interviews, or approval logs were accessed.

A hypothetical event approval workflow was created based on common procedures used by student clubs in educational institutions.

---

# 2. Current Workflow

## Roles Involved

| Role | Responsibility |
|--------|--------------|
| Club Representative | Creates and submits event request |
| Faculty Coordinator | Reviews proposal |
| Student Affairs Office | Checks policy compliance |
| Accounts Team | Reviews budget requirements |
| Venue Coordinator | Checks venue availability |
| Club Representative | Receives final decision |

---

## Current Steps

1. Club representative prepares event proposal.
2. Proposal is submitted through email or paper form.
3. Faculty coordinator reviews request.
4. Incomplete requests are returned for correction.
5. Approved requests are forwarded to Student Affairs.
6. Student Affairs verifies compliance.
7. Budget requirements are reviewed.
8. Venue availability is checked.
9. Final approval is issued.
10. Club receives approval and conducts the event.

---

# 3. Current Workflow Diagram

Club Representative

↓

Faculty Coordinator

↓

Student Affairs

↓

Accounts Team

↓

Venue Coordinator

↓

Final Approval

---

# 4. Evidence Log

### Date

23-Oct-2026

### Method

Hypothetical Walkthrough

### Sample Size

5 Synthetic Requests

### Access Limitations

- No direct observation.
- No access to approval records.
- No staff interviews.

### Observed Facts

No observations available due to access limitations.

### Estimates

- Approximately 10 event requests per month.
- Faculty review requires about 10 minutes.
- Administrative review requires about 10 minutes.

### Assumptions

- 20% of requests require corrections.
- Communication occurs through email.
- Reviews occur during office hours.

---

# 5. Operational Problems

## Problem 1: Multiple Handoffs

Requests move through multiple departments before approval.

### Impact

Approval delays and waiting periods between reviewers.

---

## Problem 2: Missing Information

Students may submit incomplete forms.

### Impact

Repeated communication and additional review effort.

---

## Problem 3: No Status Tracking

Students cannot easily determine:

- Current status
- Pending reviewer
- Expected completion date

### Impact

Additional follow-up emails and uncertainty.

---

## Problem 4: Duplicate Requests

Students may submit duplicate requests while waiting.

### Impact

Unnecessary administrative workload.

---

# 6. Scale of the Problem

## Time Per Request

| Activity | Estimated Time |
|----------|---------------|
| Proposal Preparation | 15 min |
| Faculty Review | 10 min |
| Student Affairs Review | 10 min |
| Budget Review | 5 min |
| Venue Review | 10 min |
| Communication | 5 min |
| Total | 55 min |

### Rework

20% of requests require corrections.

Correction effort:

20 minutes

Calculation:

0.20 × 20 = 4 minutes

Average processing time:

55 + 4 = 59 minutes

---

## Monthly Effort

10 requests per month

59 × 10 = 590 minutes

590 ÷ 60 = 9.83 hours

Approximately 10 staff-hours per month.

---

# 7. Proposed Improved Workflow

## Objective

Reduce approval delays and improve visibility.

### Inputs

- Club Name
- Event Title
- Event Date
- Event Description
- Venue Requirement
- Budget Requirement
- Faculty Coordinator

---

## Statuses

- Draft
- Submitted
- Under Faculty Review
- Under Administrative Review
- Awaiting Budget Approval
- Awaiting Venue Confirmation
- Returned for Correction
- Approved
- Rejected

---

## Accountable Owner

Student Affairs Office

Responsible for tracking requests until completion.

---

## Approval Boundaries

### Human Approval Required

- Event approval
- Budget approval
- Policy exceptions

### Automated Actions

- Form validation
- Status updates
- Email notifications
- Duplicate detection

---

## Audit Record

The system stores:

- Submission timestamp
- Review timestamp
- Approval timestamp
- Status history

---

## Fallback Procedure

If the system is unavailable:

1. Use a PDF request form.
2. Submit through email.
3. Record decision manually.
4. Update the system after restoration.

---

# 8. Improved Workflow

Student Submission

↓

Automatic Validation

↓

Faculty Review

↓

Student Affairs Review

↓

Budget & Venue Verification

↓

Final Approval

↓

Student Notification

---

# 9. Testing with Synthetic Cases

## Case 1: Normal Request

Input:
Complete proposal

Expected Result:
Approved

Recovery:
None

Decision Maker:
Faculty Coordinator and Student Affairs

---

## Case 2: Missing Information

Input:
Budget field missing

Expected Result:
Returned for correction

Recovery:
Student updates request

Decision Maker:
Student

---

## Case 3: Duplicate Request

Input:
Same event submitted twice

Expected Result:
Duplicate warning generated

Recovery:
Student confirms request

Decision Maker:
Student Affairs

---

## Case 4: Unauthorized Request

Input:
Request submitted by unauthorized member

Expected Result:
Rejected

Recovery:
Authorized representative submits request

Decision Maker:
Student Affairs

---

## Case 5: Failed Step

Input:
Venue unavailable

Expected Result:
Venue conflict

Recovery:
Alternative venue selected

Decision Maker:
Venue Coordinator

---

# 10. Estimated Time Savings

## Current Process

Average effort:

59 minutes per request

## Improved Process

Average effort:

35 minutes per request

### Savings

59 − 35 = 24 minutes per request

Monthly savings:

24 × 10 = 240 minutes

240 ÷ 60 = 4 hours

---

## Support Effort

User support:
1 hour

Exception handling:
30 minutes

Workflow review:
30 minutes

Total Support:
2 hours/month

---

## Net Time Saved

4 − 2 = 2 hours/month

Estimated net benefit: 2 staff-hours per month.

---

# 11. Risks

- Users may continue using emails.
- Incorrect routing may delay approval.
- Staff training may be required.
- Approval policies may change.

---

# 12. Remaining Unknowns

- Actual request volume.
- Existing software in use.
- Real review times.
- Actual correction rates.

---

# 13. Conclusion

The proposed workflow reduces manual effort, improves request visibility, prevents duplicate submissions, and streamlines approvals. Based on the stated assumptions, the redesigned process can save approximately 2 net staff-hours per month while maintaining human oversight for key approval decisions.
