ATT&CK Layers and Mapping Notes
Purpose: track coverage against the Enterprise matrix and tie detections/playbooks to concrete TTPs for interview‑ready evidence.

How this folder is used
Store ATT&CK Navigator .json layers for techniques covered by labs and detections.

Add short notes per technique: log sources, example queries, validation steps.

Getting started
Create a new layer in ATT&CK Navigator, select Enterprise, and save it here as enterprise-baseline.json.

For each covered technique, include: Technique ID, what to log, how to query, and how to simulate.

Example note template
Technique: T1059 Command and Scripting Interpreter.

Logs: Windows Event ID 4688 / Sysmon 1; Linux process creation.

Query: detect suspicious interpreters with network calls and encoded commands.

Validation: simulate benign and malicious runs to tune false positives.
