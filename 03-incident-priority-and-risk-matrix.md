# Incident priority and risk matrix
**Organisation:** North Technology Services *(fictional)*
Priority is set from **impact** (how much of the business is affected) and **urgency** (how quickly the business needs it fixed). The service desk will usually set the initial priority; the incident manager can change it as more is known.
## 1. Impact
| Level | Definition |
| --- | --- |
| High | Organisation-wide, a critical service is unavailable, or a security breach is suspected |
| Medium | A whole team, site or a non-critical service is affected |
| Low | One user or a small group, with a workaround available |
Use the CMDB to see which services depend on the failed component before rating impact.

## 2. Urgency
| Level | Definition |
| --- | --- |
| High | Work has stopped, financial loss or data loss is occurring now |
| Medium | Work is degraded but can continue for a short time |
| Low | Work can continue; the issue is an inconvenience |

## 3. Priority matrix
| Impact \ Urgency | High | Medium | Low |
| --- | --- | --- | --- |
| **High** | P1 Critical | P2 High | P3 Medium |
| **Medium** | P2 High | P3 Medium | P4 Low |
| **Low** | P3 Medium | P4 Low | P4 Low |

## 4. Targets
| Priority | Response | Resolution target | Updates to stakeholders | High priority incident process |
| --- | --- | --- | --- | --- |
| P1 Critical | 30 minutes | 6 hours | Every hour | Yes |
| P2 High | 1 hour | 12 hours | Every 2 hours | Yes |
| P3 Medium | 4 business hours | 3 business days | On change of status | No |
| P4 Low | 1 business day | 10 business days | On change of status | No |

**SLA breach prevention:** the incident manager reviews all open P1 and P2 incidents at 50% and 75% of their resolution target, and escalates to the resolver team lead and service owner if a breach is likely.
## 5. Risk assessment for every P1 and P2
Alongside priority, rate the risk of the incident getting worse. This decides how hard to escalate and whether to take drastic action, such as shutting a system down.
| Question | Yes increases risk |
| --- | --- |
| Is there a suspected security compromise? | Engage Cyber Security immediately |
| Could data be lost or corrupted? | Consider stopping the affected system |
| Is the impact spreading? | Raise priority and widen communications |
| Is a critical business deadline affected (for example payroll)? | Engage the business owner |
| Is there no known workaround? | Escalate to vendor or senior technical lead |

## 6. Examples
| Scenario | Impact | Urgency | Priority |
| --- | --- | --- | --- |
| Outlook is down for all staff | High | High | P1 |
| Payroll system unavailable on pay day | High | High | P1 |
| Printer on level 3 offline, others working | Low | Low | P4 |
| One team cannot access a shared drive before a deadline today | Medium | Medium | P3 |
| Suspected ransomware on one workstation | High | High | P1 |
| A user's second monitor is not working | Low | Low | P4 |
