# TODO

- **Lock down invoicing** — DONE: `invoice.html` and the `getInvoiceData` / `createInvoice` Apps Script
  actions now require a `passcode` parameter, checked against a `PASSCODE` Script Property in Code.gs.
  To enable: in the Apps Script project, go to Project Settings > Script Properties and add a property
  named `PASSCODE` with a value you choose. The first time `invoice.html` is loaded it will prompt for
  the passcode and remember it for the browser session. If `PASSCODE` is not set, the check is skipped
  (so existing behavior is unchanged until you set it).
