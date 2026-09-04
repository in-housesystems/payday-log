# IHS Payday Log

https://in-housesystems.com/payday-log/

Jack's W-2 piece-rate log for finished in-house appliances. IHS does not invoice the practice.

## Use it

Open the live URL on the computer you will keep using.

1. **Rates** — review the SAMPLE nightguard ($84) and edit amounts to match the practice. Logging stays blocked until rates are marked reviewed.
2. **Log** — enter Case ID (practice work-order number) and appliance when the treating dentist accepts the work. Assigned payday is the next regular payday after that date.
3. **Payroll** — copy the list, download CSV, or open a mailto draft. Mark included only after it is actually in payroll. The app never sends email.
4. **Settings** — regular payday weekday (does not move work already finished) and optional payroll email for drafts.

Records stay in `localStorage` in this browser on this device. They are not uploaded or synced. Clearing browser data or using another browser or device can lose the log.

## Rules

- Do not enter patient names, initials, DOB, chart numbers, or other PHI.
- Case ID is the practice work-order number, not a patient identifier.
- This repository and its GitHub Pages site are public. Only the static application shell belongs in git. Never commit pay records or PHI.
- This app is not a patient chart. This app is not HIPAA certified and does not claim HIPAA compliance.
