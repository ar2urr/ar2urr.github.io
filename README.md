# Artur Istratov – portfolio

Single-file site (`index.html`), no build step.

## Deploy to GitHub Pages
1. Create a repo named `ar2urr.github.io`.
2. Add `index.html`, `.nojekyll` and `fyp-report.pdf` to the repo root and `cv.pdf`.
3. Push to `main`. Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. The site goes live at `https://ar2urr.github.io` within a minute or two.

## Before publishing
- Search `index.html` for `class="todo"` and `YOUR-` and replace every placeholder.
- Remove the `todo` class from each span once its text is real.

## Features
- Interactive edit-distance explorer in the hero (unit vs structural cost models).
- Command palette: Ctrl K / ⌘K or `/`.
- Light/dark theme toggle (remembers the choice), follows the system by default.
- All motion respects the "reduce motion" accessibility setting.
