# Nonconformity Report — Template

> Original template. One report per nonconformity, with objective evidence.
> Corrective-action reasoning is captured here so the finding, root cause, and
> effectiveness check live together.

| Field | Value |
|---|---|
| NC ID | |
| Audit ID | |
| Classification | Major / Minor |
| Requirement (normative) | Clause / Annex A control the "shall" comes from |
| Statement of nonconformity | What was required vs. what was found |
| Objective evidence | What you saw/heard/read (records, dates, sample IDs, AI system refs) |
| Auditee acknowledgement | Name / date |

## Corrective action (completed by auditee, verified by auditor)

| Field | Value |
|---|---|
| Correction (immediate) | Fix/contain the specific instance |
| Root cause analysis | Why it happened (e.g., 5 Whys) |
| Corrective action | Remove the root cause so it can't recur |
| Owner | Accountable person |
| Target date | |
| Effectiveness check | How/when you'll confirm it worked |
| Status | Open / In progress / Verified closed |

## Guidance (3-part rule)
State the **requirement**, the **evidence**, and the **nonconformity**.
- **Major** — absence/total breakdown of a required process, or a gap that
  raises significant doubt the AIMS can govern AI responsibly (e.g., no AI system
  inventory, no impact assessments at all, AI risk process undefined, SoA missing).
- **Minor** — an isolated lapse that doesn't by itself break the system (e.g., one
  AI system missing an impact assessment; one data-provenance record incomplete).
- Do **not** put the fix in the finding itself (impartiality). Grade on impact to
  the system, not on how easy it is to fix. OFIs are recorded separately.

## Example

| Field | Value |
|---|---|
| NC-003 | — |
| Classification | Minor |
| Requirement | Clause 8.4 / A.5.2 — AI system impact assessment performed |
| Statement | An AIA is required for in-scope AI systems; the deployed support chatbot (AIS-002) had no completed AIA. |
| Objective evidence | AI inventory lists AIS-002 as "operating"; no AIA on file; confirmed with Product Lead, 2026-05-14. |
| Root cause | AIA step not triggered when the chatbot moved from pilot to production. |
| Corrective action | Add an AIA gate to the deployment checklist; complete AIA-CHAT before next release. |
| Effectiveness check | Re-check at next surveillance that all "operating" systems have a current AIA. |
