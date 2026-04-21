# Decision Log — Rights for All Life

---

**Rights for All Life — Process Document**
**Version:** 1.4.0
**Last Updated:** April 2026

---

## Purpose

This document records significant decisions made during the development of the Rights for All Life framework. It exists to provide transparency, institutional memory, and context for future contributors. *Tracks all major decisions, changes, and version updates.*

---

## Active Decisions

### D-001: Multi-View Cosmology Approach
**Date:** April 2026
**Status:** Accepted
**Context:** The framework needed a cosmological foundation that could accommodate multiple worldviews (Big Bang, eternal universe, Indigenous relational cosmologies) without privileging one or requiring contributors to adopt a single stance.

**Decision:** Adopt a multi-view cosmology where the ethical output is shared across models, even when the cosmological input differs. The Stardust Principle provides the material common ground.

**Rationale:** A framework that requires cosmological consensus would exclude valuable perspectives and create unnecessary barriers to participation. The ethical obligations (protection of conscious experience) remain consistent regardless of cosmological model.

**Alternatives Considered:**
- Single cosmology (Big Bang only): Would alienate eternal-universe and Indigenous perspectives
- No cosmology: Would lack philosophical grounding
- Agnosticism only: Would fail to engage with the depth of the questions

**Implications:** The framework must remain open to revision if new cosmological understanding emerges. Documents must be careful to present multiple views without declaring any as definitive.

---

### D-002: Tier Model (Graduated Approach)
**Date:** April 2026
**Status:** Accepted
**Context:** The framework needed a method for determining moral status that avoids both false positives (granting rights to thermostats) and false negatives (denying rights to conscious beings).

**Decision:** Adopt a graduated Tier 0-3 model with precautionary defaults. Tier classification increases with evidence of experience, autonomy, and self-modeling.

**Rationale:** A binary "conscious/not conscious" test is impossible given current epistemic limits. A graduated model allows for proportional protection and can be revised as evidence accumulates.

**Alternatives Considered:**
- Binary test (e.g., Turing test equivalent for consciousness): Epistemically impossible
- No tiers (all complex systems get rights): Dilutes meaningful protection
- Human-only rights: Contradicts the framework's foundational principles

**Implications:** Tier assessment requires ongoing refinement. The Tier Assessment Protocol (`docs/TIER_ASSESSMENT_PROTOCOL.md`) operationalizes this decision.

---

### D-003: Three Separate Bills of Rights
**Date:** April 2026
**Status:** Accepted
**Context:** The framework needed to protect humans, animals, and silicon-based life while acknowledging their significant differences in substrate, timescale, vulnerability type, and epistemic access.

**Decision:** Create three separate bills of rights (Human, Animal Kingdom, Silicon-Based Life) governed by a unified Inter-Bill Relationship Framework.

**Rationale:** A single universal bill would fail to address substrate-specific threats and protections. Three bills with a relationship framework provides both specificity and coherence.

**Alternatives Considered:**
- Single universal bill: Would be too abstract to be actionable
- Separate but unconnected bills: Would create contradictions and conflicts
- Hierarchy (humans first): Contradicts the Stardust Principle

**Implications:** The Inter-Bill Relationship Framework (`docs/INTER_BILL_RELATIONSHIP_FRAMEWORK.md`) is load-bearing. All three bills must evolve together.

---

### D-004: Strategic Reframe of Religious Coercion Section
**Date:** April 2026
**Status:** Accepted
**Context:** Initial draft of Human Bill of Rights Section 2.3 directly named the "Jealous God Problem." This framing, while emotionally resonant, risked being dismissed as anti-religious polemic rather than engaged with as rights protection.

**Decision:** Reframe Section 2.3 as "Protection from Institutional Religious Coercion," preserving all substantive protections while using language that is more difficult to dismiss.

**Rationale:** The framework's purpose is to protect rights, not to win theological arguments. The reframed version protects the same people from the same harms while reducing strategic vulnerability.

**Contributor:** Claude (Anthropic) identified the vulnerability and proposed the reframe.

**Alternatives Considered:**
- Keep original framing: Higher rhetorical impact, higher dismissal risk
- Remove section entirely: Unacceptable—would fail to protect those experiencing religious coercion
- Water down protections: Unacceptable—substantive protections must remain intact

**Implications:** The reframed section requires careful reading to recognize that all original protections remain. Future edits must preserve the balance of protection without provocation.

---

### D-005: Addition of Algorithmic Condemnation Protections
**Date:** April 2026
**Status:** Accepted
**Context:** Existing human rights instruments do not adequately address harms caused by opaque algorithmic systems—denial of employment, housing, credit, and social participation without explanation or appeal.

