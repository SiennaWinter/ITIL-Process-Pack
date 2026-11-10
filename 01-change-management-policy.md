# Change Management Policy
**Organisation:** North Technology Services (fictional)\
**Owner:** Change Manager\
**Version:** 1.0\
**Review:** Quarterly
## 1. Purpose
This policy sets out how North Technology Services plans, assesses, approves, and implements changes to IT services, so that changes deliver their intended benefit with minimal disruption.
## 2. Scope
The policy applies to any addition, modification, or removal of anything that could affect an IT service. This includes hardware, software, network and cloud configuration, security settings, and service documentation held in the CMDB.
Out of scope: routine service requests (see the service catalogue) and changes to business processes that do not affect IT services.
## 3. Change types
| Type | Definition | Approval | Example | 
|------|------------|----------|---------|
| Standard | Low risk, repeatable, with a documented and tested procedure | Pre-approved | Adding a user to a security group, monthly workstation patching |
| Normal | Any change that is not standard or emergency | Change manager or CAB (change advisory board), based on risk | firewall rule change, cloud migration |
| Emergency | Must be implemented urgently to restore service/s or close a serious security risk | Emergency CAB (ECAB) | Applying a zero day security patch, major outage resolution |

A normal change can become a standard change after it has been successfully implemented at least three times and the change manager has approved its procedure. 
## 4. Risk assessment
Every normal and emergency change is evaluated using the risk matrix below. The evaluation sets the approval path.

| Likelihood of disruption / Impact | Single user or team | One service | Multiple services | Organisational wide |
|---|---|---|---|---|
| **Likely** | Medium | High | High | High |
| **Possible** | Low | Medium | High | High |
| **Unlikely** | Low | Low | Medium | High |

|Risk | Approver | Lead time |
|---|---|---|
| Low | Change manager | 2 Business days |
| Medium | CAB | 5 Business days |
| High | CAB, with business owner sign off | 10 business days |

```math
\text{Average change lead time} = \frac{\sum (\text{Deployment start time} - \text{Submission time})}{\text{Total number of changes complete}}
```
