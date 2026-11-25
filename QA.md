# DUREV checks — 2026-11-25

Template 1.3.0, source Freebielife/TON-Observatory-Template@6578013.

- 17 Python unit tests and 15 JavaScript tests passed; app.js syntax passed.
- Standalone HTML verified against its exact embedded snapshot.
- Browser checks: desktop CSS viewport 1363px and narrow viewport 340px (browser zoom); no horizontal document overflow at either width. Mobile layout visually inspected; no physical-phone test.
- RU/EN, chart, section navigation, holder expansion 10 to 20, services tab verified.
- All images loaded; no external script, stylesheet or image rendering dependencies. Snapshot refresh and wallet lookup use the network.
- Project and pool links returned HTTP 200; Telegram and X direct HTTP checks returned 403, so response availability there is not established by the HTTP check. The official Telegram channel and its contract/link were read through web retrieval.
- Historical coverage is partial. No verified staking/lock integrations were configured. Common DNS and Fragment ownership checks progress across later refreshes; absence of a badge is not proof of absence of ownership.
- Code publication, workflow execution, unattended schedule and TON Storage publication are separate states.
