# Sarah Yoga Class Builder

Static local-first web app for building gentle Monday yoga classes.

## GitHub Pages setup

1. Create a new GitHub repository.
2. Upload the contents of this folder:
   - `index.html`
   - `README.md`
3. In GitHub, open the repository settings.
4. Go to **Pages**.
5. Set source to **Deploy from a branch**.
6. Choose the `main` branch and `/root`.
7. Save.

The app will be available at the GitHub Pages URL shown by GitHub.

## Notes

- The app is fully static: no server, database, or build step required.
- Saved week choices use the browser's `localStorage`, so they are saved per device/browser.
- `Print / Save PDF` uses the browser print dialog.
- `Copy Notes Checklist` creates a plain-text checklist Sarah can paste into Apple Notes.
- `Download Email Checklist File` downloads a `.txt` file that can be emailed or saved.
