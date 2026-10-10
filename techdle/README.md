# Techdle

A responsive, no-build static web game inspired by Wordle. Guess five-letter technology and computer-science terms from concept hints.

## Features
- Daily puzzle and unlimited practice mode
- Six guesses with Wordle-style letter feedback
- Three progressive concept hints
- Definitions and practical examples after each round
- Keyboard support, on-screen keyboard, shareable results
- Local stats and daily game state via `localStorage`
- Responsive dark theme; no backend or API keys required

## Run locally
Open `index.html` in a browser.

## Deploy free with Netlify Drop
1. Unzip `techdle.zip`.
2. Open https://app.netlify.com/drop in your browser.
3. Sign in or create a free Netlify account if prompted.
4. Drag the **techdle folder** (the folder containing `index.html`) into the drop area.
5. Netlify will publish the site and give you a public URL.

## Deploy with GitHub Pages
1. Create a GitHub repository and upload `index.html` (and optionally this README).
2. In the repository, open **Settings → Pages**.
3. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Wait for GitHub Pages to publish the site.

## Notes
- This is a front-end prototype. It stores stats and the current daily game in the browser where you play.
- The included daily rotation is deterministic for visitors using the same date and version. For a real public launch, align the daily puzzle schedule to a chosen timezone and add a broader reviewed word bank.
- The word bank currently contains curated five-letter tech terms. Add new objects to the `WORDS` array in `index.html` using the same `word`, `cat`, `hints`, `definition`, and `example` fields.
