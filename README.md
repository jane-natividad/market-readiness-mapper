# Market Readiness Mapper

Finds the real launch bottleneck in each of 13 markets and suggests the order to launch in next.

**[Try the live demo](https://market-readiness-mapper.vercel.app)**. It works straight away with no setup, runs entirely in your browser, and stores nothing. All data is fictional or synthetic.

## Why I built it

While studying real multi market launches, one surprise stood out. The missing markets were rarely the hard to reach ones. They were mature markets that simply sat outside the regulatory framework the others shared. That made me want a way to find each market's real bottleneck.

## The problem

Global often means one launch playbook copied market by market. Every launch runs through evidence, regulatory, market access and commercial execution, and which one is the bottleneck changes from place to place.

## What I built

A market map scoring a fictional patient program across 13 markets and four functions. It names the weakest link in each market, explains what fixing it involves, ranks what to launch next, and flags live markets that may be launched but not yet adopted.

## Who it's for

Global brand, market access and international business unit leaders deciding where to go next.

## What it does

- Click any market to see four function scores, the bottleneck and what it would take to fix
- Adjust scores or weights and watch the launch order update
- Spot live markets that may be launched but not yet working

## Decisions that shaped it

1. **The weakest score sets readiness:** averages can hide the thing that stalls a launch.
2. **Shared versus own regulatory framework:** this explains why familiar markets are often the ones missing.
3. **Hypothesise, check, then act:** outside in scores are a starting point for a real conversation.

## Key takeaway

A launch moves at the speed of its weakest function, so that's what the ranking looks at.

## Built with

- HTML, CSS and JavaScript in a single file

## Run it locally

Open `index.html` in any browser. There's nothing to install.

## About this project

This is a working prototype I built to explore a real problem space. It uses illustrative, fictional data and isn't connected to any organisation's systems. You can find more of my work at [jane-natividad.github.io](https://jane-natividad.github.io).

Built by [Jane Natividad](https://github.com/jane-natividad).
