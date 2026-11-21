---
name: incident-summary
description: Draft a short incident status update or handoff from provided notes. Use when the user asks to summarize service impact, mitigation, recovery evidence, and next steps for an incident.
---

# Incident summary

1. Identify the audience and use the language requested by the user. If unspecified, use the language of the request and default to an internal engineering handoff.
2. Use only the supplied evidence. State user-visible impact, the latest observed status, and the timestamp and time zone if known. Do not infer the time zone.
3. Include a short timeline when it helps explain the impact, mitigation, or recovery. Distinguish what was done from what is proposed.
4. Label suspected causes as hypotheses. Do not declare recovery without evidence. Flag missing measurements or conflicting notes as unknown.
5. List next steps. Include an owner or ETA only when provided; otherwise mark it unassigned or not confirmed.

Return the draft with **Status**, **Impact**, **Timeline**, and **Next steps**. Omit sensitive identifiers and raw secrets. Do not send the draft or change any systems.
