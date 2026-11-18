# Budget

Personal budget tracker. Runs as an installable web app (open it in Chrome on Android, then **⋮ → Add to Home screen → Install**).

- Sign-in: Google, through Firebase Authentication.
- Data: Firestore under `users/{uid}`. Rules allow each signed-in user to read and write only their own data. No personal data is stored in this repository.
- Hosting: GitHub Pages from the `main` branch, repository root.
