# RE:STACK x Woo — Free Data Audit landing page

Static co-branded landing page with an embedded HubSpot form.

- `index.html` — the whole page (inline CSS, no build step)
- `assets/` — RE:STACK and Woo logos

## HubSpot form

The page embeds a HubSpot form via `js.hsforms.net`.

- Portal ID: `2687773` (Woo.io, region `na1`)
- Set `WOO_FORM_ID` near the bottom of `index.html` to the form GUID.

Until a real GUID is set, the form area shows a placeholder message.

Form fields expected: first name, last name, work email, company, database (ATS).
Submit button: "Get my free audit."
