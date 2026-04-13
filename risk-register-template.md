# Risk Register Template — ISO 27001:2022

**Organisation:** ___________________________
**ISMS Scope:** ___________________________
**Register Version:** 1.0
**Last Reviewed:** ___________________________
**Risk Owner:** ___________________________
**Approved By:** ___________________________

---

## Risk assessment methodology

This register uses the **likelihood × impact** qualitative risk scoring method
as required by ISO 27001:2022 Clause 6.1.2.

### Likelihood scale

| Score | Level | Description |
|---|---|---|
| 1 | Very Low | Unlikely to occur — no known history, strong preventive controls |
| 2 | Low | Could occur but rarely — limited opportunity, some controls in place |
| 3 | Medium | May occur occasionally — moderate controls, known threat vectors |
| 4 | High | Likely to occur — weak controls, frequent threat activity observed |
| 5 | Very High | Almost certain to occur — no controls, active exploitation known |

### Impact scale

| Score | Level | Description |
|---|---|---|
| 1 | Negligible | No meaningful disruption — no financial, legal, or reputational impact |
| 2 | Minor | Limited impact — small financial loss, easily recoverable |
| 3 | Moderate | Noticeable disruption — moderate financial/operational impact |
| 4 | Significant | Serious disruption — regulatory breach, major financial loss possible |
| 5 | Critical | Catastrophic — regulatory action, severe reputational damage, business continuity threat |

### Risk score matrix

| | **Impact 1** | **Impact 2** | **Impact 3** | **Impact 4** | **Impact 5** |
|---|---|---|---|---|---|
| **Likelihood 5** | 5 🟡 | 10 🔴 | 15 🔴 | 20 🔴 | 25 🔴 |
| **Likelihood 4** | 4 🟢 | 8 🟡 | 12 🔴 | 16 🔴 | 20 🔴 |
| **Likelihood 3** | 3 🟢 | 6 🟡 | 9 🟡 | 12 🔴 | 15 🔴 |
| **Likelihood 2** | 2 🟢 | 4 🟢 | 6 🟡 | 8 🟡 | 10 🔴 |
| **Likelihood 1** | 1 🟢 | 2 🟢 | 3 🟢 | 4 🟢 | 5 🟡 |

🟢 Low (1–4) | 🟡 Medium (5–9) | 🔴 High (10–25)

### Risk treatment options

| Option | Description |
|---|---|
| **Mitigate** | Implement controls to reduce likelihood or impact |
| **Accept** | Acknowledge the risk; residual risk within tolerance |
| **Transfer** | Shift risk to a third party (e.g., cyber insurance, outsourcing) |
| **Avoid** | Eliminate the activity or asset that introduces the risk |

---

## Risk register

> Replace the sample rows below with your organisation's identified risks.
> Add rows as needed. Risk IDs should follow the format: `RISK-[number]`.

| Risk ID | Asset / Process | Threat | Vulnerability | Likelihood (1–5) | Impact (1–5) | Risk Score | Risk Rating | Treatment Option | Annex A Control(s) | Control Owner | Due Date | Residual Likelihood | Residual Impact | Residual Score | Accepted By |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| RISK-001 | User credentials | Phishing / credential theft | Lack of MFA on critical systems | 4 | 4 | 16 | 🔴 High | Mitigate | A.5.17, A.8.5 | IT Manager | | 2 | 4 | 8 | |
| RISK-002 | Customer personal data | Unauthorised access | Excessive user access rights | 3 | 5 | 15 | 🔴 High | Mitigate | A.5.15, A.5.18, A.8.2 | IT Manager | | 2 | 5 | 10 | |
| RISK-003 | IT infrastructure | Ransomware / malware | Unpatched software vulnerabilities | 4 | 5 | 20 | 🔴 High | Mitigate | A.8.7, A.8.8, A.8.19 | IT Manager | | 2 | 4 | 8 | |
| RISK-004 | Business operations | Power / utility outage | No UPS or redundant power | 2 | 4 | 8 | 🟡 Medium | Mitigate | A.7.11, A.8.14 | Facilities Manager | | 1 | 4 | 4 | |
| RISK-005 | Sensitive documents | Data leakage by staff | No clean desk policy / DLP controls | 3 | 3 | 9 | 🟡 Medium | Mitigate | A.7.7, A.8.12 | IS Manager | | 2 | 3 | 6 | |
| RISK-006 | Cloud data (SaaS) | Insecure cloud configuration | No formal cloud security policy | 3 | 4 | 12 | 🔴 High | Mitigate | A.5.23 | IT Manager | | 2 | 4 | 8 | |
| RISK-007 | Supplier access | Third-party data breach | Insufficient supplier security controls | 3 | 4 | 12 | 🔴 High | Mitigate | A.5.19, A.5.20, A.5.22 | Procurement | | 2 | 3 | 6 | |
| RISK-008 | Employee data | HR data misuse | No separation of HR system duties | 2 | 3 | 6 | 🟡 Medium | Mitigate | A.5.3, A.6.2 | HR Manager | | 1 | 3 | 3 | |
| RISK-009 | Backup data | Backup failure / data loss | Backups not tested regularly | 2 | 5 | 10 | 🔴 High | Mitigate | A.8.13 | IT Manager | | 1 | 5 | 5 | |
| RISK-010 | Network infrastructure | DDoS / network intrusion | No network segmentation | 3 | 4 | 12 | 🔴 High | Mitigate | A.8.20, A.8.22 | Network Admin | | 2 | 4 | 8 | |
| RISK-011 | | | | | | | | | | | | | | | |
| RISK-012 | | | | | | | | | | | | | | | |

---

## Risk treatment plan summary

| Risk ID | Treatment Option | Controls to Implement | Responsible Owner | Target Completion | Status |
|---|---|---|---|---|---|
| RISK-001 | Mitigate | Deploy MFA; enforce strong password policy | IT Manager | | |
| RISK-002 | Mitigate | Access review; implement RBAC; quarterly recertification | IT Manager | | |
| RISK-003 | Mitigate | Patch management programme; endpoint protection deployment | IT Manager | | |
| RISK-004 | Mitigate | Procure UPS; test at least annually | Facilities Manager | | |
| RISK-005 | Mitigate | Issue clear desk policy; train staff; deploy DLP | IS Manager | | |
| RISK-006 | Mitigate | Draft cloud security policy; review cloud configs quarterly | IT Manager | | |
| RISK-007 | Mitigate | Supplier security questionnaire; add security clauses to contracts | Procurement | | |
| RISK-008 | Mitigate | Implement role segregation in HR system | HR Manager | | |
| RISK-009 | Mitigate | Schedule quarterly backup restore tests; document results | IT Manager | | |
| RISK-010 | Mitigate | Implement VLAN segmentation; deploy IDS | Network Admin | | |

---

## Risk register review log

| Review Date | Reviewer | Changes Made | Next Review Due |
|---|---|---|---|
| | | Initial version created | |
| | | | |

---

## Notes

- This risk register must be reviewed at least **annually** or after significant
  changes to the ISMS scope, environment, or threat landscape (ISO 27001:2022 Clause 8.2).
- All accepted risks must be formally signed off by an appropriate risk owner.
- The Statement of Applicability must reflect controls selected from this risk treatment plan.
- Residual risk must be reviewed and accepted before closure of each treatment item.
