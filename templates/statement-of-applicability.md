# Statement of Applicability (SoA) — Template

> Original template. The SoA is the bridge between your AI risk treatment plan and
> the Annex A control set (A.2–A.10, 38 controls). Every control gets a decision
> (apply / exclude), a justification tied to the organization's role and its AI
> risk, an implementation status, and an evidence pointer.

| Control | Title | Applicable | Justification (or exclusion reason) | Status | Evidence ref |
|---|---|---|---|---|---|
| A.2.2 | AI policy | Yes | Governs all AI provider/user activity | Implemented | AI-POL |
| A.5.2 | AI system impact assessment process | Yes | Treats AR-001 (harm to individuals) | Implemented | AIA-PROC |
| A.6.2.4 | AI system verification & validation | Yes | We develop AI (provider role) | Partial | VV-PLAN |
| A.6.x | Development-lifecycle controls | No | Deployer only; we do not develop AI | Excluded | ROLE-DET |
| A.7.5 | Data provenance | Yes | Treats AR-004 (data quality/lineage) | Implemented | PROV-REG |
| A.10.3 | Suppliers | Yes | Foundation-model supplier in scope | Implemented | VENDOR-MSA |

## Auditor tests
1. Consistent with the **AI risk treatment plan** and the **role determination** (provider / user / both)?
2. Every inclusion / exclusion **justified** and traceable to AI risk or a legal/regulatory driver?
3. Does the claimed **status** match reality when you follow the evidence?
4. Are the impact-assessment controls (A.5) backed by actually **performed** AIAs (Clause 8.4)?

**Status values:** Implemented · Partially implemented · Planned · Excluded
