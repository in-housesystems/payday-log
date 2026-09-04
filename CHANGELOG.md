# IHS Payday Log changelog

Newest first. This is the human list of what went live. GitHub still has the technical commits.

## Sep 4, 2026 — Architecture pass (no change)

- Looked at the live app and this repo. No structure change was needed.
- Already a one-file GitHub Pages shell. Pay records stay in this browser. There is no extra catalog, leftover server, unused login, or second calculator to collapse.
- Live URL, four screens (Log / Payroll / Rates / Settings), and this-browser storage stay as they are.

## Sep 2, 2026 — v1 goes live

- Live at https://in-housesystems.com/payday-log/
- Jack's W-2 piece-rate log. IHS does not invoice the practice.
- Log finished work as Case ID (practice work-order) plus appliance. Finished means the treating dentist accepted the appliance.
- Each item stores the next regular payday after that accept date. Changing the weekday later does not move old work.
- SAMPLE nightguard $84. Rates must be reviewed before logging.
- Payroll list can be copied, downloaded as CSV, or opened as a mailto draft. The app never sends email.
- Records stay in `localStorage` in this browser on this device. Not a patient chart. Not HIPAA certified.
