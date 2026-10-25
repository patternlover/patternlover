# Edoardo Cavalcanti

Digital analyst in Italy. Tracking, measurement, data pipelines — and a growing
amount of automation wrapped around all three.

I build processes that stop depending on me remembering them: a script, a test,
a log line and an obvious way to fail. AI goes where it makes the script
stronger, not where it makes the result fuzzier.

## What keeps me here

**Making the fuzzy deterministic.** Most of what I do at work is invisible
until it breaks: events that fire twice, parameters that arrive empty, a
tracking plan nobody can check. I like turning that into something checkable —
a spec, a diff, a table you can paste into a sheet.

**The setup is part of the work.** I run my own agent harness (skills, agent
definitions, model routing, a private context store my agents read before
answering). Not out of curiosity for its own sake: it is how a one-person
workflow stops losing things.

**Measurement as a craft.** GTM, GA4, dataLayer, BigQuery, Looker Studio. Day
job at Storeis; the tools I build here exist because the ones I could buy never
quite fit.

## Now

**October 2026** — designing `datalayer-doctor`: point it at a spec of expected
events, let a real browser walk through the site, get back what actually fired.
Four columns, pasteable into Google Sheets. First public repo of this profile,
coming soon.

## Projects

**[Dark Card Collection](https://darkcardcollection.com)** — a Pokémon TCG shop
(sealed, singles, slabs) I built and run with a partner. Private repo, live in
production.

- Next.js App Router storefront on Vercel
- Medusa 2 backend, self-hosted in Docker on a free-tier VM
- Custom procurement module: purchase lots, FIFO cost averaging, margins
- Playwright E2E against the live checkout, CI, secret scanning
- The interesting part is not the shop, it is the machinery that keeps cost and
  price honest while nobody is watching

**The harness behind these repos** — how I run AI agents on two machines, with
skills, budgets and guardrails. Sanitized version will land here as its own
repo.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/edoardo-cavalcanti) — the professional
version of this page.

My agents' context store is a private Obsidian vault: notes, decisions and logs
that get read before every answer and committed every day. The content stays
private, the system is described in the harness repo.
