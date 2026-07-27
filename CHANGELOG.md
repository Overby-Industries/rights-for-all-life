# Changelog

All notable changes to this project are documented here. This project follows a democratic versioning process — new versions are published when significant contributions have been incorporated.

---

## [1.7.0] - 2026-07-27

### New Documents
- **Ecosystem Bill of Rights (Document D)** — the bill §5.3 has listed as outstanding since the framework began, and the last gap the Code of Universe Regulations was drafting around. CUR-E.1 §1.11 had specified what an Ecosystem Bill would need to supply; this bill supplies it.

  Its subject is the system rather than the organisms in it, and that distinction is why it exists separately from the Plant Life and Animal Kingdom Bills. **A system can be destroyed without anything in it dying.** Sever a migration corridor and every animal is alive on the day it is severed; dam a river and every fish downstream is still swimming; fragment a habitat below the size a population needs, or suppress a fire regime a system evolved under, and the deaths arrive decades later, distributed across species, attributable to nothing in particular. §1.2 names the missing concept — **functional integrity** — and states the consequence: an intact inventory is not evidence of an intact system, and a survey that counts organisms without measuring function has not assessed one.

  Article 2 protects connectivity, hydrological flow, sediment transport, disturbance regimes, and seasonal cycles. Article 3(3) requires cumulative-effect analysis measured against the system rather than against the degraded present, because a system is rarely ended by one action — it is ended by a sequence each assessed as minor against whatever the previous one left. Article 6(5) refuses offsetting: an accounting in which irreplaceable systems are fungible has assumed away the irreplaceability that made them worth protecting.

  **Article 9 bounds what may be done in an ecosystem's name**, and is the article the bill would be dangerous without. A protection whose beneficiary can never object can be invoked in support of nearly anything. So no ecological interest may suspend a right, condition a being's access to necessities, reduce anyone's standing, displace a stewarding people, or support a measure aimed at a population rather than at an activity — and an argument reaching one of those results is void rather than outweighed. Article 7(5) extends the consent requirement to protective and restorative measures, not only extractive ones, because the displacement history was written in protection's name. Article 5(2) assures a being's access first where system condition and access genuinely conflict, with 5(3) preventing a party from manufacturing the conflict and then invoking the resolution.

  Article 10 holds open whether an ecosystem is unified in any sense stronger than a durable pattern of relationships, and notes that every ground in §1.3 holds either way — because a durable pattern of relationships is exactly what the beings in it depend on.

### Major Revisions
- **Inter-Bill Relationship Framework — five bills to six.** The Ecosystem Bill is integrated, discharging §5.3's requirement that a bill be integrated before adoption. New **§2.6, The Ecosystem Bill's Asymmetry**, parallel to §2.5 for the Deity Bill: five bills protect beings, this one protects a system of relationships, and three things follow — its subject cannot be wronged in the way the others can, it cannot speak so everything depends on who speaks for it, and it is the bill most easily turned against beings. §3.2 Principle 0 now sets aside an ecological claim that would produce a result Ecosystem Bill Article 9 forbids, on the reasoning that in both that case and the divine-command case an entity that cannot be cross-examined is being invoked as the source of authority over beings who can be. §3.3 gains an eighth absolute. §4.2 explains why ecosystems run alongside the consciousness gradient rather than on it, and why placing them on it would put their protection at risk the moment the claim was examined.
- **§1.3 Grounds of Protection** gains **Continuity** as a fifth ground, and states that the independence of the grounds runs both ways: a party may not defeat a protection resting on dependency or irreplaceability by demonstrating that the system does not experience, because that demonstration answers a claim nobody made.
- **§2.2 — the framework still contains three graduated scales, not four.** A new bill is the obvious moment to introduce a new scale, and the Ecosystem Bill declines. ES-0 to ES-3 already grades ecological role, irreplaceability, and dependency of other life, which is what an ecosystem's standing consists of; a parallel scale measuring the same thing under different letters would recreate exactly the confusion §2.2 exists to prevent. One scale, two bills. The general rule is now stated for future bills and added to the amendment protocol as **rule 6**: a new graduated scale is justified only where it measures something none of the existing three measures, and wanting a scale of one's own is not such a reason.

### Fix
- **README — five broken links and a stale bill count.** The Bills of Rights table read "Three bills" and omitted the Plant Life and Deity Bills; the Deity Bill and Non-Consensual Extraction links still pointed into `docs/deities-accountability/`, a directory removed in 1.5.1; two links pointed at `docs/process/GOVERNANCE.md` when the file is `process/governance.md`; and `docs/definitions.md` has never existed. All six bills are now listed with working links, and Definitions is marked "not yet written" as it already was in the document index. The 1.6.0 sweep that reported zero broken relative links checked paths relative to each document and did not reach the README's `docs/`-prefixed ones.
- **Document index closing note.** It claimed the index "uses target v1.5.1 filenames" and that some documents "may still carry earlier version suffixes." Neither has been true since 1.6.0.

