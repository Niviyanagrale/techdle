# Techdle

A responsive, no-build static web game inspired by Wordle. Guess five-letter technology and computer-science terms from concept hints.

## Features
- Daily puzzle and unlimited practice mode
- Six guesses with Wordle-style letter feedback
- Three progressive concept hints
- Definitions and practical examples after each round
- Keyboard support, on-screen keyboard, shareable results
- Responsive dark theme; no backend or API keys required




## Notes
- This is a front-end prototype. It stores stats and the current daily game in the browser where you play.
- The included daily rotation is deterministic for visitors using the same date and version. For a real public launch, align the daily puzzle schedule to a chosen timezone and add a broader reviewed word bank.
- The word bank currently contains curated five-letter tech terms. Add new objects to the `WORDS` array in `index.html` using the same `word`, `cat`, `hints`, `definition`, and `example` fields.
