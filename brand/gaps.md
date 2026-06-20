# gaps.md — Hammad Ali Rana
# Generated: 2026-06-20
# Rule: a gap closes only when evidence ships → new resume.json entry → row deleted.

| Gap | Evidence the target demands it | What I have | Madison build that would close it | Plan |
|-----|-------------------------------|-------------|----------------------------------|------|
| No hands-on enterprise GRC platform experience (ServiceNow, Drata, LogicGate) | GRC analyst job postings (LinkedIn, Indeed, June 2026) cite GRC platform familiarity in 80%+ of listings. Interviewers ask about platform workflows, not just framework knowledge. | Sentinel GRC Ops — a custom-built GRC pipeline. Understands GRC data models from building one. No commercial platform seat time. | Extend Sentinel GRC Ops with a ServiceNow-compatible output format — JSON tickets that match ServiceNow GRC intake schema. Demonstrates understanding of how enterprise GRC platforms ingest data without requiring a $50K license. | Build ServiceNow-compatible remediation ticket output in Sentinel. Document the data model mapping. Publish as a case study on LinkedIn. |
| No formal security certification (CompTIA Security+, CISM, or equivalent) | 60%+ of GRC analyst postings list Security+ or equivalent as preferred. Some list it as required. Signals baseline domain credibility to screeners. | ETA Certified Proctor (TOEFL/Pearson VUE) — operations credibility, not security credibility. Cybersecurity and Audit course in progress Summer 2026. | Madison Study Agent — a spaced-repetition quiz agent built on CISA/NIST framework content that doubles as Security+ exam prep. Building the tool proves domain knowledge while preparing for the cert. | Enroll in CompTIA Security+ exam. Build Madison study agent as the prep tool. Target cert completion by December 2026. |
| No direct compliance auditing experience (SOC 2 audit participation, ISO 27001 assessment) | Audit experience cited in senior GRC postings. Even junior postings reference "supporting audit readiness." Validators want evidence of working inside an audit cycle, not just knowing the frameworks. | Sentinel GRC Ops maps advisories to Annex A controls and SOC 2 criteria — demonstrates framework fluency. No actual audit participation on record. | Madison Audit Readiness Agent — simulates a SOC 2 Type II audit readiness checklist, generating evidence requests and gap reports from a given control set. The build artifact IS the audit readiness demonstration. | Build audit readiness simulation module in Sentinel. Offer to run it for a real small organization pro bono. Document the engagement as a case study. |
| No published thought leadership in GRC/AI space | Hiring managers in compliance increasingly Google candidates. A published piece on "AI in GRC" or "automating CISA advisory mapping" would surface in searches and establish voice before the interview. | Sentinel GRC Ops is a strong proof point but is not yet written up as a public article or case study. | Madison Content Agent — automates drafting of LinkedIn articles and technical posts from project documentation. First output: a 600-word LinkedIn article on "How I built a free AI tool that maps CISA advisories to ISO 27001 in under 10 minutes." | Write and publish one LinkedIn article per month starting July 2026. Use Sentinel GRC Ops as the first case study. Target 500+ impressions per post within 30 days. |

---

## Top Gap — Project Proposal (150–200 words)

**Project: Madison Audit Readiness Agent**

The highest-signal gap between my current profile and a GRC analyst role is the absence of direct compliance auditing experience. Every GRC job posting references audit readiness, evidence collection, or control gap assessment — and no amount of framework knowledge substitutes for having worked inside an audit cycle.

My proposed Madison build closes this gap directly: an Audit Readiness Agent that simulates a SOC 2 Type II readiness assessment. The agent takes a control set as input, generates a structured evidence request list per control, identifies gaps between what exists and what an auditor would require, and outputs a prioritized remediation plan.

Building this artifact accomplishes three things simultaneously: it demonstrates hands-on understanding of SOC 2 audit workflows, it extends Sentinel GRC Ops with a new capability, and it produces a portfolio piece I can show hiring managers as evidence of audit process knowledge. The build itself is the credential — a shipped, working audit simulation is worth more than a line on a resume that says "familiar with SOC 2." Target completion: August 2026.

---

## Rows killed

- ~~"No Python experience"~~ — KILLED. Sentinel GRC Ops is written in Python. This was an aspiration in the import draft, not a real gap. Removed because the evidence already exists in resume.json > proj_001.
