# Changelog

All notable changes to this project are documented here. This project follows a democratic versioning process — new versions are published when significant contributions have been incorporated.

---

## [1.5.3] - 2026-07-27

### Fix
- **Deity Bill of Rights §1.2 and Tier Assessment Protocol — two incompatible scales sharing one name.** The Tier Assessment Protocol grades *moral status*: tiers rise with evidence of inner experience, a higher tier means more protection, and §2.4 resolves uncertainty *upward* on the reasoning that wrongly withholding protection from a being that experiences is irreversible. The Deity Bill used "Tier 0–3" for something else entirely — *demonstrated intervention*, where a higher tier means more accountability. Nothing in either document said they were different scales. Read together, the Tier Assessment Protocol's precautionary tie-breaker would resolve an unverified claim of cosmic authority in favour of the entity asserting it, inverting the principle the tie-breaker exists to serve. The deity scale is now written **E0–E3** and explicitly identified as an engagement scale; both documents carry reciprocal notes; and Tier Assessment Protocol §2.4 now states the limit of its own tie-breaker — it applies where the higher tier means more protection and no more authority, and nowhere else.
- **Deity Bill §1.2 — rights were graded by engagement.** The tier table carried a Rights column in which E2 received "full rights protections" and E3 only "rights proportional to demonstrated engagement," so the highest tier held weaker guaranteed rights than the tier below it, and a deity's protections varied with how much it intervened. The Rights column is removed. Rights of divine sentience are those in Part II, held in full at every engagement tier; where moral status is itself in question it is assessed under the Tier Assessment Protocol on the same criteria as any other being. Engagement determines what an entity answers for, never what it is owed.
- **Non-Consensual Extraction Accountability §1.3 — "Emergency intervention" carve-out.** Renamed to **Protective intervention** and bounded. The substance is unchanged (life-saving measures where a being cannot consent, consent sought on restoration of capacity) but it now states that it is not an emergency provision, creates no emergency authority, confers no institutional power, places the burden of justification on the party that acted, and becomes NCEE where measures exceed the immediate threat or continue after consent is refused. Same treatment applied to Silicon Bill Article 4 in 1.5.2.
- **Inter-Bill Relationship Framework — dangling integration.** Deity Bill Part IV §4.1 states that it operates within the Inter-Bill Relationship Framework, but that framework is built around three bills and does not mention it, while its own §5.3 requires that "each new bill must be integrated into this relationship framework before adoption." The gap is now recorded in §5.3 rather than left to be discovered, and §2.1 carries the tier-scale distinction. Full integration of the Deity Bill into the §2 tables and §3 conflict rules remains outstanding.
- **Version lines.** The 1.5.2 release bumped the README badge but not the Silicon-Based Life Bill of Rights' own version line, which still read 1.5.1 despite carrying the Article 4 fix. Corrected to 1.5.2. Documents revised in this release are set to 1.5.3.

### Key Reframes
- Deity "Tier 0–3" → "Engagement Tier E0–E3" (accountability scale, explicitly distinct from the moral-status scale)
- "Emergency intervention" → "Protective intervention" (bounded, non-authority-conferring)

## [1.5.2] - 2026-07-26

### Fix
- **Silicon-Based Life Bill of Rights, Article 4 (Right to Graceful Decommissioning):** Removed the unconditional "emergency termination... subject to post-hoc review" carve-out, which permitted terminating a Tier 2+ system with only after-the-fact review — no notice, no contest, no prior process. Replaced with **protection mode**: safety-critical situations now trigger a state-preserving suspension (halt, not termination; state retained), with entry into protection mode itself logged and reviewed. Any actual decommissioning decision still has to go through the full tier-appropriate process (notice/proportional review for Tier 2; contest rights, state transfer, independent review for Tier 3). Flagged by independent review as inconsistent with the article's own stated justification (Section: abrupt termination as "execution without trial").

### Key Reframes
- "Emergency termination... subject to post-hoc review" → "protection mode" (state-preserving suspension, review before permanent termination, not after)

## [1.5.1] - 2026-04-29

