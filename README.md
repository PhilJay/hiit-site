# Burnd site

This is the static landing site for Burnd, a HIIT interval timer for iPhone. Preview it locally with `python3 -m http.server 8000` in this folder and open http://localhost:8000. It deploys as GitHub Pages from the `main` branch, at https://philjay.github.io/hiit-site/.

The app links to `privacy.html` and `terms.html` from `Constants.swift`.

Styles live in `styles.css` and are copied into each page by `./build.sh`, so nothing blocks the first paint. Edit `styles.css`, run the script, and commit both.
