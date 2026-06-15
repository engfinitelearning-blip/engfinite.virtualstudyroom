# EngFinite Learning

A self-contained IELTS practice platform (Reading + Listening modules) built as a single static HTML file.

## Deploying with GitHub Pages

1. Create a new repository on GitHub (e.g. `engfinite`).
2. Upload `index.html` and `.nojekyll` to the root of the repository (or to a `/docs` folder / `gh-pages` branch — your choice).
3. Go to **Settings → Pages**, and set the source to the branch/folder where these files live.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Files

- `index.html` — the entire website (HTML, CSS, and JavaScript all inline).
- `.nojekyll` — tells GitHub Pages to skip Jekyll processing and serve the file as-is.

## Notes

- Listening audio is streamed from a Supabase storage bucket — no audio files need to be uploaded here.
- All test data, question banks, and styling are embedded directly in `index.html`.
- Dark mode and text-size settings are stored in each student's browser (local storage), so no backend/database is required.
