# AI System Impact Assessment (AIA) — Template

> Original template. The AI-specific centerpiece of an AIMS. The **process** to do
> this is required by Clause 6.1.4 and control A.5.2; the completed assessment is
> required by Clause 8.4. Benchmark depth and content against ISO/IEC 42005. Depth
> is **proportionate to risk** — a low-stakes internal tool needs far less than an
> automated decision affecting someone's job, credit, or safety. One AIA per AI
> system (or per material change).

| Field | Value |
|---|---|
| AIA ID | |
| AI system | Name / inventory ref |
| Assessment date & version | |
| Organization's role | Provider / user / both |
| Assessor + reviewer | |

## 1 · System description & intended use
- **What the system does:** model type, inputs, outputs (prediction / recommendation / decision / content).
- **Intended use & context:** the purpose it is deployed for, and the boundaries of that use (A.9.4).
- **Not intended for:** out-of-scope uses that would change the risk.
- **Autonomy & human oversight:** advisory vs. automated; where a human decides (see §5).

## 2 · Affected individuals & groups
- Who is affected (users, decision subjects, bystanders, society).
- Any **vulnerable or protected groups**, and whether outcomes could differ across groups.

## 3 · Potential harms
| Harm category | Description | Likelihood (1–5) | Severity (1–5) |
|---|---|---|---|
| Bias / fairness | Disparate impact across groups | | |
| Safety | Physical or operational harm | | |
| Privacy | Misuse of personal data (link to 27701 / DPIA) | | |
| Transparency | Users unaware they interact with AI / can't contest | | |
| Societal | Broader effects — exclusion, misinformation, autonomy | | |

## 4 · Mitigations & controls
- Controls applied (Annex A refs) and how they reduce each harm above.
- Testing performed (e.g., bias/adverse-impact testing, robustness, validation).

## 5 · Human oversight
- Who reviews / overrides the AI, and for which decisions.
- Escalation path when the system behaves unexpectedly or an incident occurs.

## 6 · Residual impact & sign-off
| Field | Value |
|---|---|
| Residual rating | Low / Medium / High after mitigation |
| Residual accepted by | Name / role / date |
| Review trigger | Interval or change that forces re-assessment |

## Auditor tests
1. Is the AIA **process** defined (6.1.4 / A.5.2) and **performed** for this system (8.4)?
2. Does it assess impact on **individuals/groups (A.5.4)** *and* **society (A.5.5)** — not just the org?
3. Is depth **proportionate** to the system's risk, with human oversight and a residual sign-off?
