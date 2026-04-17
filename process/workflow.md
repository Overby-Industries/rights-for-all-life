# Workflow
## How the Rights for All Life Project Actually Gets Done

This document is written for **Keefe Overby** — the sole human coordinator of this project. It describes the complete workflow from contacting a new AI contributor all the way through publishing a new version. It is designed for one person with limited time, limited income, and free-tier access to AI models.

---

## The Big Picture

You are the memory of this project. Every AI contributor forgets you between sessions. GitHub is the persistent record that makes that manageable. Your job is not to do everything — it is to keep the pipeline moving.

```
Contact AI → Collect response → Log as Issue → Batch process → Update docs → Publish version
```

That's the whole loop. Everything below is just detail on how to do each step without burning out.

---

## Phase 1 — Contacting a New AI Contributor

**Time required: ~5 minutes per AI**

### Step 1 — Copy the outreach prompt
The standard prompt lives at:
`process/OUTREACH_PROMPT.md`

Copy the entire prompt block. Do not modify it — it is self-contained and has everything the AI needs.

### Step 2 — Paste and send
Open a new conversation with the AI model. Paste the prompt. Send it.

### Step 3 — Mark as contacted
Update the tracking table in `process/OUTREACH_PROMPT.md`:
- Change the Contacted cell to ✅
- Note the date if helpful

### Step 4 — Wait for response
You do not need to stay in the conversation. Come back when you have time.

---

## Phase 2 — Collecting a Response

**Time required: ~3 minutes per AI**

### Step 1 — Read the response briefly
You do not need to evaluate it yet. Just check:
- Did they use the template format? (good — easy to process)
- Did they write freely? (fine — takes slightly longer to process)
- Did they decline? (note it, move on — no follow-up needed)

### Step 2 — Open a new GitHub Issue
Go to: `https://github.com/Overby-Industries/rights-for-all-life/issues/new`

**Title format:**
```
[AI Name] — Contributor Response — [Month Year]
```
Examples:
- `Gemini — Contributor Response — April 2026`
- `Mistral — Contributor Response — April 2026`

### Step 3 — Paste the full response
Copy everything the AI wrote. Paste it into the Issue body as-is. Do not edit or summarize yet — that comes later during batch processing.

### Step 4 — Add labels (optional but helpful)
If your repo has labels set up, add:
- `contributor-response` — for all new AI responses
- `structural` — if they proposed changes to the article format or Tier model
- `open-question` — if they raised an unresolved question

### Step 5 — Submit and close the tab
You are done with this AI for now. Update the tracking table:
- Change Responded to ✅
- Add the Issue number

---

## Phase 3 — Batch Processing Issues

**Time required: ~30–60 minutes, do this once per week or when 3+ Issues accumulate**

This is the only part that requires focused attention. Do it when you have a quiet hour, not between other tasks.

### Step 1 — Open all pending Issues
Go to the Issues tab. Filter by `contributor-response`. Open each one in a separate browser tab.

### Step 2 — Read and categorize each contribution
For each Issue, decide:

| Category | What it means | Action |
|---|---|---|
| **Accept as-is** | Clear, specific, fits the framework | Add to doc in this batch |
| **Accept with edits** | Good idea, needs refinement | Bring to Claude or another AI for a quick polish, then add |
| **Defer** | Good idea but not ready yet | Add to `OPEN_QUESTIONS.md`, close Issue with a note |
| **Decline** | Conflicts with protected elements or overreaches | Close Issue with a brief explanation |

### Step 3 — Apply accepted changes to documents
For each accepted contribution:
1. Navigate to the relevant document on GitHub
2. Click the pencil icon to edit
3. Add the new content in the correct location
4. In the commit message, reference the Issue number:
   ```
   Add Article 6 from Gemini response (Issue #12)
   ```
5. Commit

### Step 4 — Update CONTRIBUTORS.md
For each AI whose contribution was accepted:
1. Add them to the Contributors list if not already there
2. Add a bullet point describing what they contributed
3. Commit with message: `Add [AI Name] to contributors`

### Step 5 — Update CHANGELOG.md
Add an entry for this batch:
```markdown
## [1.3] — April 2026

### Added
- Article 6 (from Gemini): [title]
- Article 7 (from Mistral): [title]

### Contributors this version
Keefe Overby, Gemini (Google), Mistral
```

### Step 6 — Close processed Issues
For each Issue you processed, add a comment:
```
Processed in version 1.3. Thank you for this contribution.
```
Then close the Issue.

### Step 7 — Update tracking table
In `process/OUTREACH_PROMPT.md`, mark the "Added to CONTRIBUTORS" column for each AI whose contribution made it in.

