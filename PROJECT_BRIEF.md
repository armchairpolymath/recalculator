# recalculator

## What It Is
A real estate transaction date calculator built as a single self-contained HTML file. Given a contract date and closing date, it computes all the critical milestone dates in a real estate transaction — inspection periods, contingency deadlines, loan commitment dates, title deadlines, and more. Built for use by Patrick and the brokerage team to quickly calculate and track transaction timelines. Released under CC0 (public domain).

## Current Status
**Beta / stable** — v1.0 shipped March 2026. Single-file tool; functional and in use. No active development sprint. Future enhancements would be tracked in GitHub Issues.

## Tech Stack
- **Single file:** plain HTML + CSS + JavaScript (no build step, no dependencies)
- **Hosting:** previously deployed (GitHub repo has CNAME history suggesting a custom domain); currently local/standalone use
- **License:** CC0 1.0 Universal (public domain)

## Key Files & Entry Points
- `Date-Calculator v1.html` — the entire application; open in any browser to run it

## Architecture Notes
Fully self-contained single-page application. All styles, logic, and markup live in one HTML file. Multiple calculator modes selectable via tab UI. No server, no API, no build process — just open the file. The prior GitHub history (CNAME commit) suggests it was previously hosted at a custom domain; that deployment may or may not still be active.

## GitHub
- **Repo:** https://github.com/armchairpolymath/recalculator
- **Issues:** https://github.com/armchairpolymath/recalculator/issues
> Known bugs and feature requests are tracked in GitHub Issues. Check there before starting any dev work.

## Routing Notes (Darrow)
Any changes to date logic or UI → developer. This is a utility tool; keep it simple and self-contained unless there is a specific reason to add a build step. If a v2 is discussed (e.g. adding NM-specific rules, integrating with Vesta), that warrants a new planning session.
