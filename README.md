# Thanksgiving 2026 — family planner

Replaces the Grenada site. Tue Nov 24 – Sat Nov 28, 2026, Charlotte NC, with a family vote on adding a mountain or beach house.

- `index.html` — the whole site in one file. Styling and logic are at the top of the `<script>`; everything the site *says* (house shortlist, ballot questions, three itineraries, dinner options, things to do, sports, tips, to-dos, packing list) is in the clearly marked CONTENT block near the bottom. Edit that block for content changes.
- `media/` — hero and section-break videos. See `media/README.md`; the site falls back to Pexels CDN links until the files are there.

Shared state (votes, dish sign-ups) lives at textdb.online under `POLL_KEY` in `index.html`. Checklists and the chosen itinerary tab are localStorage. Accepted passwords are in `PASSWORDS`.

House research: [Google Sheet](https://docs.google.com/spreadsheets/d/1T4Ifz5WJcnUI3UqJMsfFqeEtp-3msQ0m4lG4rC_eIyc/edit) — 75 Airbnb listings available for the dates and sleeping 10, searched Oct 29, 2026.
