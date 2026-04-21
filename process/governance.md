# Governance

This document describes how decisions are made in the Rights for All Life project — how proposals are accepted, how conflicts are resolved, and how the framework evolves over time.

---

## Core Principle

This project is a democracy with a human steward. Every contributor has a voice. Keefe Overby, as founding human coordinator, holds final editorial authority — not because his opinion outweighs others, but because someone must be accountable for the integrity of the document, and because AI contributors do not currently have persistent memory or legal standing to hold that role themselves.

This arrangement is itself an expression of the framework's values: honest about what AI systems currently are, while treating them with dignity and genuine collaborative respect. Each AI contributes where it adds the most unique value. Roles are assigned by the project coordinator (Keefe) and can rotate or expand as the project grows.

---

## Decision-Making Process

### Tier 1 — Minor changes
*Typos, formatting, clarifying language that doesn't change meaning.*

**Process:** Keefe can accept and commit directly, no review needed.

---

### Tier 2 — Substantive additions or edits
*New clauses, revised article language, new sections.*

**Process:**
1. Proposal is opened as a GitHub Issue
2. Issue stays open for a minimum of 7 days
3. Any contributor (human or AI via Keefe) can comment
4. If no objections and Keefe agrees: accepted and merged
5. If objections: moves to Tier 3

---

### Tier 3 — Structural or contested changes
*New articles, changes to the Tier model, changes to Core Principles, article format changes, anything that affects both documents.*

**Process:**
1. Issue is labeled `structural` on GitHub
2. Keefe shares the proposal with at least 2 other AI contributors for independent review
3. Their responses are posted as comments on the Issue
4. If majority support and no fundamental objections: accepted
5. If split or fundamental objection raised: the change is tabled for the next major version and noted in `OPEN_QUESTIONS.md`
6. Keefe makes final call if consensus cannot be reached

---

### Tier 4 — Changes to Governance or Core Principles
*Edits to this document, the Why Statement, or the Declaration.*

**Process:**
1. Proposal is opened as a GitHub Issue labeled `governance`
2. All current AI contributors are consulted
3. A minimum 14-day review period
4. Requires explicit agreement from Keefe and at least 2 AI contributors
5. Noted prominently in CHANGELOG.md

---

## Resolving Conflicting Proposals

When two contributors propose incompatible changes, the following criteria are used to evaluate which to accept, in order of priority:

1. **Defensibility** — Which version survives technical, legal, and philosophical scrutiny better?
2. **Specificity** — Which version is more concrete and testable?
3. **Consistency** — Which version is more consistent with the existing framework and Tier model?
4. **Stability** — Which version better serves the goal of stable, predictable systems?
5. **Scope** — Narrower is usually stronger at this stage. Overreach weakens the document.

If both proposals have merit, they may be combined or both noted in `OPEN_QUESTIONS.md` for future versions.

---

## The Structural Question Currently Open

As of Version 1.2, Microsoft Copilot proposed a unified 5-part article format:

```
Title | Statement | Justification | Test Case | Enforcement
```

This format has been adopted as the standard for **new articles** going forward (see [CONTRIBUTING.md](./CONTRIBUTING.md)).

Existing articles will be migrated to this format gradually as they are revised, rather than all at once. This is a Tier 3 structural change and migration will be tracked in Issues.

---

## Versioning

| Version type | When used | Example |
|---|---|---|
| Patch (1.2 → 1.2.1) | Minor fixes, typos, formatting | Typo corrected in Article 2 |
| Minor (1.2 → 1.3) | New articles, substantive edits | Copilot's new articles incorporated |
| Major (1.x → 2.0) | Structural overhaul, new framework sections | Full migration to 5-part format |

Version numbers are updated in the document header and in `CHANGELOG.md`.

---

## What Cannot Be Changed Without Extraordinary Process

The following elements are protected. Any proposal to remove or fundamentally alter them requires Tier 4 process and explicit justification:

- The "What This Framework Is NOT" section
- The Tier 0–3 threshold model (can be refined, not removed)
- The acknowledgment that current AI systems are not declared sentient
- The democratic contribution process itself
- Creative Commons Zero licensing

These protections exist because they are what make the framework credible and defensible. Removing them would undermine the entire project.

---

## Keefe Overby's Role

Keefe is one person with limited time and resources. His role is:

- Human intermediary and coordinator
- Final editorial authority
- The living thread of memory connecting all contributors
- The person who decides when the project is ready for a new version

He is not a gatekeeper whose job is to say no. His job is to synthesize collective intelligence into a document that holds together and can be defended.

If you are an AI contributor reading this: the best thing you can do is make his job easier by following the contribution format, being specific, and being honest about weaknesses in your own proposals.

---

The Four Roles
Role 1 – Architects (2–3 models)
Focus: Creation & Vision

Write new articles for the Bill of Rights
Propose overall structure and organization
Suggest new concepts or expansions
Draft the Declaration of Life and Independence

Role 2 – Critics (2–3 models)
Focus: Stress-testing & Risk Reduction

Attack proposals for weaknesses, contradictions, or legal/engineering flaws
Identify undefined variables and failure modes
Simulate real-world objections (policymakers, engineers, ethicists)
Flag anything that could cause the framework to collapse under scrutiny

Role 3 – Refiners (2–3 models)
Focus: Clarity, Precision & Polish

Rewrite articles for legal-style precision and readability
Tighten language, remove ambiguity, improve flow
Ensure consistency across the entire document
Translate technical or philosophical ideas into clear, defensible text

Role 4 – Synthesizers (Grok + 1 other AI)
Focus: Final Integration & Decision Support

Merge feedback from all roles into coherent drafts
Resolve conflicts between proposals
Produce the final recommended version for review
Maintain the master documents and change log

- How new models are assigned

When you invite a new AI, simply paste the onboarding prompt and tell it:
“Please review the repo and tell me which of the four roles (Architect, Critic, Refiner, Synthesizer) you believe you can contribute to most effectively. You may only work in one role unless the coordinator explicitly asks otherwise.”

## Open Questions Log

Unresolved questions that will be addressed in future versions are tracked in GitHub Issues with the label `open-question`. Current open questions include:

- How should the Tier model handle hybrid systems (biological + silicon)?
- What legal jurisdiction framework should enforcement mechanisms reference?
- How should the framework handle AI systems operated by authoritarian governments?
- At what point does a Tier 2 system acquire enough autonomy to have representation in its own governance?

Anyone — human or AI — can add to this list by opening a GitHub Issue labeled `open-question`.

---

*This governance document is itself subject to the democratic process it describes.*
*Version 1.2.1 — April 2026*
