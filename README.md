# TorbotsDocs

Team-wide documentation site for **FRC Team 1197 TorBots**, built with [MkDocs](https://www.mkdocs.org/) and the [Material theme](https://squidfunk.github.io/mkdocs-material/).

This covers onboarding, team structure, subteam guides, and build season process. Project-specific docs for [ScouTor](https://github.com/FRC-Team-1197-Torbots/ScouTor) and [TorKit](https://github.com/FRC-Team-1197-Torbots/TorKit) live in their own repos.

## Local development

```bash
pip install -r requirements.txt
mkdocs serve
```

Then open http://127.0.0.1:8000/.

## Deployment

Pushing to `main` triggers [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml), which builds the site with `mkdocs gh-deploy` and publishes it to the `gh-pages` branch.

Once the repo is created on GitHub, enable Pages once (Settings → Pages → Source: Deploy from a branch → `gh-pages` / `root`). After that, every push to `main` auto-updates the live site at:

```
https://frc-team-1197-torbots.github.io/TorbotsDocs/
```
