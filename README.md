# IHS Payday Log

https://in-housesystems.com/payday-log/

IHS Payday Log is a static, local-only W-2 piece-rate payroll log. IHS does not invoice the practice.

This repository and its GitHub Pages site are public. Only the static application shell belongs in git. Never commit patient names, initials, DOB, identifying chart numbers, photos, intraoral scans, STLs, visit notes, real case lists, storage dumps, or other PHI.

Finished work is the practice Case ID (work-order number) plus appliance type. Do not enter patient names, initials, DOB, or chart numbers. Finished means the treating dentist accepted the appliance. Each item stores the next regular payday after that accept date and does not move if the weekday setting later changes.

Records stay in `localStorage` in the current browser on the current device (`ihs-payday-v1-*` keys). They are not uploaded or synced. The payroll list can be copied, downloaded as CSV, or opened as a mailto draft. The app never sends email.

This app is not a patient chart. This app is not HIPAA certified and does not claim HIPAA compliance.

To deploy, publish GitHub Pages from the `master` branch and repository root. The app uses `<base href="/payday-log/">`; keep `.nojekyll` at the root. For local preview, serve it at `/payday-log/` on localhost rather than opening it with `file://`.
