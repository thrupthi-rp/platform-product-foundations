# Platform Decision Boundaries

A practical framework for identifying which product, data, and platform decisions require deep governance and which should move fast.

---

# Why this exists
In complex product environments, teams often slow down the decisions that could move fast and rush the ones that are hardest to reverse. 

Minor roadmap choices are debated endlessly, while foundational decisions data models, privacy boundaries, platform contracts are quietly locked in with limited scrutiny. 

These patterns surface most clearly at moments of product maturity when optimisation gives way to discontinuity and early decisions begin to outlive teams.

This repository exists to help teams distinguish between:
- **Decisions that should move fast**
- **Decisions that must move deep**

Not all decisions carry the same weight. Treating them as if they do creates unnecessary drag, risk, and long-term fragility. 

---

**Core idea: Decision reversibility under scale**

At the heart of this framework is a simple lens.

---

**Two-Way Door Decisions (Reversible)**

Choices that can be undone with limited cost:
- Vendor trials
- UI flows
- Feature experiments
- Pilot metrics
- Short-term integrations

**Failure mode: Over-governance**

When these decisions are treated as irreversible, teams slow learning and create permission-seeking cultures.

---

**One-Way Door Decisions (Hard to reverse)**

Choices that materially constrain future options:
- Data schemas and ownership models
- Identity and privacy foundations
- Core platform abstractions (event models, domanin boundaries)
- Long-term API or vendor contracts
- Regulatory or compliance commitments

**Failure mode: Under-thinking**

When these decisions are rushed, teams inherit years of architectural debt disguised as progress. 

---

**What this repository contains**

This repo is intentionally small and opinionated.
- A decision classification framework for platforms and data
- Heuristics for identifying irreversible commitments early
- Questions to stress-test assumptions before locking them in \
- Guidance for applying deeper scrutiny without stalling delivery

It is not a prescriptive process.
It is a judgement aid.

---

**Who this is for**

This material is relevant for:
- Product people working on platforms or data-heavy systems
- Teams designing foundations intended to scale\Organisations navigation AI, privacy, and infrastructure trade-offs
- Anyone responsible for decisions that outlive roadmaps and teams

---

**How to use it**

Use this framework:
- During early discovery or architecture discussions
- Before committing to foundational data or platform decisions
- As a shared language betweek product, engineering, and governance roles

If a decision feels heavy, ask:

**Is it heavy because it's hard or because it is irreversible?**

---

**Scope and intent**

This repository reflects practical thinking shaped by experience across software engineering, product delivery, platform transformation, and governance focused work.

It is not exhaustive.
It is designed to evolve.

**The goal is clarity, not completeness.**

---

**Status**

This is working note.

It evolves only when patterns repeat across multiple product or platform contexts. The intent is not to scale content, but to preserve judgement clarity over time. 
