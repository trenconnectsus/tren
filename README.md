# TREN Website

Tennessee Research & Education Network — static site built with Hugo, hosted on GitHub Pages.

## Setup

1. Clone `git@github.com:trenconnectsus/tren.git`
2. Copy these files into the repo root
3. Enable GitHub Pages in repo Settings → Pages → Source: GitHub Actions
4. Push to `main` — the site deploys automatically

## Where to change things

| What | File |
|---|---|
| Site URL | `hugo.yaml` → `baseURL` |
| Nav links | `hugo.yaml` → `params.nav` |
| Institutions | `hugo.yaml` → `params.institutions` |
| Homepage stats | `data/stats.yaml` |
| Hero image | `static/images/hero.jpg` (replace this file) |
| NSF award number | `hugo.yaml` → `params.nsf_award` |
| Hugo version | `.github/workflows/deploy.yml` → `hugo-version` |

## Adding content

**News item:**
```
content/news/your-item-name/
  index.md
  photo.jpg        ← optional
```

**Event:**
```
content/events/your-event-name/
  index.md
```

**Page:**
```
content/about/governance/
  index.md
```

## Local preview

```bash
brew install hugo     # macOS
hugo server
```

Open http://localhost:1313

## Deployment

Push to `main` → GitHub Actions builds and deploys automatically.
Check the Actions tab in GitHub for build status.
