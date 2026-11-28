# Carina Apps

Public website and privacy policies for [Carina Apps](https://younggraphix.github.io/carina-apps/), including [Carina Tasks for desktop](https://younggraphix.github.io/carina-apps/desktop/tasks/).

GitHub Pages is served from the `main` branch (root). The site is static HTML — `.nojekyll` is present so GitHub does not run Jekyll.

## Privacy policy URLs

The live site lists every app and links to its policy under `/privacy/<app>/`. Carina Tasks for desktop is at `/desktop/tasks/`. Installers are GitHub Release assets (tag `v1.2.0-desktop`), not files in this branch.

**Do not remove or rename `privacy-policy.html` at the repository root.** That file is the Lift Tracker policy already used on Google Play:

https://younggraphix.github.io/carina-apps/privacy-policy.html

Carina Launcher’s Play listing currently uses a separate hosted copy that should also stay up:

https://0tv023j.sharehtml.org/

## Updating a policy

1. Edit the matching HTML under `privacy/<app>/index.html` (and `privacy-policy.html` if you change Lift Tracker).
2. Keep the effective date in the page accurate.
3. Commit and push to `main`. Pages usually updates within a few minutes.

Contact: austin@younggraphix.com
