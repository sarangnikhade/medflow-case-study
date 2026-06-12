# MedFlow — UX Case Study

A long-scroll UX research case study for **MedFlow**, a medication-adherence app.
Static site (plain HTML + CSS), published on Vercel and updated weekly.

## Structure

```
index.html        → the full case study
styles/theme.css  → "Clinical Calm" health theme (tokens + components)
vercel.json       → static hosting config (clean URLs)
```

## Progress

- [x] **Week 1** — Project Overview · Research Plan · Interview Guide · Assumption Audit
- [ ] **Week 2** — Synthesis + Research Findings (section 05)
- [ ] **Week 3** — Personas + Journey Maps (section 06)
- [ ] **Week 4** — Design Decisions + Final Screens (section 07)

## Run locally

Just open `index.html` in a browser — no build step. (Needs network for Google Fonts.)

## Publishing & weekly updates

This repo is deployed on Vercel. Each push to `main` triggers an automatic
production deploy.

To ship a weekly update:

```bash
# 1. edit index.html (unlock the next section, add content)
# 2. commit + push
git add .
git commit -m "Week N: <what you added>"
git push
```

Vercel rebuilds and the live URL updates in ~20 seconds.
