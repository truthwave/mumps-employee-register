# 🤖 Employee Roster You Understand in Seconds

> **Registration: 10 seconds. Search: 0.2 seconds. Output: 1 click.**
> A roster's value is determined by its speed.

---

## Experience (Three Key Actions)

- **Register**: Enter name, phonetic reading, and date of birth without hesitation. Automatically converts to Japanese calendar format.
- **Search**: Perform fuzzy searches by department, position, or name. Instantly reach the desired personnel.
- **Output**: Direct CSV export. Immediately paste into HR/General Affairs forms.
> The goal isn't “input.” **It's to speed up decision-making.**

---

## Before → After (Estimated)

- New registration: 1 minute → **10 seconds**
- Name/department search: 10 seconds → **0.2 seconds**
- Monthly CSV output: 15 minutes → **1 click**
*Times may vary depending on environment and data volume.

---

## Implementation Highlights

- **Batch Import**: Import external CSV department/title master data and format into a list
- **Japanese Era/Gregorian Calendar**: Input in Gregorian, display selectable (Japanese Era/Gregorian)
- **Fuzzy Search**: Hits partial/prefix matches, supports type-ahead
- **Export**: Instant CSV output of registered data

---

## Security and Operations

- Authentication: Supports internal SSO (SAML/AD integration) or device-based constraints
- Permissions: Assign view/edit roles per department
- Auditing: Records update operations in audit logs (who/when/what)
> Move beyond “no password management” to “**password-independent enterprise authentication**”.

---

## Technical Notes (Minimal)

- Core: MUMPS (high-speed KVS)
- Integration: CSV input/output, anticipates future **Web UI (Vue / Django)** expansion
- Data: Lightweight schema for employees/departments/positions, indexes applied to name, department, position

---

## Roadmap

- Web interface (mobile-optimized)
- Cloud Sync (encrypted/incremental transfer)
- External Integration API (payroll/attendance)

---

## 🧑‍💻 Creator

**[Truth Wave ― 真理の波](https://github.com/truthwave)**  
▶ Projects featuring AI × Practical Efficiency × Design currently featured

## Feel Free to Contact Us
[📩 Inquiries & Quotes](mailto:realmadrid71214591@gmail.com)

---

> **Don't add. Reduce uncertainty.**
> Ledgers are completed with “speed” and “certainty.”
