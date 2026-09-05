# Security Policy

## Scope

This repository contains the public Relay Rider TDM landing-page prototype and waitlist form. Source control must remain free of submitted waitlist records and production credentials.

## Reporting

Report suspected vulnerabilities privately to **relayridersupport@gmail.com**. Do not publish exploit details, credentials, or waitlist information in public issues or pull requests.

## Data boundary

Never commit form submissions, names, email addresses, ZIP-based commute records, partner exports, precise locations, production API keys, private keys, environment files, or confidential operating material. Treat any exposed credential as compromised and rotate it outside GitHub.

## Public form expectations

- Collect only information necessary for the stated waitlist or research purpose.
- Use general geography rather than precise home addresses.
- Keep anti-bot controls and consent language enabled.
- Do not add payment, identity-document, driver-license, insurance, or verification collection to the static form.
- Protect third-party script and stylesheet dependencies and review them before version changes.
- Keep program availability and modeled outcomes clearly non-guaranteed.
