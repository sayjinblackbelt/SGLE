# SGLE — Waiting List Management System

[🇧🇷 Português](README.md) | 🇺🇸 English | [🇪🇸 Español](README.es.md)

**Started:** 2025  
**Version:** 1.0.0  
**Status:** Under continuous development  
**Developer:** Filipe Gimenes de Morais

## 💼 Project origin

SGLE began in **2025** after identifying **unmet demand** and the need to improve the organization and follow-up of people waiting for available places in activities and services.

The need was initially discussed during a **management committee meeting**. From there, the solution was planned jointly with **pedagogical coordination**, while the definition of workflow rules and requirements included collaboration from **two social work professionals**.

The practical challenge of transforming a predominantly manual process into a structured digital workflow was one of the factors that encouraged deeper study of **automation, Google Workspace, and Google Apps Script**.

SGLE therefore brings together two dimensions:

- a response to a real management and organizational need;
- a practical project for learning and developing automation skills.

To preserve privacy and the identity of the original organization, this repository uses a generic approach and does not identify the institution where the demand was observed.

## Objective

The Waiting List Management System (SGLE) aims to digitize and organize the registration of learners waiting for available places in activities and services with limited capacity.

The system replaces manual waiting-list registration with an integrated workflow between Google Forms and Google Sheets, with planned evolution toward Google Apps Script automation, metrics, dashboards, and support for vacancy management.

SGLE **does not replace in-person enrollment**. The form records the learner on the waiting list; enrollment continues to be completed in person, and activities are defined according to availability at the time of enrollment.

## Mission

Transform the manual waiting-list registration process into a simple, standardized, and automated system, reducing rework, data-entry errors, and administrative time while improving the quality of management metrics.

## Target audience

- NGOs and civil society organizations
- Social projects
- Educational institutions
- Community centers
- Public agencies and departments

## Specific objectives

- Digitize waiting-list registration.
- Standardize data collected by the team.
- Automatically record registration date and time.
- Automatically calculate age.
- Organize the queue by registration date.
- Support invitations for in-person enrollment.
- Record process status.
- Generate metrics on unmet demand.
- Support analysis of activity capacity and availability.
- Enable future evolution toward enrollment, attendance, and activity-management modules.

## Operational flow

```text
Parent / guardian / family
        ↓
Responsible team
        ↓
Waiting-list registration
        ↓
Google Forms
        ↓
Google Sheets
        ↓
Data processing and organization
        ↓
Waiting list / Unmet demand
        ↓
Availability arises
        ↓
Invitation
        ↓
In-person enrollment process
        ↓
Activities defined according to availability
```

## Planned architecture

```text
Google Forms
      ↓
Google Sheets
      ↓
Google Apps Script
      ↓
Data layer / business rules
      ↓
Administrative dashboard
      ↓
Reports
      ↓
PWA (future)
```

## Technologies

- Google Forms
- Google Sheets
- Google Apps Script
- HTML5
- CSS3
- JavaScript
- Google Charts
- Material Icons

## Planned structure

```text
waiting-list-management-system/
├── README.md
├── README.en.md
├── README.es.md
├── CHANGELOG.md
├── ROADMAP.md
├── DOCUMENTACAO.md
├── .gitignore
│
├── backend/
├── frontend/
└── documentacao/
```

During the initial phase, the priority is documentation and the Forms → Sheets workflow. Code files will be added as automations are implemented.

## Fundamental rule

**Waiting List ≠ Enrollment.**

SGLE records the intention to join and organizes unmet demand. Enrollment takes place in person only when availability exists and after the procedures defined by the responsible team.

## Privacy and data protection

The project may process personal and potentially sensitive information. The public repository must contain only code, documentation, and fictional or sample data.

Never publish on GitHub:

- real participant names;
- guardian names;
- phone numbers;
- addresses or identifying data;
- disability or health information;
- real spreadsheets from the original context;
- credentials, tokens, or API keys.

Implementation should follow applicable privacy and data-protection principles, including purpose limitation, necessity, security, and access control.

## License

This project was developed from a real management and organizational need, with practical, educational, and technical demonstration purposes. A specific open-source license may be defined in a later stage if appropriate.
