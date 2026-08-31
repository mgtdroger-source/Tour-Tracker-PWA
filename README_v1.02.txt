TD Tour Entrant Tracker v1.02

Changes from v1.01:
- Fix rapid track accumulation regression introduced by the v1.01 UI tidy-up.
- The immediate first report is now controlled by a separate run-level flag.
- Each new GPS fix no longer triggers another immediate tracking report.
- Normal behaviour restored: one first report, then one report every 30 seconds.
- Compact running line now shows: Queue · Total · Acc.
- Queue = reports waiting on the phone.
- Total = tracking reports generated in the current run.
- Acc = latest GPS accuracy to one decimal place.
- Existing offline queue/retry and Google acknowledgement behaviour retained.
