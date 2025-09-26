SIEM & Triage Labs
Queries, correlation, and prioritization exercises for Tier‑1 SOC workflows.

What goes here
Basic and intermediate searches, alert triage mini‑reports, and false‑positive tuning notes.

A one‑page cheatsheet with queries for processes, logons, and network activity.

Deliverables checklist
 []  Two alert triage mini‑reports with screenshots and decisions.

 []  SIEM cheatsheet (Splunk/KQL) with 10–15 core queries.

 []  ATT&CK mapping per detection.

NOTES:
Roles and first actions: Level 1 handles initial alert triage, validates signal vs. noise, and documents the 5 Ws before escalating; only escalate with evidence attached.

Escalation path: L1 → L2 for deeper correlation; L2/L3 involve IR when impact or persistence is suspected; loop in Security Engineer for tooling or rule changes.

Severity handling: work Critical → High → Medium → Low; start with containment suggestions for Critical (e.g., isolate host, block IOC) even before handoff if playbook allows.

Communication artifacts: every ticket must include a summary, 5 Ws, key IOCs (IPs/domains/hashes), screenshots or log excerpts, and a recommended next step; avoid vague titles.

Handover checklist: for each closed/handed alert, confirm linked cases, duplicate suppression, rule feedback to Detection Engineer, and note if a playbook update is needed.
