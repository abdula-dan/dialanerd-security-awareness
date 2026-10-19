# Dial a Nerd — Security Awareness Training

Internal staff Security Awareness Training site for **Dial a Nerd**. Derived from
the template `abdul-dan/CoPilotCode` (wired as the `upstream` remote).

- Live site: `docs/index.html` — self-contained, no build step.
- Branding: `CUSTOMER = "Dial a Nerd"`, `LOGO = "assets/dialanerd-logo.png"`.
- Campaign window: **19 Oct 2026 → 26 Oct 2026** (one week).
- Results submit to: **internalit@dialanerd.co.za**.

## Publish (GitHub Pages)

Settings → Pages → Source: **Deploy from a branch**, Branch: **main** / **/docs**.
Link: `https://abdula-dan.github.io/dialanerd-security-awareness/`

## Pull template improvements later

```sh
git fetch upstream
git merge upstream/main
git push origin main
```

## Reporting

Staff click **View my results → Submit my results** (emails internalit@) or
**Download CSV**. Run the report generator in `CoPilotCode/tools/report/` over the
collected submissions to produce the consolidated CSV and management report.
