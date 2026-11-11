#Change Advisory Board (CAB): agenda and meeting minutes

**Organisation** North Technology Services *(fictional)*
**Metting:** Weekly, Wednesday 10:00 to 11::00
**Chair:** Change Manager
## Attendees
| Name | Role | Present |
| --- | --- | --- |
| | Change Manager (Chair) | |
| | Service Desk Manager | |
| | Infrastructure Lead | |
| | Network Lead | |
| | Applications Lead | |
| | Cyber Security representative | |
| | Business representative (as needed) | |

Minumum attendance: Chair plus three technical leads, inlcuding Cyber Security for any change affecting security controls.
## Agenda
1. Welcome and attendance
2. Actions from last meeting
3. Review of changes implemented since the lastc CAB (successful, failed, and rolled back)
4. Emergency changes since last CAB
5. Post implementation reviews
6. New RFCs for approval
7. Forward schedule of change (next two weeks) and conflicts
8. Upcoming freezes and major events
9. Other business

## 3. Changes implemented since last CAB

| Change ID | Summary | Result | Incidents caused | PIR needed |
| --- | --- | --- | --- | --- |
| CHG-00000-XXX | | Successful / Failed / Rolled back | | Yes / No |

## 4. Emergency changes
| Change ID | Summary | Reason for emergency | Approved by | Retrospective review outcome |
| --- | --- | --- | --- | --- |
| | | | | |

## 6. New RFCs
For each RFC, the change owner presents for no more than five minutes.

| Change ID | Summary | Risk | Services affected | Rollback plan tested | Decision | Conditions |
| --- | --- | --- | --- | --- | --- | --- |
| | | Low / Medium / High | | Yes / No | Approved / Rejected / Deferred | |

**Questions CAB shoud ask for every new RFC**
- What could go wrong, and how would we know?
- Which services and users are affected? has the CMDB been checked?
- Has it been tested, and where?
- How long does a rollback take, and who decides on this?
- Does it conflict with anything else on the schedule?

## 7. Forward schedule of change
| Date | Window | Change ID | Summary | Conflicts |
| --- | --- | --- | --- | --- |
| | | | | |

## Actions
| # | Action | Owner | Due | Status |
| --- | --- | --- | --- | --- |
| 1 | | | | Open |
---

## Worked example (fictional)
| Change ID | Summary | Risk | Services affected | Rollback plan tested | Decision | Conditions |
| --- | --- | --- | --- | --- | --- | --- |
| CHG-58142-PRD | Upgrade the HR system from version 8.2 to 8.4 | Medium | HR system, payroll interface | Yes, restore tested in UAT (CHG-47993-UAT) | Approved | Payroll team confirms no pay run that night; vendor on call during the window |
| CHG-58156-PRD | Replace core switch in Building C | High | All Building C network services | Yes | Deferred | Clashes with CHG-38393-PRD window; reschedule to the following Thursday and notify Building C staff 5 days ahead |
