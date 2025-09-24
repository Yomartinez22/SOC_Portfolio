# SOC Portfolio — Blue Team from Zero

Goal: Build, in 4–6 months part‑time, a junior SOC/Blue Team profile with solid fundamentals, realistic hands‑on practice, and a verifiable 6–8 piece portfolio before applying in Switzerland.
Method: Follow a structured SOC Analyst Learning Path with guided modules and labs, document everything with reproducible writeups, and map coverage to MITRE ATT&CK.

## Weekly cadence
- 60–90 min theory from the active module (short notes and ATT&CK mapping).
- 2–3 h hands‑on labs/challenges (phishing/web, SIEM/triage, DFIR, hunting).
- 30–60 min documentation: one writeup or playbook/cheatsheet update.

## Month 1 milestones
- SOC fundamentals and alert flow; core ATT&CK tactics/techniques.
- 2 labs: phishing analysis and web attack detection with writeups.
- SIEM 101: basic queries and a triage cheatsheet.
- 1 short IR playbook (detection → containment → recovery).
- Initial ATT&CK layer with 10 techniques and log sources notes.

## Portfolio deliverables
- Writeups: 6–8 cases (phishing/web, SIEM/triage, DFIR, hunting) with reproducible steps.
- IR playbook: 1–2 pages with escalation criteria and report templates.
- SIEM cheatsheet: Splunk/KQL queries and common triage patterns.
- Detection rules: at least 2, ATT&CK‑mapped and validated in the home lab.

## Repository structure
- docs/attck → ATT&CK .json layers and mapping notes.
- docs/metrics.md → hours, completed labs, techniques covered.
- docs/resources.md → study links and quick references.
- labs/phishing-web → writeups and artifacts.
- labs/siem-triage → queries, screenshots, mini‑reports.
- labs/dfir-hunting → timelines, findings, detection improvements.
- playbooks/ → IR playbook and report templates.

## Study plan (pre‑application)
- Frameworks and concepts: MITRE ATT&CK, Cyber Kill Chain, IR lifecycle, common SOC alerts.
- Systems and logs: Windows (logon, process, registry, Sysmon), Linux (auth/sudo/cron), basic web logs.
- SIEM: ingestion/normalization, queries, rules, prioritization, threat intel enrichment.
- Common threats: phishing, initial malware, basic lateral movement, frequent persistence.
- Early hunting: hypotheses, baselines, TTPs vs IoCs, documenting findings.

## Platform and modules
- Path: SOC Analyst Learning Path covering ATT&CK, SIEM, IR, malware, and guided labs.
- Note: log weekly progress per module in docs/metrics.md.

## Metrics and tracking
- Planned hours/week: 4–6; actual: update every Sunday.
- Labs completed this week: count and links to writeups.
- New ATT&CK techniques covered: brief list with IDs.

## Next steps (Week 0)
- Day 1: create repo and structure, open account on the SOC path, prep an empty ATT&CK Navigator layer.
- Day 2: annotate 5 frequent ATT&CK techniques with “which logs to look at.”
- Day 3: draft a 1‑page triage map for common incidents.

## Quick references
- MITRE ATT&CK — Get Started: official fundamentals and resources.
- ATT&CK Navigator — step‑by‑step layer creation and export.
- SIEM — core concepts and 2025 capability checklist.
- SOC interviews — checklists and preparation.
