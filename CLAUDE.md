# Axiom

## What This Is

Marketing/pitch site for an AI-powered insurance regulatory returns platform. Branded under **Grace Blackwell** (graceblackwell.ai).

**Product concept:** Axiom is a governance and orchestration platform for insurance regulatory reporting — automating data collection, XBRL validation, approval workflows, and submission to regulators (PRA, Lloyd's, FCA, EIOPA).

**This project is the pitch materials only — not the product itself.**

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing page — problem statement, capabilities, business case |
| `platform.html` | Platform capabilities — orchestration pipeline diagram, feature cards |
| `architecture.html` | Technical architecture — stack, deployment, security |
| `regimes.html` | Regulatory regime coverage — Solvency UK, Lloyd's, FCA, EIOPA |
| `critique.html` | Critique — claim verification, competitive landscape, feasibility assessment |
| `Axiom_Insurance_Sector_Brief.docx` | Sector brief document (sales collateral) |

## Tech

- Static HTML, CSS (inline), vanilla JavaScript
- Fonts: Google Fonts (Lato, Cabin)
- Design: Dark theme, minimal, animated SVG diagrams
- Responsive: Mobile breakpoints included
- No build step, no dependencies, no backend

## Key Concepts

- **Four-stage pipeline:** Collect → Validate → Approve → Submit
- **AI + Deterministic:** AI handles orchestration; validation is deterministic (XBRL schema)
- **Human-in-the-Loop (HITL):** Board sign-off gates, no auto-submission
- **Enterprise Memory:** Prior returns, methodology, assumptions retained for consistency
- **Policy Engine:** Encodes submission rules, deadlines, templates as deterministic policy

## Target Market

UK insurance sector — Lloyd's managing agents, Solvency UK firms, dual-regime (UK + EU) insurers.

## Git

Repo: `github.com/mat-e-exp/axiom` (public)
