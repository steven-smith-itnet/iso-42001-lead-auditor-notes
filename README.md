# ISO/IEC 42001 Lead Auditor — Study Notes

![Topic](https://img.shields.io/badge/Topic-ISO%2FIEC%2042001%3A2023-58a6ff)
![Focus](https://img.shields.io/badge/Focus-AIMS%20%C2%B7%20Audit-7cc4ff)
![Type](https://img.shields.io/badge/Type-Study%20Notes-4ade80)
![License](https://img.shields.io/badge/License-MIT-blue)

Original, self-authored study notes for learning to audit an **Artificial
Intelligence Management System (AIMS)** against **ISO/IEC 42001:2023** — the
world's first AI management-system standard — written as I worked through a
lead-auditor learning path, and paired with real-world use cases and reusable
templates I built along the way.

## 🔗 Live notes

**https://steven-smith-itnet.github.io/iso-42001-lead-auditor-notes/**

## 📚 Learning path (sections)

1. **ISO Fundamentals ("The Basics")** — how standards work, certification vs.
   accreditation, the multi-year audit cycle, normative vs. informative criteria,
   and why the Annex SL spine means 27001 knowledge transfers
2. **ISO 42001 & the AIMS** — the first AI management-system standard, the
   organization's role (provider vs. user), and how it integrates with 27001,
   27701 and 9001
3. **The Clause Spine (4–10)** — the auditable requirements in clause order with
   an AI lens, and the two homes of the AI system impact assessment
4. **Annex A Controls** — 38 controls in nine objectives (A.2–A.10), and the role
   of Annexes B, C and D
5. **AI Risk, the Impact Assessment & the SoA** — risk to people and society, the
   AI system impact assessment as the AI-specific centerpiece, and how the SoA
   ties controls to risk
6. **Supporting Standards** — 22989, 23894, 42005, 42006, 5259, 19011, 17021-1 —
   what each is for
7. **The Lead Auditor Path** — training vs. certification, grades, and the
   AI-specific competence an AIMS auditor needs
8. **The Audit** — order of operations, nonconformity classification, and common
   AI hot-spots

## 📝 Templates

Original, reusable starters in [`templates/`](templates/):

- [Statement of Applicability](templates/statement-of-applicability.md)
- [AI risk register](templates/ai-risk-register.md)
- [AI system impact assessment](templates/ai-system-impact-assessment.md)
- [AI system inventory](templates/ai-system-inventory.md)
- [AIMS audit plan](templates/audit-plan.md)
- [AIMS audit checklist](templates/audit-checklist.md)
- [Nonconformity report](templates/nonconformity-report.md)

## 📌 Reflections

The distinction that reframed everything was **normative vs. informative**
criteria — an auditor can only raise a nonconformity against a "shall." What is
new in an AIMS is *who* the risk is about: AI risk and the **AI system impact
assessment** must weigh harms to individuals, groups, and society, not just the
organization. The rest is disciplined evidence-gathering: follow a real audit
trail from AI system → risk → impact assessment → control → monitoring record,
and test control **effectiveness**, not just existence.

## ⚖️ About / copyright

These are **original** notes and examples written from general knowledge of ISO/IEC
42001 and AI management. They are **not affiliated with, derived from, or endorsed
by any training provider**, and they **do not reproduce** the ISO standard or any
course materials. Clause *numbers*, control *identifiers*, and framework structure
are referenced for orientation only — for the normative text and control guidance,
obtain the official
[ISO/IEC 42001](https://www.iso.org/standard/81230.html) standard from ISO.
Templates are original starting points and are not legal advice.

## Tech

A single self-contained `index.html` (no build step) plus markdown templates.
Deploys anywhere static files are served (GitHub Pages, S3/CloudFront, etc.).

## License

[MIT](LICENSE) — for the notes and templates in this repository.
