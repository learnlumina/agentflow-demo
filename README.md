# Agentic AI Bootcamp: Hands-On Labs for Real Business Problems

Free YouTube series + companion code repo. Every episode builds on the
last, using one running example business — **Northwind Outfitters**, a
fictional outdoor gear retailer — so by the end of the free series
you'll have one complete, deployed AI agent ("Sidekick") that you built
yourself, one concept at a time.

**The full course is complete — free series (Episodes 1-15) plus the
paid course track (Episodes 16-23, including the capstone).** The paid course track
picks up from Episode 16 and applies the same skillset to new business
domains, plus advanced topics, culminating in a capstone that combines
everything into one platform. See the course outline for the full
breakdown.

## How to use this repo

Each episode has its own folder:

```
ep-XX/
├── starter/                <- start here — has TODOs for the episode's lab
├── solution/               <- reference implementation
├── README.md               <- episode overview
├── tips-and-notes.md       <- class notes
└── lab-instructions.md     <- step-by-step lab walkthrough
```

Work through episodes in order — each one assumes the code from the
previous episode. Every `starter/` folder is self-contained (own
`requirements.txt`, own `.env.example` where an API key is needed) so
you can jump into any single episode without setting up the whole
course at once.

## Prerequisites

- Python 3.10+
- An API key from either [OpenAI](https://platform.openai.com/api-keys),
  [Anthropic](https://console.anthropic.com/settings/keys), or
  [Google AI Studio](https://aistudio.google.com/apikey) (Gemini) — this
  course is provider-agnostic; pick whichever you have access to and set
  it in each episode's `.env` file. A few dollars of credit covers the
  entire free series. (A couple of paid-track episodes need no API key
  at all — see their individual READMEs.). Note: Google Gemini has a generous free tier

## Solutions

This repo ships `starter/` scaffolds only — no answer keys. Full
reference solutions for every lab, exercise, and the capstone live in a
`solutions/`, kept apart on purpose so you have to genuinely attempt each lab first. Follow along in the lab episode videos, where the solution is built live.

## Episodes (free series). Subscribe to see new episodes released weekly.

| Ep | Title | Status |
|---|---|---|
| 1 | What Is Agentic AI, Really? | Weekly |
| 2 | Anatomy of an Agent: Prompts, Tools, Loops | Weekly |
| 3 | Mapping a Business Process to Agent Design | Weekly |
| 4 | Function Calling: Giving Your Agent Tools | Weekly |
| 5 | LangGraph Tutorial: Build a Real AI Agent | Weekly |
| 6 | CrewAI Tutorial: Build a Multi-Role AI Agent Team | Weekly |
| 7 | OpenAI Agents SDK vs AutoGen: Which Should You Use? | Weekly |
| 8 | RAG for AI Agents: Stop Your Agent From Making Things Up | Weekly |
| 9 | Give Your AI Agent Memory (So It Remembers Customers) | Weekly |
| 10 | Multi-Agent Systems Explained: Building an Agent Handoff | Weekly |
| 11 | MCP Explained: Connect AI Agents to Slack, Email & Your Tools | Weekly |
| 12 | n8n AI Agents: Build a No-Code Business Agent | Weekly |
| 13 | How to Test AI Agents (Before They Break in Production) | Weekly |
| 14 | AI Agent Guardrails: Stop Prompt Injection & Protect Your Data | Weekly |
| 15 | Deploy Your AI Agent: From Localhost to Production | Weekly |

## Episodes (paid track — Business Bootcamp Add-On)

Each paid episode applies the same skillset to a new business domain
(or, from Episode 20 on, to scaling, hardening, and optimizing the
system you've already built) and ships a standalone PDF study guide,
plus (for most episodes) one extra episode-specific deliverable — a
prompt template pack, report template, sample dataset, checklist,
benchmark spreadsheet, etc. See each episode's README for specifics;
not every episode ships a second deliverable, and the capstone ships a
different set of course notes entirely (see its own README).

| Ep | Title | Status |
|---|---|---|
| 16 | Sales/SDR Agent — Northwind's Outbound Assistant | Available |
| 17 | Research/Analyst Agent — Market & Competitor Watch | Available |
| 18 | Finance/Reporting Agent — Weekly Ops Digest | Available |
| 19 | Internal Ops Agent — IT/HR Helpdesk | Available |
| 20 | Scaling Multi-Agent Orchestration | Available |
| 21 | Security & Compliance for Agentic Systems | Available |
| 22 | Fine-Tuning & Optimizing Agent Behavior | Available |
| 23 | Capstone — The Northwind Agent Platform | Available |

## That's the course

Episode 23 is the last one — the full 23-episode course, free and
paid, is complete. Thanks for building through it.

## License / usage

Code in this repo is free to use and adapt for learning and your own
projects. If you build something with it, tag us — we'd love to see it.
