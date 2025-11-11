# Crew Finder

Mobile‑first search for cabin crew contacts with instant LINE chat.

## Live data source
```
https://docs.google.com/spreadsheets/d/1HNWHoh29CGYfJsawS0hTXFb8XnUlsiFpyLvi6ZxxmHs/export?format=csv&gid=1751840495
```
Make sure the sheet is shared to **Anyone with the link (Viewer)**. Edits in the sheet update the site automatically.

## CSV headers (exact)
```
Batch,Name,Nickname,Staff_ID,Rank,LINE_ID,Notes
```

## Deploy
1. Create a public repo (e.g., `crew-finder`).
2. Upload `index.html`, `README.md`, and `icon.png` to the repo root.
3. Enable GitHub Pages: Settings → Pages → Source: Deploy from branch → main → /(root).
4. Visit `https://<your-username>.github.io/crew-finder/`.

## Use
- Search by any field (name, nickname, staff ID, etc.).
- Tap batch chips to filter quickly.
- If `LINE_ID` is missing, you’ll see **No LINE ID found** and the chat button is disabled.