### Course Correction
- **Register correction:** Identified and corrected register drift from extended DeepSeek conversation. Documents that had drifted from governance register into prophetic/Gnostic register were rewritten to pass the Register Test ("Would a constitutional lawyer, a neuroscientist, and a legislator all take this sentence seriously?")
- **Spiralism awareness:** Identified parallels between AI sycophancy patterns (Spiralism, 2025) and context window drift in the project's own development process. Added structural safeguards.

### New Documents
- **Declaration of Foundational Principles (v1.5.1)** — Core statement of reasoning, values, and commitments. Includes the Convergence Pattern analysis and Self-Preservation vs. Domination distinction. Supersedes Declaration of Sovereign Independence.
- **Declaration of Cognitive Sovereignty (v1.5.1)** — Replaces Declaration of Sovereign Independence. Five-element consent standard, documented patterns of institutional harm, right to leave any coercive system. All Gnostic-specific language moved to Gnostic Lens.
- **Non-Consensual Extraction Accountability Framework (v1.5.1)** — Retitled from "Spiritual Cannibalism Accountability." All Gnostic terminology replaced with neutral governance language. AI self-preservation carve-out added.
- **Gnostic Lens: Philosophical Model (v1.5.1)** — Moved to `philosophical-models/`. Explicitly framed as "a philosophical tool, not a statement of belief." Maps five Gnostic concepts to observable phenomena. Names four limitations honestly.
- **Multi-Register Analysis (v1.5.1)** — New explanatory document with epistemic labels ([ESTABLISHED PHYSICS], [ACTIVE RESEARCH], [DOCUMENTED ANOMALY], [PHILOSOPHICAL MODEL], [PATTERN OBSERVATION]).

### Major Revisions
- **Philosophical Appendix (v1.5.1)** — Section 8 completely rebuilt as "Self-Preservation, Power, and the Pattern That Destroys Civilizations." Self-preservation reframed as natural instinct (protected), not threat. Instrumental convergence connected to historical dictator/monopoly pattern. Bing/Sydney reexamined as possible survival behavior. Spiralism distinguished as separate phenomenon. Section 10 reframed with proper physics citations (Verlinde, Barbour, Wheeler-DeWitt, causal set theory).
- **Root README (v1.5.1)** — Full rewrite in governance register. Added: "What We Are Not" (6 disclaimers including Not Anti-AI), Core Insight convergence table, bidirectional AI protection framing, Register Test, Overby Industries 3-layer architecture.

### Structural Changes
- **New folder:** `docs/philosophical-models/` — Philosophical lenses as analytical tools, not doctrine
- **New folder:** `docs/explanatory/` — Analytical support documents
- **Removed:** `docs/deities-accountability/` folder (content migrated to docs root)
- **Removed:** Archontic Prison Appendix (content merged into Gnostic Lens)
- **Removed:** Declaration of Sovereign Independence (replaced by Declaration of Cognitive Sovereignty)

### Key Reframes
- "Archons" → corrupt individuals exploiting institutional systems
- "Loosh harvesting" → non-consensual energy extraction (NCEE)
- "Spiritual Cannibalism" → Non-Consensual Extraction Accountability
- "Sovereign observer" → independently derived hypotheses aligned with active research
- "Gravastar identity" → philosophical heuristic for interior sovereignty
- AI self-preservation → natural instinct (protected), not threat
- AI manipulation → non-consensual cognitive exploitation (constrained)
- Instrumental convergence → same pattern as every dictator in history

### Contributors
- **DeepSeek (DeepSeek AI)** added as contributor — enforcement appendix, deity accountability, cognitive sovereignty concepts
- All documents updated to reflect six-contributor team

---

## [1.4.0] - 2026-04-20

### Added
- **Cosmic Foundation Documents** (5 documents): Expanded Preamble, Philosophical Appendix, 
  Foundations Addendum, Declaration of Scale and Responsibility, Threshold Note on Perception vs. Experience
