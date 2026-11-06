# OwlCircle

Temple AI Build · Team 28

OwlCircle brings campus events, academic support, career resources, and student communities into one starting point. It helps students translate a goal into relevant opportunities, a manageable event plan, and connections with complementary peers.

## Preview

Serve this folder with any static web server, for example `python -m http.server 4173`, then open http://localhost:4173. There is no build step and no dependency installation.

## Publish with GitHub Pages

In repository Settings → Pages, choose **Deploy from a branch**, branch **main**, folder **/(root)**, and save. The entry point is `index.html`; all assets use relative paths, so project URLs work. `.nojekyll` disables Jekyll processing.

## Features

- Goal matching with a local statistical intent classifier and explained event recommendations.
- Ten official Temple resource links, plus nine curated public event snapshots and twelve clearly labeled fictional events.
- Bookmarks, a weekly plan with a time budget and overlap checks, and calendar export.
- Six fictional peer profiles with complementary skills and editable introduction templates.
- Manual event import with review and duplicate checks, private reflections, and local preference reset.

## Data and scope

Public records and resource descriptions were checked November 5, 2026. Example event dates are November 9–15, 2026. Source URLs remain attached to the listings. The directory is a curated sample, not complete Temple coverage or live synchronization.

All simulated events and student profiles are labeled. No real student data, accounts, messages, registration, shared database, or live feeds are used. Preferences and plans stay in the visitor’s browser. Opening an official source follows that provider’s rules.

## AI use

ChatGPT / Codex assisted with research synthesis, interface and code generation, synthetic data and training phrases, matching design, and verification. At runtime, a small multinomial Naive Bayes classifier learns from 72 synthetic phrases and runs locally. Scheduling, duplicate checks, peer matching, imports, and introduction drafts use deterministic rules or templates. No external generative AI API is connected.

## Files

- `index.html`: page shell
- `styles.css`: responsive visual design
- `data.js`: public snapshots, synthetic examples, and source links
- `engine.js`: intent model, ranking, scheduling, imports, and calendar generation
- `app.js`: views, interactions, and browser storage
- `icon.svg`: site icon

## Demo

Start with the 60-second tour. Then try Build a project → Build my plan → Suggest my campus plan → Find your people. Campus resources shows official support links; Why OwlCircle explains the product’s contribution alongside existing Temple platforms.
