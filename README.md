# Merchant Onboarding & Activation Tracker

A lightweight single-page web app for tracking merchant onboarding progress — built as a portfolio piece for an Onboarding Specialist / Merchant Activation internship role.

## What This Project Is

Tracks merchants through a Facebook/Instagram ad campaign setup pipeline — from sales closure to campaign go-live — with a dashboard of activation metrics and an escalation log.

## Why I Built It

Practicing the skills an Onboarding Specialist needs every day: tracking merchant stages, spotting at-risk deals, calculating time-to-activation, and logging escalations. The seed data mirrors real small-business merchants (kirana stores, salons, gyms, tuition centers) so the dashboard looks populated from the first load.

## Tech Stack

- Plain HTML + CSS + JS (no framework)
- Chart.js via CDN for the bar chart
- `localStorage` for data persistence — no backend needed

## How to Run

1. Clone the repo
2. Open `index.html` in any browser
3. Data auto-saves to `localStorage` — refresh the page and your changes persist

To host on GitHub Pages: push to a repo, enable Pages in Settings → deploy from `main` branch. Works as-is since there are no build steps.

## Project Structure

```
merchant-onboarding-tracker/
├── index.html              # Single-page app (dashboard + table + modal)
├── docs/
│   ├── merchant-enablement-script.md   # Hindi-English AI ad agent call script
│   └── escalation-log-template.md      # Template for logging onboarding issues
└── README.md
```
