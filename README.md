# IHS Payday Log

IHS Payday Log is a static, local-only W-2 piece-rate payroll log. IHS does not invoice the practice.

This repository and its GitHub Pages site are public. Only the static application shell belongs in git. Never commit patient names, initials, DOB, identifying chart numbers, photos, intraoral scans, STLs, visit notes, real case lists, storage dumps, or other PHI.

Records stay in `localStorage` in the current browser on the current device; they are not uploaded or synced. The app supports current mobile and desktop browsers. Case ID means the practice work-order number, not a patient identifier.

To deploy, place the repository on GitHub and publish Pages from the `master` branch and repository root. The app uses `<base href="/payday-log/">`; keep `.nojekyll` at the root. For local preview, serve it at `/payday-log/` on localhost rather than opening it with `file://`.

This app is not HIPAA certified and does not claim HIPAA compliance.
