# Security policy

## Supported versions

This repository hosts **community metadata and recipe JSON** for **Coffee Roast Tracker**, a **client-side** web app (no hosted database in the app itself). Security issues usually involve the **public website**, **browser data**, or **accidental disclosure**—not a traditional server CVE list.

## Reporting a vulnerability

If you believe you found a security problem (for example XSS that steals local data, a malicious recipe file that breaks the app in a dangerous way, or a problem with how the site is hosted):

1. **Do not** open a public issue with exploit details.
2. Prefer **GitHub private vulnerability reporting** (repo **Settings → Security → Code security**), if available. Otherwise email organization owners, or open an Issue titled `SECURITY — private follow-up` with **no exploit details** until a maintainer replies.

Include: affected URL, browser/OS, minimal reproduction steps, and impact.

## Secrets and privacy

- Do **not** paste credentials, API keys, or private links into Issues, Discussions, or recipe files.
- The app stores roast data in **browser local storage**; treat exported JSON like **personal data** if it contains notes or identifiers you care about.

## GitHub secret scanning

GitHub may alert on accidentally committed secrets. That does not replace careful review—especially in attachments and pasted logs.
