# Pulse — Smart Churn Copilot

**From insight to action, in one click.**

Pulse is an AI copilot built for Case Study 2: Smart Subscription & Customer Experience Optimization. It targets subscription-based SaaS, media, and telecom companies, and closes the gap most churn tools leave open: knowing a customer is at risk is not the same as acting in time to save them.

Most churn tools stop at prediction. Pulse continues past it — predicting which accounts are likely to churn, simulating the financial outcome of a specific retention offer before it's sent, and then executing that offer, with a single human **"Approve & Deploy"** step.

---

## The Problem

Existing churn-analytics dashboards surface a risk score and a cohort view, then stop at the point where a human has to take over: exporting a list, opening a separate campaign tool, and manually looping in other departments.

- **Isolated Workflows** — marketers jump between CSVs, CRMs, and email tools just to act on data.
- **Costly Delays** — cross-departmental communication is slow, and days lost equal revenue lost.
- **Guesswork** — discounts get sent without knowing the expected ROI, conversion rate, or budget impact.

The stakes are real: North America's SaaS market alone is projected to grow from **$148B (2025) to $172B (2026)**, and a single churned account can cost over **$1.2M in lost profit** over an eight-year horizon. Retention tooling sits directly on the revenue line, not next to it.

## The Solution — Software as a Teammate

Pulse works in three steps:

| Step | What it does |
|---|---|
| **1. Predict** | Continuously monitors usage telemetry and support tickets to flag high-value customers before they cancel, scored by churn risk and CLV. |
| **2. Simulate** | Runs "what-if" scenarios to forecast conversion rate, budget impact, and retained revenue before an offer ever goes out. |
| **3. Execute** | Auto-generates personalized campaigns and escalates product bugs to engineering, all with one click. |

## Key Features

- **Explainable Churn Dashboard** — every flagged account comes with an explainability drawer naming the exact factors behind the score (usage drop, open ticket, billing failure) — no black-box numbers.
- **CLV-Ranked Priority List** — at-risk accounts ordered by revenue impact, with 1-click CSV export.
- **Faceted Audience Builder** — four multi-select filters (Lifecycle/Risk Stage, Plan Tier, Engagement, Demographics) for precise retention or upsell cohorts.
- **Campaigns & A/B Testing** — a unified workspace to build, manage, and test retention campaigns, scheduled on a built-in calendar.
- **Conversational AI Copilot** — a natural-language assistant with six quick-start flows: Clean Data, Find Audiences, Simulate Strategy, AI Recommendations, Analyze Campaigns, and Analyze Sentiment.

## The Copilot, in Action

One flow, start to finish:

> **Ask** — *"Show me high-value VIPs at risk of leaving."*
> **Isolate** — 96 VIPs surfaced, RM45,000 at risk, with the specific risk factor behind each account.
> **Simulate** — 68% success probability, RM30,600 revenue retained, with the reasoning shown, not just the number.
> **Approve & Deploy** — one click launches it. Nothing sends without a human approving it first.

## Why Not Just Use a Traditional Dashboard?

| Dimension | Traditional Dashboard | Pulse |
|---|---|---|
| Incentive Strategy | Blanket discounting | Zero-Waste Margin Protection — minimum discount calculated per user |
| A/B Testing | Post-launch validation | Pre-launch simulation |
| Architectural Scope | Marketing silo, no engineering visibility | Cross-functional orchestration via auto-generated tickets |
| Prioritization | Volume-based routing | CLV-weighted routing |

## Tech Stack

**Current prototype:** HTML5, Tailwind CSS, vanilla JavaScript, Chart.js.

**Intended production build:** React frontend; Node.js/Python (FastAPI) microservices; PostgreSQL with a vector store for support-ticket search; a gradient-boosted model (e.g., XGBoost) for CLV-weighted churn scoring; an LLM reasoning layer for explainability and the conversational interface; deployed on AWS with Vercel preview environments.

## Try It

This is a self-contained, single-file prototype — no build step, no dependencies.