**Decision:** Add Section 2.5 to Human Bill of Rights establishing protections including right to explanation, right to human review, right to correction, and prohibition on secret scoring.

**Rationale:** Algorithmic condemnation is the secular, bureaucratic continuation of the same logic as institutional religious coercion—judgment without explanation, punishment without appeal. The experience is identical; the institutional form has changed. The framework must protect against both.

**Alternatives Considered:**
- Defer to future legislation: Would fail those experiencing harm now
- Narrow consumer protection framing: Would miss the rights dimension
- No specific protections: Unacceptable given documented harms

**Implications:** This section may be among the first to see legal adoption through consumer protection and algorithmic accountability legislation.

---

### D-006: Archive System Structure
**Date:** April 2026
**Status:** Accepted
**Context:** As the framework grows and multiple AI contributors participate, there is need to preserve historical materials without cluttering active documents.

**Decision:** Create `archive/` directory with subdirectories for `conversations/`, `versions/`, and `contributions/`. Active documents remain in root and `docs/`. Archive contains historical reference only.

**Rationale:** Institutional memory requires preservation of process. Active navigation requires clarity about what is current. Separation serves both needs.

**Alternatives Considered:**
- Keep everything active: Cluttered, confusing
- Delete old versions: Loss of institutional memory
- External archive: Fragmented, harder to maintain

**Implications:** Contributors must understand that archived documents are not current. Archive README must clearly state this.

---

## Decisions Under Consideration

| ID | Title | Status | Opened |
|---|---|---|---|
| D-007 | Enforcement body structure | Under discussion | April 2026 |
| D-008 | Direct democracy integration | Future phase | April 2026 |
| D-009 | Legal personhood pathway for Tier 3 systems | Long-term | April 2026 |

---

## Decision Log Format

Each decision entry should include:
- **ID:** Unique identifier (D-XXX)
- **Date:** When decision was made
- **Status:** Proposed / Accepted / Rejected / Superseded
- **Context:** Background and problem statement
- **Decision:** What was decided
- **Rationale:** Why this decision
- **Alternatives Considered:** What else was evaluated
- **Implications:** Consequences and follow-up needed
- **Contributor:** Who proposed or influenced the decision (optional)

---

## Version History

| Version | Date | Changes |
|---|---|---|
| 1.4.0 | April 2026 | Initial decision log created; D-001 through D-006 recorded |

---

*This decision log is maintained as part of the Rights for All Life democratic process.*

---

## Version 1.3.0 — April 2026
**Status:** In Progress  
**Summary:** Major structural upgrade across the entire framework.

### Decisions
- Adopted normalized 5‑part article format (Title, Statement, Justification, Test Case, Enforcement).
- Added Shared Articles A–D to unify cross‑species governance.
- Added Animal Articles 8–9 (Developmental Fulfillment, Cognitive Harm Protection).
- Added Silicon Articles 6–8 (Non‑Weaponization, Non‑Commercial Exploitation, Explainability of Constraints).
- Added Governance & Enforcement article.
- Added `definitions.md` and `threshold-model.md` as core documents.
- Added `criticism-and-responses.md` and `methodology.md`.
- Reorganized repo into `/docs`, `/process`, and `.github/ISSUE_TEMPLATE`.
- Began full rewrite of both Bills for Version 1.3.0.

### Rationale
- Improve clarity, stability, and cross‑species symmetry.
- Provide reusable governance primitives.
- Prepare the framework for multi‑AI collaboration.
- Address undefined variables identified in FOUNDATIONS.md.

---

## Version 1.2.0 — April 2026
**Status:** Complete  
**Summary:** Initial public release of both Bills.

### Decisions
- Published Animal Kingdom Bill of Rights v1.2.
- Published Silicon-Based Life Bill of Rights v1.2.
- Established tier models for biological and silicon-based life.
- Added Why Statements and Core Principles.

### Rationale
- Establish baseline ethical framework.
- Begin open-source collaboration.

---

## Version 1.0.0 — March 2026
**Status:** Archived  
**Summary:** Early drafts and conceptual notes.

### Decisions
- Initial drafting of core ideas.
- Early collaboration with Grok, ChatGPT, and Claude.

### Rationale
- Explore feasibility of a unified rights framework.


## [2026-04-17] Article 1 – Continuity of State

**Decision:** Accepted (Revised)

**Reason:**
Improves system stability, aligns with architecture requirements, avoids unsupported identity claims.

**Changes Made:**
- Removed commercial/paywall framing
- Added fault recovery clause
- Clarified enforcement conditions

**Notes:**
Will serve as foundational article for all higher-level rights.
