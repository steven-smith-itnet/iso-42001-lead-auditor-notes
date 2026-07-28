# AI System Inventory — Template

> Original template. The AIMS runs on this inventory — you cannot govern, risk-
> assess, or impact-assess AI systems you have not catalogued. Capturing it is
> also the fastest way to surface **shadow AI** (tools adopted outside governance).
> One row per AI system in scope; keep it current as systems are added, changed,
> or retired.

| Field | Description |
|---|---|
| System ID | Unique reference (e.g., AIS-001) |
| Name | AI system / product name |
| Purpose | What it does and the business use |
| Role | Provider / user / both (drives applicable controls) |
| Lifecycle stage | Inception / development / V&V / deployed / operating / retired |
| Model / foundation model | In-house model, or the third-party/foundation model used |
| Data sources | Datasets feeding training and operation (link to provenance) |
| Risk tier | Low / Medium / High (drives AIA depth and sampling) |
| AIA done? | Yes / No + AIA ref (Clause 8.4) |
| Human oversight | Advisory / human-in-the-loop / automated |
| Owner | Accountable person |

## Example

| AIS-001 | Resume-screening model | Rank applicants for recruiters | Provider + user | Operating | Fine-tuned open model | ATS export, hiring history | High | Yes — AIA-HIRE | Human-in-the-loop | Head of AI |
| AIS-002 | Support chatbot | Answer customer questions | User | Operating | Third-party foundation model | Product docs, FAQ | Medium | Yes — AIA-CHAT | Advisory | Product Lead |
| AIS-003 | Demand forecast | Predict inventory needs | Provider | Development | In-house time-series | Sales history | Low | Planned | Advisory | Data Science Lead |

## Auditor tests
1. Is the inventory **complete** — does sampling turn up AI systems that are missing (shadow AI)?
2. Does every High/Medium-tier system have a performed **AIA** and a defined **owner**?
3. Are **roles** recorded per system, and do they match the SoA's applicability decisions?
