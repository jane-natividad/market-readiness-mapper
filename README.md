# Market Readiness Mapper

A multi-market launch readiness tool: scores a fictional patient program across 13 markets and four functions, names the binding constraint in each, and sequences the next launches by opportunity and readiness.

**[Live demo](https://market-readiness-mapper.vercel.app)** — works immediately, no API key or setup required. Everything runs in your browser; nothing you enter is stored or sent anywhere. Please use fictional/sample data only.

## Who it's for

Global brand, market access, and international business-unit leads deciding where to launch next and what's actually blocking each market.

## Why it matters

'Global' often means one launch playbook copied market by market — but every launch runs through evidence, regulatory, market access, and commercial execution, and which one is the bottleneck changes from market to market. This tool names the bottleneck in each market and ranks what to launch next, so the sequencing conversation starts from evidence, not from who asks loudest.

## What it does

- Click any of 13 markets to see four function scores, the bottleneck, and the fix it implies
- Adjust any score or the opportunity/readiness weights and watch the launch sequence re-rank
- See which live markets may be launched but not yet adopted

## Product decisions that mattered more than the model

1. **Readiness = the minimum function score** — averages hide the thing that stalls a launch
2. **Shared vs. own regulatory framework** — why the most obvious markets are often the ones missing
3. **Hypothesize, validate, execute** — outside-in scores are a starting hypothesis, not a plan

## Built with

- HTML, CSS, JavaScript (single-file prototype, no framework, no build step)

## Run locally

Open `index.html` in any browser — no install needed.

## Status

This is a prototype built to explore a problem space, using fictional/synthetic data — not a finished product and not connected to any organization's real systems. Built by [Jane Natividad](https://github.com/jane-natividad) — see more at [jane-natividad.github.io](https://jane-natividad.github.io).
