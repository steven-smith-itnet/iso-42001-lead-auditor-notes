# AI Risk Register — Template

> Original template. Feeds the AI risk treatment plan, the AIAs, and the SoA. The
> AIMS difference: AI risk weighs harm to **individuals, groups, and society** as
> well as to the organization. Keep the method, criteria, and risk owners
> documented (Clause 6.1.2); benchmark the process against ISO/IEC 23894.

| Field | Description |
|---|---|
| Risk ID | Unique reference (e.g., AR-001) |
| AI system | Which system in the inventory the risk relates to |
| Risk source | Model, data, use, third party, etc. (see Annex C) |
| Harm to whom | Individuals / groups / society **and** the organization |
| Harm type | Bias, safety, privacy, security, transparency, societal |
| Likelihood (1–5) | Per the documented criteria |
| Severity (1–5) | Severity of the harm if it occurs |
| Inherent score | Likelihood x Severity |
| Risk owner | Accountable person |
| Treatment | Mitigate / accept / avoid / transfer |
| Controls | Annex A (or other) controls applied |
| AIA ref | Linked AI system impact assessment |
| Residual score | After treatment |
| Residual accepted by | Risk owner + date |

## Example

| AR-001 | Hiring model | Training data | Job applicants (bias) / society | Bias | 4 | 5 | 20 | Head of AI | Mitigate | A.5.4, A.7.4, A.9.4 | AIA-HIRE | 8 | Head of AI 2026-05 |
| AR-004 | Support chatbot | Third-party model | Customers (misinformation) | Transparency | 3 | 3 | 9 | Product Lead | Mitigate | A.8.2, A.10.3 | AIA-CHAT | 4 | Product Lead 2026-05 |