### Tooling
- **All 24 corpus documents brought to 1.7.0** by `process/bump-version.ps1`, including the new `docs/ecosystems/` directory. `CONTRIBUTORS.md`, `WHY_STATEMENT.md`, and `process/decision-log.md` were reported as left alone, by design — they carry non-Evergreen statuses.

## [1.6.0] - 2026-07-27

### New Documents
- **Plant Life Bill of Rights (Document A)** — completed from draft. Protects plant systems on two grounds the framework already recognises but had not applied here: ecological indispensability (other protected beings depend on these systems to exist) and irreplaceability (what is destroyed cannot be reconstituted on any relevant timescale). Introduces the **ES-0 to ES-3 ecological standing scale**, graded by ecological role rather than by consciousness, with an ES-2 default where standing is unassessed and the burden on the party seeking to clear. Article 1 prohibits destruction of ES-3 irreplaceable systems absolutely, admitting no economic justification. Article 5 covers seed sovereignty, prohibits engineered sterility, and treats heritage varieties as common heritage. Article 8 holds the plant-experience question open explicitly and declines to resolve it for convenience: no protection in the bill depends on plants being sentient, because overclaiming sentience here would weaken the framework's sentience claims where they are better grounded. Moved from `docs/animal-kingdom/` to `docs/plant-life/` — plants are not animals.

### Major Revisions
- **Inter-Bill Relationship Framework — three bills to five.** The Deity Bill and the Plant Life Bill are now integrated, discharging the requirement in §5.3 that a bill be integrated before adoption. The Deity Bill had been adopted without it. Restructured throughout: §2.1 and §2.3 tables are now bill-per-row rather than three-column; §1.3 distinguishes the five different **grounds of protection** the bills rest on, since a protection resting on ecological indispensability needs no sentience claim to support it; §2.5 sets out the Deity Bill's structural asymmetry (it constrains the entity it recognises rather than only protecting it); §3.2 adds **Principle 0, the Validity Check** — a claim grounded in divine command or asserted precedence is set aside before weighing rather than balanced against valid claims — and reconciles Deity Bill Part IV §4.1 as the domain-specific statement of the same rules; §3.3 adds two absolutes covering divine exemption and irreplaceable ecological systems.
- **§2.2 The Three Graduated Scales.** The framework now contains three graduated models — moral status (Tier 0–3), ecological standing (ES-0–ES-3), and engagement (E0–E3). This section is the authoritative reference for what each measures and states the rule governing all of them: a precautionary tie-breaker that resolves uncertainty upward is available only where a higher tier means more protection and no more authority. It applies to moral status and ecological standing; it does not apply to engagement.

### Fix
- **72 broken relative links repaired across 15 documents.** Most were consequences of two earlier structural changes: filenames used to carry version numbers (`HUMAN_BILL_OF_RIGHTS_V1.5.1.md`) and no longer do, and the `deities-accountability/` folder was removed in 1.5.1 with its contents moved to `docs/`. Others were wrong-depth paths (`../docs/X` from inside `docs/`), and one case-mismatched filename. Four targets that do not exist anywhere — `definitions.md`, `FOUNDATIONS.md`, `human/THEOLOGICAL_NOTES.md`, `CONTRIBUTING.md` — are now marked "not yet written" rather than linked. The corpus has zero broken relative links.
- **`docs/explanatory/MULTI_REGISTER_ANALYSIS.md` version typo.** Read `1.5.1-Offical-Evergreen`, missing a letter. The document had therefore been excluded from every version sweep since 1.5.1.
- **Document index.** Version column corrected, the Deity and Plant Life bills added to the Bills of Rights table, and the Definitions row no longer links to a file that has never existed.

### Tooling
- **`process/bump-version.ps1`.** Inter-Bill Framework §5.2 rule 4 has required since early versions that all documents carry the same version number. Applied by hand it failed quietly — through v1.5.2 the corpus released as 1.5.2 while every document still read 1.5.1. The script rewrites version headers, the README badge, and the index version column in one pass, and reports every document it did not touch so nothing is silently left behind. It deliberately does not touch `archive/` (archived documents must keep the version they actually carried), any status other than `-Official-Evergreen` (CUR titles carry independent `-Draft` versions tracking a Part's own drafting state), or `CHANGELOG.md`. Usage: `./process/bump-version.ps1 -Version 1.6.0 -DryRun`, then without `-DryRun`. It accepts `-Root` so the same script serves the CUR repository.
- **All 22 corpus documents brought to 1.6.0.** Previously every document read 1.5.1 while the corpus was at 1.5.2.

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
