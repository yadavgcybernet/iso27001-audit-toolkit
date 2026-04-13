# ISO 27001 Audit Toolkit

> A practical, ready-to-use toolkit for ISO 27001:2022 internal audits,
> risk assessments, and ISMS implementation — built from real-world audit experience.

Maintained by [Yadav Ghorasainee](https://linkedin.com/in/yadav-ghorasainee)
— IS Auditor | ISO 27001 Internal Auditor | GRC Professional | Perth, WA, Australia

---

## What is this?

This toolkit provides structured, reusable templates and checklists for:

- Conducting ISO 27001:2022 internal audits
- Building and maintaining a risk register
- Drafting a Statement of Applicability (SoA)
- Collecting and organising audit evidence

It is based on ISO/IEC 27001:2022 (the current version — all ISO 27001:2013
certifications expired in October 2025).

---

## Repository contents

| File | Purpose |
|---|---|
| [`annex-a-controls-checklist.md`](./annex-a-controls-checklist.md) | All 93 Annex A controls across 4 themes — with audit status tracking |
| [`risk-register-template.md`](./risk-register-template.md) | Risk register with likelihood × impact scoring methodology |
| [`statement-of-applicability-template.md`](./statement-of-applicability-template.md) | Full SoA template — all 93 controls with justification columns |
| [`audit-evidence-guide.md`](./audit-evidence-guide.md) | Clause-by-clause evidence requirements for certification audits |

---

## ISO 27001:2022 at a glance

### Mandatory clauses (4–10)

| Clause | Title | Key deliverable |
|---|---|---|
| 4 | Context of the Organisation | ISMS Scope document |
| 5 | Leadership | Information Security Policy (top management signed) |
| 6 | Planning | Risk assessment, SoA, IS objectives |
| 7 | Support | Competence records, awareness logs |
| 8 | Operation | Executed risk assessments, treatment evidence |
| 9 | Performance Evaluation | Internal audit report, management review minutes |
| 10 | Improvement | Corrective action log, nonconformity records |

### Annex A — 4 themes, 93 controls

| Theme | Controls | Focus |
|---|---|---|
| 5 — Organisational | A.5.1 – A.5.37 (37 controls) | Policies, roles, asset management, supplier security, incident management |
| 6 — People | A.6.1 – A.6.8 (8 controls) | HR security, screening, awareness, remote working |
| 7 — Physical | A.7.1 – A.7.14 (14 controls) | Physical perimeters, entry controls, clear desk |
| 8 — Technological | A.8.1 – A.8.34 (34 controls) | Access control, cryptography, secure development, monitoring |

### 11 new controls introduced in 2022

`A.5.7` Threat intelligence · `A.5.23` Cloud services security · `A.5.30` ICT readiness for BC
`A.7.4` Physical security monitoring · `A.8.9` Configuration management · `A.8.10` Information deletion
`A.8.11` Data masking · `A.8.12` Data leakage prevention · `A.8.16` Monitoring activities
`A.8.23` Web filtering · `A.8.28` Secure coding

---

## How to use this toolkit

### For internal auditors
1. Use `annex-a-controls-checklist.md` as your audit checklist — mark each control's status
2. Use `audit-evidence-guide.md` to know exactly what evidence to request per clause
3. Document findings and raise nonconformities (NCs) and observations (OBs)

### For ISMS implementers
1. Start with `statement-of-applicability-template.md` — document inclusion/exclusion of each control
2. Build your `risk-register-template.md` — link identified risks to controls in the SoA
3. Work through the evidence checklist to identify documentation gaps

### For certification preparation
1. Verify all mandatory records exist (see `audit-evidence-guide.md`)
2. Ensure the SoA is signed off and links to the risk treatment plan
3. Confirm internal audit and management review have been completed within the last 12 months

---

## Audit risk rating scale used in this toolkit

| Score | Likelihood / Impact | Label |
|---|---|---|
| 1 | Very low | Negligible |
| 2 | Low | Minor |
| 3 | Medium | Moderate |
| 4 | High | Significant |
| 5 | Very high | Critical |

**Risk score = Likelihood × Impact** (max 25)

| Risk score | Rating |
|---|---|
| 1–4 | Low |
| 5–9 | Medium |
| 10–16 | High |
| 17–25 | Critical |

---

## Disclaimer

This toolkit is based on ISO/IEC 27001:2022 and reflects practical audit experience.
It is intended as a working aid — not a substitute for the official ISO standard or
accredited certification body guidance. Always refer to the published ISO 27001:2022
standard for authoritative requirements.

---

## License

[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Licensed under Creative Commons Attribution 4.0. You are free to use, adapt, and
share with attribution.

---

## Author

**Yadav Ghorasainee**
IS Auditor | (ISC)² CC | ISO 27001 Internal Auditor | Fortinet NSE
Perth, WA, Australia | Full Australian working rights

- 📧 yadavg.cybernet@gmail.com
- 🔗 [LinkedIn](https://linkedin.com/in/yadav-ghorasainee)
- 🌐 [Portfolio](https://yadavgcybernet.github.io/sec)
