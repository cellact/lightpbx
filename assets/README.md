# 🎨 Assets

Images, logos, diagrams and brand files used by documents in this repository.

[⌂ Main menu](../README.md)

## Contents

| Asset | Used in | Notes |
|---|---|---|
| *No assets yet* | — | — |

## Suggested structure

```text
assets/
├── logos/         ← logo-lightpbx-dark.svg, logo-arnacon.svg, …
├── screenshots/   ← screenshot-<screen>-<lang>.png
└── diagrams/      ← diagram-<topic>.svg / .png
```

## How to add an asset

1. Name it `<type>-<description>[-<lang>].<ext>` in kebab-case, e.g. `screenshot-team-list-he.png`.
2. Prefer SVG for logos and diagrams, PNG for screenshots; keep files small (ideally under 1 MB).
3. **Screenshots must not show real customer data, phone numbers, e-mail addresses, invitation links or QR codes** — blur or crop first. See the [privacy checklist](../CONTRIBUTING.md#privacy-checklist).
4. Add a row to the table above, and link the asset from documents with a relative path, e.g. `![Team list](../assets/screenshots/screenshot-team-list-he.png)`.
