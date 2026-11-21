# GKZ Skills

Practical Agent Skills for DevOps, automation, and client work, maintained by GKZ.

รวม Skill สำหรับงาน DevOps, Automation และงานลูกค้า พร้อมตัวอย่างที่ลองใช้ได้โดยไม่ต้องใช้ข้อมูลจริง

## Skills

| Skill | What it does |
| --- | --- |
| [incident-summary](skills/incident-summary/SKILL.md) | Turns incident notes into a concise status update, with facts, unknowns, and next steps kept separate. |

Each skill follows the [Agent Skills format](https://agentskills.io/specification). To try one, copy its folder into the skills directory used by your agent and ask it to use that skill. For example:

> Use incident-summary to draft a Thai status update. At 10:05, checkout errors rose from 1% to 8%. At 10:12, the team rolled back. By 10:18, errors returned to 1%. The root cause is still under investigation.

The examples in this repository are fictional. Remove customer details, credentials, and sensitive infrastructure data before sharing incident notes.
