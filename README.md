# Traditional Model-Driven Banking Software System

Software engineering course project (AIUB, Spring 25-26, Group G6) that specifies and designs a role-based banking system using the **V-Model** life cycle.

This repository contains **project documentation, not application code**: the full project report and the Trello backlog used to plan the work.

## What's inside

| Path | Contents |
| --- | --- |
| [`SoftwareProjectReport.pdf`](SoftwareProjectReport.pdf) | 42-page report: proposal, Gantt chart, SRS, design, Git workflow |
| [`Trello/`](Trello) | 24 user-story cards, grouped by board column (`Backlog`, `To Do`, `In Progress`) |

### Report sections

1. **Project proposal** — the problem with manual, disconnected legacy banking workflows, and why the V-Model was chosen (each development phase is paired with a matching test phase, which suits security- and compliance-heavy financial software).
2. **Timeline** — Gantt chart.
3. **Software Requirements Specification** — scope and features, user story table, and a requirements traceability matrix covering functional and non-functional requirements.
4. **Software design** — system design and UI wireframes made in Figma.
5. **Git workflow** — feature branches per Trello card, peer review before merging to `main`.
6. **Conclusion**

## System scope

The design covers four roles:

- **Admin** — create staff profiles, monitor login sessions, view the audit trail
- **Manager** — review loan applications, manage card requests, generate reports, view customers
- **Teller** — cash deposits and withdrawals, daily cash summary
- **Customer** — view accounts, update contact details, internal and external transfers, apply for and track loans, request cards, download statements

Shared requirements include login, role-based dashboards, password change and recovery, automatic balance updates, transaction status tracking, and digital receipts.

## Team

Musa Abdullah ([@s21gem](https://github.com/s21gem)), Farhat Bin Munsur, Najiat Islam Rishad, Alvi Al Faris.
