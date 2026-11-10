<div align="center">

# LightPBX Materials Hub

**Sales, support, operations and development materials for LightPBX by Cellact**

[Sales](sales/README.md) · [Support](support/README.md) · [Operations](operations/README.md) · [Development](development/README.md) · [Assets](assets/README.md)

</div>

---

## About LightPBX

LightPBX is Cellact's cloud business phone system (PBX). A business gets professional phone numbers, an extension for every team member, and full control over who answers each number: one person, a ring group, or (on Pro) a call menu (IVR).

- **Arnacon is where teams use it.** Calls, extensions and transfers run in the Arnacon app on iPhone, Android and the web.
- **Extension 500 is the admin.** The admin manages the system from Arnacon in admin mode or from the browser at [app.lightpbx.com](https://app.lightpbx.com/).
- **Sign-up** is at [lightpbx.com](https://lightpbx.com/).

This repository is the single, organised home for LightPBX materials used by the Cellact team.

## Main menu

| Section | What you will find | Audience |
|---|---|---|
| 💼 [Sales](sales/README.md) | Sales & setup guides, pricing explanations, demo scripts, pitch material | Sales, partners |
| 🛟 [Support](support/README.md) | FAQ, troubleshooting, step-by-step setup guides | Support, customer success |
| ⚙️ [Operations](operations/README.md) | Customer onboarding, numbers & provisioning (high level), billing process | Operations, account management |
| 🛠️ [Development](development/README.md) | Architecture overview, integrations, release notes | Engineering, product |
| 🎨 [Assets](assets/README.md) | Logos, screenshots, diagrams, brand files | Everyone |
| 📄 [Document template](docs/_template.md) | Starting point for any new document | Contributors |

## Latest materials

<!-- Newest first. Add one line per new document: date — title (language) — link. Keep the 10 most recent. -->

| Date | Document | Language | Section |
|---|---|---|---|
| 2026-11-10 | [LightPBX sales & setup guide (Markdown)](sales/guides/lightpbx-sales-setup-guide-he-2026-11-10.md) | Hebrew | Sales |

See the [CHANGELOG](CHANGELOG.md) for the full history.

## Repository layout

```text
lightpbx/
├── README.md                ← you are here (main menu)
├── CONTRIBUTING.md          ← how to add and maintain materials
├── CHANGELOG.md             ← history of changes
├── NOTICE.md                ← copyright notice (all rights reserved)
├── sales/
│   └── guides/              ← sales & setup guides
├── support/
│   └── setup-guides/        ← step-by-step customer setup guides
├── operations/
├── development/
├── assets/                  ← images, logos, diagrams
├── docs/_template.md        ← template for new documents
└── .github/workflows/       ← automatic link check
```

## Contributing

1. Pick the right folder (see [CONTRIBUTING.md](CONTRIBUTING.md#folder-rules)).
2. Name the file in `kebab-case`, with a date or version suffix for versioned documents, e.g. `pricing-overview-en-2026-12-01.md`.
3. Start from [`docs/_template.md`](docs/_template.md).
4. Register the file in that folder's `README.md` and in **Latest materials** above, and add a line to the [CHANGELOG](CHANGELOG.md).
5. Run through the [privacy checklist](CONTRIBUTING.md#privacy-checklist) — **this repository is public**.

Every push and pull request runs an automatic [link check](.github/workflows/link-check.yml), so broken internal links are caught early.

## Contact

Sales and demos: sales@cellact.com · Product site: [lightpbx.com](https://lightpbx.com/)

---

<sub>All rights reserved © Cellact. The materials in this repository are published for reference only; no licence to copy, modify or redistribute is granted. See [NOTICE.md](NOTICE.md).</sub>
