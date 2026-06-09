# Daily Briefing History

This file persists context across daily briefing runs.

---
## Briefing: 2026-06-09

### P1 items
- **DEV-27655 (Priority 0)** — Sims Metal Management: Floor Scale Price Override incorrectly generates Charge instead of Payable on Supplier Tickets. NetSuite approval request from Auslynn Anderson. **Action: review and approve/reject.**
- **DEV-27104 (SIMS)** — Failed by customer. Philippe Barbotin update: 5-sec non-configurable delay introduced is not enough; out-of-sync issues with Scale still occur intermittently during grading material deductions. **Action: track team's next iteration, advise.**
- **#841021 SIMS Patch (Richard Chico)** — Needs approval on InventoryManagement PR 242940 (develop branch). Patch 2026-05 (19-21) Patch 3, ERP_CI 9.10.4 / Scale 9.10.1. **Action: review and approve PR.**
- **DEV-27547 (P1, Katelyn Steigerwalt)** — Active P1 call coordinated by Gokul Muthu yesterday; Teams meeting was set. Confirm follow-through and resolution status.

### P2 items
- **Graeme Sutters** — Pending reply on PRD vs ITD question (PR 241093 docs(spec): 851585 Account Centric Scale Consolidated Screen Part 2). He's also OOO note received — clarify before he's out.
- **Aira Pega** — Questions and clarifications on Feature 844923 (GAL-43a: Material Mgnt – Display shipper's weights on inbound transaction log). Needs your input.
- **DEV-26204 (John Neigel)** — Vehicle reference field for grading screens (Québec). FF not yet enabled in his environment; John following up with that group but may circle back.
- **Bug 853358** — Regression Bug: Material Gross Weight of Material with Deduction updated upon ticket completion. Assigned to you (Azure DevOps).
- **DEV-2163 (Veolia ES UK, P3)** — Approval request from David Stapleton: Exclude weighing tickets from needing WCL based on material profile.
- **DEV-11215 (HRS MILJØ, P3)** — Approval request from Elliot Buckley: Printout in DAT (Scale Web UI).
- **Scale CR Review** — Meeting scheduled with Aindreas Hodgins, Gokul, Paul, Philippe. Tshirt sizing and planning of incoming CRs.
- **Material deduction refactor** — Confirmed Kurt Aaron Cabrera will not fix remaining deduction issue in his pod; assigned to you, moved to pod 2 and will be fixed in your refactor.

### Unresolved carry-overs
- First run — no prior history.

### Notes
- High volume of CI build-success notifications from Azure DevOps (POD-4 pipelines) — noise filter applied.
- Paul MacDonald OOO until 11 June; Graeme Sutters also OOO (per OOO email).
- Ingo Hansen flagged Mindanao earthquake (8 June) and the Wednesday town hall (10 June) — non-actionable but socially worth noting.
- Heavy SIMS-related load today: three distinct SIMS issues (DEV-27655 P0, DEV-27104 grading latency, #841021 patch). Prioritize SIMS thread.

