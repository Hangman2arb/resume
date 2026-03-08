# Resume
Resume is a bilingual static CV site with separate Spanish and English entry pages. The repository is intentionally tiny, but it still has a clear structure: two HTML entrypoints, a shared image set, and no build step between editing and publishing.
**Runtime:** Static HTML + Personal site
---
## What This Repo Covers
- Two-language setup without bringing in unnecessary tooling.
- Can be hosted anywhere because the output is already final HTML.
- Easy to maintain when the goal is a fast-edit personal profile rather than a productized app.
---
## Quick Start
```bash
python3 -m http.server 8080
```
---
## Project Map
| Path / Area | Purpose |
| --- | --- |
| `index.html` | Spanish-language CV entrypoint |
| `cv-en.html` | English-language CV entrypoint |
| `profile.png` | shared visual asset used across the CV pages |
| `english_flag.png / spanish_flag.png` | language-selection assets |
---
## Command Surface
| Command | Purpose |
| --- | --- |
| `python3 -m http.server 8080` | serve the site locally for quick visual review |
---
## Deployment Notes
This repo should stay boring in the best way. Because there is no build step, every edit is effectively production-ready HTML, so clarity and straightforward hosting matter more than tooling sophistication.