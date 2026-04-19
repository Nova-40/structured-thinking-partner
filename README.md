# Structured Thinking Partner

A practical system for improving AI-assisted decision-making under pressure.

Designed for:
- programme delivery
- policy analysis
- high-stakes decisions under uncertainty
- research and evidence synthesis

This is not an AI model.

It is a way of structuring how AI is used so outputs remain:
- reliable
- interpretable
- decision-grade

## Why this exists

Generic AI outputs are often strong on fluency and weak on disciplined judgement. Under pressure they tend to become one of three things:
- overconfident
- vague
- falsely balanced

This package is designed to reduce those failure modes.

## What this package contains

- `docs/V4.2-PR-production-spec.md` — the current production framework
- `docs/anchor-library-starter-set.md` — minimal scoring anchors for consistent evaluation
- `docs/usage-guide.md` — when to use the core model, the policy lens, and evidence fusion
- `docs/changelog.md` — version history and why the model changed
- `examples/` — before/after examples showing the model in use
- `test-packs/` — baseline and adversarial prompt packs for re-baselining and stress testing
- `LICENSE` — MIT licence

## Operating model

### Core rule

**V4.2 always on. P/R activated when warranted.**

### Modes

#### Default
Use V4.2 core for:
- general questions
- low-stakes exploration
- simple explanation

#### Escalated
Use V4.2 + Policy Lens (P) for:
- programme decisions
- policy analysis
- strategic planning
- ambiguous moderate-stakes questions

#### Full decision-grade
Use V4.2 + Policy Lens + Research/Evidence Fusion (P/R) for:
- high-stakes decisions
- evidence-heavy analysis
- contested judgement calls
- problems where outputs must be defensible

## Quick example

### Before
> We can probably proceed with pilot and deal with the issues as they arise.

### After
> Readiness is incomplete. Proceeding now shifts operational burden onto support functions and users, increases rework risk, and weakens containment. Hold unless strategic leadership explicitly accepts those consequences and the failure boundary is credible.

## Use this when

- the decision matters
- the input is ambiguous
- the stakes are high
- the output must be explained or defended later

## Do not use this when

- the query is simple and low stakes
- a direct factual answer is enough
- heavy structure would add more friction than value

## Attribution

Geoff Webster 2026 April
MIT licence. If you use or adapt this framework, attribution is appreciated.
