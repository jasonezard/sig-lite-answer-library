# The Three Answer Patterns (and the ones that fail)

Nearly every defensible questionnaire answer takes one of three shapes. They correspond to the worked examples `EX-1`–`EX-3` in the template.

## Pattern 1 — The cited "yes" (EX-1)

> **Q:** Do you review user access rights on a defined schedule?
> **A:** Yes — access reviews run quarterly across all production systems; the most recent review completed in May 2026.
> **Evidence:** Access Control Policy v2.1, §4; Q2-2026 access review report

What makes it work:
- **A schedule, not an adverb.** "Quarterly" survives scrutiny; "regularly" invites a follow-up.
- **A dated, recent instance.** The most recent review proves the schedule is real, not aspirational.
- **A citation a reviewer could request.** Name the document and section. If you can't, the answer isn't ready.

## Pattern 2 — The tested control (EX-2)

> **Q:** Do you have a documented incident response plan that is tested?
> **A:** Yes — documented IR plan with severity definitions and escalation paths; last tabletop exercise ran in March 2026.
> **Evidence:** Incident Response Plan v1.3; tabletop exercise notes 2026-03

"Documented" and "tested" are different claims — reviewers check for both. The pattern: name the artifact, name the test, date the test. A plan that has never been exercised is Pattern 3 wearing Pattern 2's clothes; answer it honestly as a gap with the test on your roadmap.

## Pattern 3 — The honest gap with a compensating control (EX-3)

> **Q:** Do you test backup restoration?
> **A:** Partially — automated daily backups with monthly restore verification for the primary database; full DR failover test is on the roadmap for Q4 2026.
> **Evidence:** Backup & Recovery Runbook; restore-verification log

This is the pattern that separates vendors who pass reviews from vendors who get caught. The structure:

1. **"Partially" or "No," said plainly.** Reviewers read hundreds of these; hedged non-answers are a flag.
2. **The compensating control you run today** — the thing that manages the same risk right now.
3. **A dated roadmap item** — not "planned," but "Q4 2026."

A truthful gap with a compensating control usually passes. A discovered lie fails the review and every future one.

## Anti-patterns — answers that fail reviews

| Anti-pattern | Why it fails |
|---|---|
| **The aspirational yes** — "Yes" for a control that's planned, partial, or abandoned | One probing follow-up ("show us the last report") collapses it, and your credibility with it |
| **The uncited yes** — "Yes." | Unverifiable, so the reviewer either escalates or discounts it. Also rots silently: nobody remembers next quarter why it was "yes" |
| **The essay** — 300 words where one sentence + citation would do | Reads as evasion; buries the actual claim; creates inconsistencies between answers |
| **The copied answer** — pasted from another company's filled questionnaire | Internally inconsistent with your real stack within five questions. Reviewers pattern-match this instantly |
| **The "N/A" dodge** — N/A on questions that clearly apply | Treated as a "no" plus a process flag |

## One habit that compounds

Re-verify before every submission. The `Last verified` column exists because true answers become false quietly — a tool gets dropped, a policy lapses, an owner leaves. A library you re-verify quarterly stays an asset; one you don't becomes a liability with citations.