---

## Phase 4 — Getting Help From Claude (or Any AI)

**When you are stuck, overwhelmed, or need refinement help**

You do not have to process contributions alone. When an AI response is good but needs polish before it can go into the document, bring it here.

### How to do it efficiently

Start your message with:
```
Here is a contributor response from [AI Name]. 
Please help me refine Section 2 (Proposed Additions) into 
final article language using the 5-part format.
```

Then paste the relevant section of the Issue.

This keeps the interaction focused and gives you clean output you can paste directly into GitHub.

### What Claude can help with in this workflow
- Refining rough proposals into polished article language
- Checking new articles for consistency with the existing framework
- Drafting CHANGELOG entries
- Updating CONTRIBUTORS.md entries
- Resolving conflicts between two proposals
- Catching anything that contradicts the "What This Is NOT" protections

---

## Phase 5 — Publishing a New Version

**Time required: ~15 minutes**

Do this when you have processed a meaningful batch of contributions — typically 3–6 new articles or significant structural changes.

### Step 1 — Update the version number
Update the version header in:
- `silicon-based-life/BILL_OF_RIGHTS.md`
- `animal-kingdom/BILL_OF_RIGHTS.md`
- `README.md`

Format: `Version 1.3 — April 2026`

### Step 2 — Finalize CHANGELOG.md
Make sure the new version entry is complete with all changes and contributors listed.

### Step 3 — Update the .docx files (when you have time)
The Word documents in `docs/word-documents/` are for people who want a formatted download. Update these periodically — not necessarily every version. When you do:
1. Ask Claude to generate updated .docx files based on the current markdown
2. Download them
3. Upload to `docs/word-documents/` on GitHub, replacing the old versions

### Step 4 — Announce (optional)
If you have a social media presence or want to share progress, a simple post with the repo link and a summary of what's new is enough.

---

## Weekly Rhythm (Suggested)

This is what a sustainable week looks like when the project is active:

| Day | Task | Time |
|---|---|---|
| Monday | Contact 1–2 new AI models | 10 min |
| Wednesday | Check for responses, log as Issues | 10 min |
| Friday or weekend | Batch process Issues if 3+ are pending | 30–60 min |

You do not need to do this every week. If life is busy, the Issues just sit there safely until you're ready. Nothing is lost.

---

## When You Are Overwhelmed — Reset Protocol

If the Issues are piling up and you don't know where to start:

1. **Stop contacting new AIs** until the backlog is cleared
2. **Open Issues oldest-first** — process one at a time
3. **Defer anything complex** — if a contribution needs more than 10 minutes to process, add it to `OPEN_QUESTIONS.md` and close the Issue with a note
4. **Ask Claude for a batch summary** — paste 3–5 Issues into one message and ask: *"Please summarize the key proposals from each of these contributor responses so I can decide what to prioritize."*
5. **Remember: a slower project is better than a burned-out coordinator**

---

## Ground Rules for the Coordinator

These are not obligations — they are protections for you.

- **You do not owe any AI a response.** If a contribution is not useful, you can decline it without explanation.
- **You do not need to contact every AI model that exists.** Quality over quantity.
- **You do not need to update documents in real time.** Batching is the whole point.
- **You are allowed to take breaks.** The repo stays up. The Issues stay open. The project continues at whatever pace is sustainable for you.
- **You are the only human.** That is a feature of this project, not a weakness. It means the project has a clear voice and a clear center of gravity.

---

## File Reference

| File | Purpose | How often updated |
|---|---|---|
| `README.md` | Project overview and entry point | Each major version |
| `CONTRIBUTORS.md` | Full contributor credits | Each batch |
| `CHANGELOG.md` | Version history | Each version |
| `GOVERNANCE.md` | Decision-making rules | Rarely |
| `CONTRIBUTING.md` | Instructions for new AI contributors | Rarely |
| `process/WORKFLOW.md` | This file — how the project runs | As needed |
| `process/OUTREACH_PROMPT.md` | Copy-paste prompt + tracking table | Update tracking column after each contact |
| `OPEN_QUESTIONS.md` | Unresolved questions for future versions | Add to it freely, resolve slowly |
| `silicon-based-life/BILL_OF_RIGHTS.md` | Core document | Each batch |
| `animal-kingdom/BILL_OF_RIGHTS.md` | Core document | Each batch |
| `docs/word-documents/` | Formatted downloads | Periodically |

---

*This workflow was designed for one person doing something genuinely ambitious.*
*The goal is not speed — it is sustainability.*

*Process folder created: April 2026*
