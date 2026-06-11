# SIG Lite Answer Library Template

**A free, ungated CSV template for building a reusable security-questionnaire answer library** — structured around SIG-style risk domains, with evidence-citation columns and three worked examples showing what a defensible answer actually looks like.

No email wall. No watermark. Open [`sig-lite-answer-library-template.csv`](sig-lite-answer-library-template.csv) in Excel or Google Sheets and start. (GitHub renders it as a table right in the browser — [preview it here](sig-lite-answer-library-template.csv).)

## Who this is for

You sell to bigger companies, and one of them just sent a vendor security questionnaire — a SIG Lite, a CAIQ, a homegrown VSA spreadsheet — with a deadline attached. You'll answer 300 questions this quarter and 300 nearly identical ones next quarter. The teams that stop suffering are the ones that maintain an **answer library**: every answer written once, cited, owned, and dated, then mapped onto whatever spreadsheet arrives next.

This template is the empty library, plus the three answer patterns that make it work.

## What's in it

| | |
|---|---|
| **30 starter questions across 14 SIG-style risk domains** | Access control, incident response, application security, business resilience, cloud hosting, privacy, third-party management, and more. The wording is ours — swap in your customer's exact questions as they arrive. |
| **Three worked examples (EX-1 … EX-3)** | The three shapes nearly every real answer takes: a clean cited **"yes"**, a **tested-control** answer, and an honest **gap answered with a compensating control** and a dated roadmap. Expanded in [`examples/ANSWER_PATTERNS.md`](examples/ANSWER_PATTERNS.md). |
| **The columns that make answers reusable** | `Evidence / citation` · `Owner` · `Status` · `Last verified`. The citation column is the whole trick — *"Yes"* expires; *"Yes, per Access Control Policy §4, reviewed May 2026"* survives into the next questionnaire. |

## How to use it

1. **Fill in what's true today.** Answer only to controls that actually run. Aspirations go in notes, not the answer cell.
2. **Cite as you go.** Every answer names the policy, tool, or dated report behind it. Uncited answers are the first to rot.
3. **Tag the gaps honestly.** Empty rows are your gap list — the same list a reviewer would find anyway. Pair each gap with the compensating control you run today (see EX-3).
4. **Assign owners and verify dates.** An answer nobody owns is wrong by next quarter. Re-verify before each submission.
5. **When the real questionnaire arrives,** map its questions to your library rows, copy, adapt wording, submit. Teams that maintain the library reuse most of it per questionnaire.

The answer patterns — including the anti-patterns that fail reviews — are documented in [`examples/ANSWER_PATTERNS.md`](examples/ANSWER_PATTERNS.md).

## What this is **not**

SIG and SIG Lite are products of [Shared Assessments](https://sharedassessments.org/), and the official question set is licensed. **This repository does not reproduce it**, and you should be skeptical of any free download that claims to. You'll receive the real SIG from your customer. What this template provides is the *answer side* — your library, organized around comparable domains, so that when the official spreadsheet lands, most of your answers are already written and cited.

## If the deadline is this week

A template helps you build the library over weeks. It does not help when the SIG arrived Tuesday and procurement wants it back Friday. For that there's [Questionnaire Rescue](https://thinsky.com/saq3/): we read the questionnaire and your actual security posture in parallel, draft truthful answers citing your real controls, and hand back both the completed document and the reusable library — a typical SIG in about 3 days.

## Related reading

- [The guide behind this template](https://thinsky.com/guides/sig-lite-template/) — full context and FAQ
- [SIG questionnaire, explained](https://thinsky.com/guides/sig-questionnaire/)
- [Security-questionnaire help: DIY vs outsourcing](https://thinsky.com/guides/security-questionnaire-outsourcing/)

## Contributing

Additions welcome — new starter questions in un-covered domains, better worked examples, translations. See [CONTRIBUTING.md](CONTRIBUTING.md). Please do **not** submit official SIG/CAIQ question text (licensing).

## Licence

[CC BY 4.0](LICENSE) — use it, adapt it, share it, including commercially; keep the attribution.

---

Maintained by [ThinSky](https://thinsky.com) — managed open-source security for Canadian SMBs (Wazuh, Keycloak, Teleport, OpenVAS, Velociraptor), Virtual CISO, and compliance readiness (SOC 2 · ISO 27001 · PIPEDA).
