# Smart Pricing Engine – UI prototype

Static frontend prototype (no backend). Synthetic demo data only.

## Files
- `index.html` – overview page showing both views side by side
- `sales-rep.html` – sales rep view (quote parameters and result)
- `approver.html` – sales manager approver view (phone)
- `assets/dc-runtime.js` – generated runtime that renders the pages (don't edit)
- `assets/react*.js` – React 18, loaded locally
- `assets/montserrat-latin.woff2` – Montserrat font (SIL Open Font License)

## Where to edit
In `sales-rep.html` and `approver.html`:
- The layout is the markup inside `<x-dc> … </x-dc>`.
- The data and behaviour (customers, articles, calculations) are in the
  `<script type="text/x-dc">` block near the bottom.

## Run locally
Open the folder with a local server (not by double-clicking), e.g.
`python3 -m http.server` and visit http://localhost:8000
