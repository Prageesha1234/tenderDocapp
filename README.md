# Bidroom

Bidroom is a browser-based tender workspace for tracking bids, submission dates, documents and team activity.

## Included in this prototype

- Account profile creation and editing
- Create, edit, filter and delete tender records
- Upload a tender document to a tender (session-level prototype)
- AI bid assistant with a document brief prompt
- Submission deadline rail and calendar actions
- Local persistence with `localStorage`

## Run locally

Open `index.html` directly in a browser, or serve the folder with any static server:

```bash
python3 -m http.server 4173
```

Then visit `http://localhost:4173`.

This is a frontend prototype. Production account authentication, cloud file storage, real calendar integrations and an AI API still need a backend service.