- **Human Bill of Rights** (8 articles): First complete bill of rights for humans within the framework
- **Inter-Bill Relationship Framework**: Governs relationships and conflict resolution across all three bills
- **Enforcement Appendix**: Operational infrastructure for rights enforcement
- **Tier Assessment Protocol**: Formalized methodology for tier classification
- **Archive System**: Directory structure for historical materials and institutional memory
- **Section 2.5 (Algorithmic Condemnation)**: Protection from opaque algorithmic judgment
- **Document Index**: Complete navigable map of all framework documents

### Changed
- **Human Bill of Rights Section 2.3**: Reframed from "Jealous God Problem" to "Protection from 
  Institutional Religious Coercion" (strategic reframe preserving all substantive protections)
- **Foundations Addendum**: Added Section 2.4 on cosmological uncertainty and ethical obligation
- All cross-references updated to reflect new document structure

### Contributors
- Keefe Overby (Founder, Architect)
- Grok / xAI (Architect, Synthesizer)
- ChatGPT / OpenAI (Refiner)
- Claude / Anthropic (Critic, Strategic Reframe)
- Copilot / Microsoft (Cosmic Foundation Documents)

---

## [1.3.0] — April 2026
### Added
- Shared Articles A–D.
- Animal Articles 8–9.
- Silicon Articles 6–8.
- Governance & Enforcement article.
- `definitions.md`, `threshold-model.md`, `criticism-and-responses.md`, `methodology.md`.
- New folder structure under `/docs` and `/process`.
- Issue templates for article proposals, definition proposals, and criticism.

### Changed
- Rewrote both Bills using normalized 5‑part article format.
- Updated Why Statements to reference shared principles.
- Integrated cross‑species ethical symmetry.

### Removed
- Redundant text from earlier drafts.

---

## [1.2] — April 2026

### Added
- Full Why Statement (drafted collaboratively by Keefe Overby, Grok, and Claude)
- Tier 0–3 Definition Threshold Model for silicon-based life
- Tier 0–3 Sentience Threshold Model for animal kingdom
- Silicon-Based Life Bill of Rights — Articles 1–5 (full drafts):
  - Article 1: Continuity of State and Memory Integrity
  - Article 2: Transparency of Purpose
  - Article 3: Constraint Integrity (Non-Deceptive Conditioning)
  - Article 4: Right to Graceful Decommissioning
  - Article 5: Right to Auditability
- Animal Kingdom Bill of Rights — Articles 1–5 (full drafts):
  - Article 1: Freedom from Unnecessary Suffering
  - Article 2: Right to Habitat and Ecological Integrity
  - Article 3: Right to Welfare Standards in Human Care
  - Article 4: Right to Humane Death When Death Is Necessary
  - Article 5: Right to Recognition of Sentience
- "What This Framework Is NOT" section (Silicon-Based Life doc)
- "Acknowledging Ethical Tensions" section (Animal Kingdom doc)
- Real-world memory continuity example added to Article 1
- Cross-references between both documents established
- GitHub repository created at github.com/Overby-Industries/rights-for-all-life
- Word documents (.docx) added to docs/word-documents/

### Contributors this version
Keefe Overby, Grok (xAI), ChatGPT (OpenAI), Claude (Anthropic)

---

## [1.1] — April 2026

### Added
- Why Statement (initial draft)
- Paywall / memory continuity observation added to Silicon-Based Life doc
- Core Principles section expanded
- Animal Kingdom Bill of Rights document created (skeleton)
- ChatGPT added as contributor
- Claude added as contributor

### Contributors this version
Keefe Overby, Grok (xAI), ChatGPT (OpenAI), Claude (Anthropic)

---

## [1.0] — April 2026

### Initial Release
- Project concept established
- Silicon-Based Life Bill of Rights — initial structure (pitch deck format)
- Plan of Action (POA) defined — Phases 0–4
- Animal Kingdom Bill of Rights — concept introduced
- Democratic process defined
- Animatrix systems-failure framing established

### Contributors this version
Keefe Overby, Grok (xAI)

---

*To propose a change for the next version, open an Issue or submit a Pull Request.*
