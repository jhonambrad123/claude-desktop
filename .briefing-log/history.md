# Daily Tech Lead Briefing — History Log

---
## Briefing: 2026-06-11

### P1 items
- **Veolia UK Driver self-service QR ticket** (Philippe Barbotin, 10 Jun) — Feasibility + complexity assessment requested by **end of next week (~19 Jun)**. To: Pangkaj, Gokul, Jhon, David Patterson. Existing pieces (signature capture, PDF generation, QR lib in UI) reduce scope; new build = secure driver-facing link + per-ticket unguessable code + QR on signature screen. Action: align with Gokul/Pangkaj on a sizing reply.
- **Sims onsite — uncompleted transfer-in tickets** (Auslynn Anderson, 10 Jun 22:04 UTC, follow-up to her first issue which Jhon resolved) — Two transfer-in tickets show "complete" on the scale ticket printout but jobs remain uncompleted; DB shows no errors. Auslynn is onsite at Sims through 19 Jun. Action: investigate root cause and reply early today PH so she has it when she's back online in NJ.
- **ADO 853586 — patch candidate?** (Auslynn, Teams meeting chat, 10 Jun) — Encountered during Sims testing; already Closed. Action: confirm with Aindreas whether it can be pulled into the upcoming patch.

### P2 items
- **PR 243616 review request** (Gokul Muthu, Teams, 10 Jun 16:54 UTC) — Bug 855971 (DEV-27672) Guided Scale reuses voided scheduled ticket instead of creating a new one. Action: review and respond.
- **DEV approvals queued** — DEV-27709 (Tomlinson Scale payment $0.01 balance, John Cadampog, P2), DEV-27710 (Tomlinson scale ticket print incorrect %, Kristian, P2), DEV-27680 (Anchorage payment type on scale ticket, Astrid, P2), DEV-27672 (Sims voided scheduled inbound retry, Auslynn, P2), DEV-26122 (Sims outbound jobs missing scheduled ID, Auslynn, P2), DEV-27662 (Berlin scale material display, Mats, P0). All co-approvers: Aindreas, Gokul, David Patterson. Action: review and approve/comment.
- **John Neigel grading-screen feedback on Story 831916 / DEV-26204** (10 Jun, after Québec UAT install) — 4 issues: (1) GS Entry Field shows DB field name not "Veh Description"; (2) Mobile Grading App working as expected (positive); (3) Some Mobile App settings fields (Yard Location) don't appear on the card; (4) "Veh Description" missing on Desktop view. He can't add to DEV/Story directly. Action: triage with Paul, log into ADO, decide if hotfix vs next sprint.
- **Time-off approvals to action** — Denise Cabardo 17–19 Jun, Geraldine DelaCerna 17 Jun. Action: approve in HRIS.
- **HR ticket REQ-122585 (Resource management mail list)** — opened by Jhon, ack received. Monitor for response.

### Today's calendar (PH time, UTC+8)
- All-day: Geraldine OOO (11–12 Jun)
- 13:30–16:30 — Focus time (own-block)
- 14:00–14:30 — Jhon / Michael 1:1
- 14:45–15:15 — Jhon / Eloise 1:1
- 16:00–16:30 — Metals Stand-up (Jhon hosts)
- 16:30–17:00 — Recycling Stand-up (Patterson)
- 17:00–17:30 — Discussion w/ Ajay: Multi lines per profile in GS
- 17:30–18:00 — Recycling CFD Review (Patterson)
- Cancelled: Refinement For Metals (replaced by POD refinements), Regression Test Coverage MR Test Plan, Scale CR Review (demo clash)

### Unresolved carry-overs
- *First run — no prior carry-overs.*

### Notes
- First run of the routine; baseline established.
- Heavy day on standups + 1:1s. Two team members OOO today (Geraldine, Eloise on 12 Jun, Jan on 12 Jun).
- Auslynn is onsite at Sims through 19 Jun (PTO 22 Jun) — responses from her are async, but she's the customer-facing escalation point so her threads have urgency.
- Org change announced: Muthu Kumar leading new Quality Engineering Team (Patterson FYI'd).
- PH team returning to 3/2 office schedule (Ingo Hansen town hall).
- Claude Code policy change starts today (11 Jun): Sonnet default, Opus paused org-wide.
