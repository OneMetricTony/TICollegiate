# TICollegiate — AI Class Landing Page

Splash / landing page for **Toronto International Collegiate's AI class** (Grade 7 → University Prep) — the web version of the class poster.

## Live site
https://onemetrictony.github.io/TICollegiate/

## What's on it
- Hero: "Create with AI" + Claude Code (by Anthropic) featured as the AI of choice
- Curriculum: Theory of AI · Prompt Engineering · Connectors · What is MCP?
- Learning outcomes, class details ($395/mo, 4–6 PM, Mon–Wed), and enrollment (QR + Principal Helen Gao)
- Instructor bio (Tony Chu)

## Files
- `index.html` — self-contained responsive landing page
- `bg.js` — animated circuit-board background (cyan/gold)
- `ai_hero.png` — AI-generated hero image · `logo-large.png` — school crest · `ti_qr.jpg` — WeChat enrollment QR

Static site, no build step. Pushing to `main` auto-deploys via GitHub Pages.

## Custom subdomain (e.g. ai.ticollegiate.com)
To serve this at a subdomain of ticollegiate.com: add a `CNAME` file here containing the subdomain, then create a DNS **CNAME** record at the ticollegiate.com registrar pointing that subdomain to `onemetrictony.github.io`. (Requires access to the ticollegiate.com DNS.)
