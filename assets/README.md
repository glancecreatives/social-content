# Social Content — Static Site for Meta App Submission

This repository contains a minimal static website to use when submitting the app **Social Content** to Meta (Facebook/Instagram) for review and verification. It is intended to be hosted on GitHub Pages.

## What is included
- `index.html` — landing page describing the app, contact info, OAuth redirect URI placeholder, screenshots section.
- `privacy.html` — simple privacy policy template.
- `oauth-callback.html` — placeholder page to capture the OAuth redirect.
- `assets/style.css` — minimal styling.

## Setup & Deploy to GitHub Pages
1. Create a new repository on GitHub named `social-content`.
2. Clone it locally and copy these files into the repo root.
3. Commit and push.

```bash
git init
git add .
git commit -m "Initial site for Meta app submission"
git branch -M main
git remote add origin git@github.com:<your-username>/social-content.git
git push -u origin main
