# Simple GitHub Pages Deployment using GitHub Actions

This is a minimal example of deploying a static website to **GitHub Pages** using **GitHub Actions**.

## Features
- Auto-deploys whenever you push to `main`
- Uses the official `actions/deploy-pages` action
- No secrets or manual setup required (besides enabling Pages in Settings)

## Steps to Use

1. Create a new GitHub repository and upload this code.
2. Go to **Settings → Pages** and set the source to **GitHub Actions**.
3. Commit and push changes to `main` — GitHub will deploy automatically.

Your site will be available at:
```
https://<username>.github.io/<repo-name>/
```
