TD Tour Entrant Tracker v1.00

Tour-only fork of TD6 Entrant Tracker TEST v0.05.

Operation:
- Configuration is carried in the Tour tracking URL as ?config={...}; no tracker-config.json is used.
- Entrant enters Tour No. and driver surname.
- App validates those details against the uploaded Tracking event entrants.
- Start Tracking / Stop Tracking only.
- GPS tracking report interval: 30 seconds.
- Each report is stored locally before transmission.
- Loss of network leaves reports queued on the phone.
- Queued reports retry automatically when connectivity returns.
- End-of-Event, fixed Day 1, fixed Route 1 and TD6 TEST logic removed.

Expected config fields:
configVersion, eventId, webAppUrl, key

This v1.00 intentionally keeps the existing Tour backend trackingSubmit contract.
