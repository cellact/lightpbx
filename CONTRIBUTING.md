# Contributing to the LightPBX Materials Hub

Thank you for keeping LightPBX materials organised. This guide keeps the repository easy to navigate and safe to publish. **This repository is public — read the [privacy checklist](#privacy-checklist) before every commit.**

[⌂ Back to main menu](README.md)

## Folder rules

| Folder | Put here | Do not put here |
|---|---|---|
| [`sales/`](sales/README.md) | Sales & setup guides, pricing explanations, pitch decks, demo scripts, objection handling | Customer-specific offers or quotes |
| [`sales/guides/`](sales/guides/README.md) | Long-form sales and setup guides (one file per version/language) | Short one-off notes |
| [`support/`](support/README.md) | FAQ, troubleshooting, known issues, customer-facing how-tos | Individual tickets or customer conversations |
| [`support/setup-guides/`](support/setup-guides/README.md) | Step-by-step setup guides for a single task | General product explanations |
| [`operations/`](operations/README.md) | Onboarding process, numbers & provisioning overview, billing process | Credentials, internal endpoints, number inventories |
| [`development/`](development/README.md) | Architecture overview, integration descriptions, release notes | Source code, secrets, configuration files |
| [`assets/`](assets/README.md) | Logos, screenshots, diagrams, brand files referenced by documents | Screenshots that show real customer data |
| [`docs/`](docs/_template.md) | Shared templates | Content documents |

If a document fits two folders, put it where its **main reader** works and link to it from the other folder's README.

## Naming conventions

- Use `kebab-case`: lowercase letters, digits and hyphens only — `call-routing-overview.md`, not `Call Routing Overview.md`.
- Add a **language code** when a document exists in more than one language: `-he`, `-en`, `-nl`.
- Add a **date suffix** (`YYYY-MM-DD`) or **version suffix** (`-v1.2`) to versioned documents such as guides, price sheets and decks:
  - `lightpbx-sales-setup-guide-he-2026-11-10.md`
  - `pricing-overview-en-v1.0.md`
- Living documents that are always kept current (for example `faq.md`) do not need a suffix; record changes in the [CHANGELOG](CHANGELOG.md).
- Keep a PDF and its Markdown version side by side with the **same base name**.
- Assets: `<topic>-<description>.<ext>`, e.g. `logo-lightpbx-dark.svg`, `screenshot-team-list-he.png`.

## How to add a document

1. **Create the file** in the right folder, starting from [`docs/_template.md`](docs/_template.md).
2. **Fill in the header** (title, owner, audience, language, version/date, status).
3. **Use relative links** to other files in this repository (`../support/faq.md`), never absolute GitHub URLs, so links keep working if the repository moves.
4. **Hebrew or other right-to-left content:** wrap the document body in `<div dir="rtl">` … `</div>` with a blank line after the opening tag and before the closing tag.
5. **Register it in the folder index:** add a row to the contents table in that folder's `README.md`.
6. **Register it in the main menu:** add a row at the top of **Latest materials** in the root [`README.md`](README.md) (newest first, keep the 10 most recent).
7. **Add a CHANGELOG entry** under the current date in [`CHANGELOG.md`](CHANGELOG.md).
8. **Run the privacy checklist** below.
9. Commit with a clear message, e.g. `Add Dutch FAQ (2026-12-01)`. The link-check workflow runs automatically; fix any broken link it reports.

### Replacing a document with a newer version

- Add the new version as a new file with a new date/version suffix.
- Update the folder index and Latest materials to point to the new version.
- Move the old version to an `archive/` subfolder inside the same folder (create it if needed) and mark it as superseded in the folder index, or delete it if it has no reference value.

## Privacy checklist

Before every commit, confirm that the change contains **none** of the following:

- [ ] Customer or prospect names, e-mail addresses or phone numbers
- [ ] Real phone numbers from live or demo systems (use placeholders such as `+972 XX-XXX-XXXX`)
- [ ] Discount, coupon or promotion codes
- [ ] Passwords, SIP credentials, API keys, tokens, invitation links or QR codes from real accounts
- [ ] Internal URLs, backend endpoints, server names, cloud bucket or project names
- [ ] Detailed provisioning steps, number inventories or carrier configuration
- [ ] Screenshots showing any of the above (blur or crop them first)
- [ ] Personal data of staff beyond what is already public

If in doubt, leave it out and ask the repository owner.

## Style

- Write for the reader of the folder: short sections, clear headings, numbered steps for procedures.
- State the date when prices or terms were checked.
- Prefer tables for comparisons and plans.
- Use icons sparingly.

---

<sub>All rights reserved © Cellact. See [NOTICE.md](NOTICE.md).</sub>
