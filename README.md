# mpp-open

Public static pages for Lumina MPP, served by GitHub Pages at https://mpp.luminacorp.com/

- `index.html` — the "Open in MPP" page used by links in Microsoft Teams. It holds no data and makes no network requests: the item reference stays in the link's `#…` fragment (never sent to a server), is validated, and is handed to the installed Lumina MPP app (`lumina-mpp:` link).
- `privacy.html`, `terms.html` — privacy statement and terms of use for Lumi, Lumina Corp's internal Teams app for Lumina MPP.

The sources live in Lumina-Corp/Master_Project_Plan (`resources/open-page/index.html`, `relay/teams-app/{privacy,terms}.html`); update them there and copy them here.
