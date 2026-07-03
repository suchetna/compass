# Case Study: AI-Assisted Meeting Intelligence Rollout
### An illustrative scenario — not an account of a specific past engagement

> **A note on what this is.** This case study is a constructed example, built to show how Compass works when applied to a real-shaped problem end to end. The organization, numbers, incidents, and outcomes below are illustrative — designed to be realistic, not reported. Treat it the way you'd treat a worked example in a textbook or a hypothetical in a strategy whitepaper: useful for seeing the framework in motion, not a claim about any specific company or project.

---

## 1. Scenario

A global technology company (~3,800 employees, engineering + sales + marketing, offices in India and the US) rolls out AI-assisted features — meeting summarization, smart drafting, intelligent search — into its internal productivity suite. The change/communications function is embedded alongside Product, IT, and HR. The rollout runs over roughly six months: discovery → pilot → phased rollout → embedding.

This scenario sits in the "medium volume, medium risk" zone of the [Workflow Audit Checklist](../toolkit/workflow-audit-checklist.md) — internal-only, but touching sensitive project discussions.

---

## 2. Readiness Assessment (illustrative scoring)

Scored against the six dimensions from the [AI Readiness Assessment](../toolkit/ai-readiness-assessment.md), adapted slightly for this org-wide (not comms-only) rollout:

| Dimension | Score (1–5) | Rationale |
|---|---|---|
| AI strategy alignment | 4 | Tied to a clear productivity narrative, though not yet part of a formal enterprise AI strategy |
| Data & privacy readiness | 3 | Strong security baseline; employee questions about data use and model training remained partly unanswered |
| Tech & infrastructure | 4 | Existing identity management and feature-flagging supported a controlled, segmented rollout |
| Talent & skills | 3 | Enthusiastic early adopters, but broad AI literacy was low; training leaned on feature demos rather than judgment-building |
| Governance & risk | 3 | General acceptable-use policy existed; AI-specific guardrails were still being formalized |
| Change & comms capability | 5 | Mature change infrastructure already in place from prior large tool rollouts |

**Overall: 3.7/5 — "ready with targeted gaps,"** concentrated in AI literacy and AI-specific governance. This is a common Stage 2 ("Emerging") profile: strong process muscle from unrelated prior work, but the governance and people pillars haven't caught up to the technology.

---

## 3. Workflow, as it might run

**Business goal:** reduce time spent by PMs, engineering managers, and marketing leads on post-meeting documentation and follow-up, while standardizing quality.

1. **Pre-meeting** — owner enables AI meeting summarization for eligible meetings, tagged to a project ID.
2. **During the meeting** — AI takes live notes and flags decisions; a designated note-taker corrects mislabels in real time. Participants see a banner and hear a spoken notice that transcription is active.
3. **Immediate post-meeting** — AI proposes a structured summary (decisions, actions, owners, deadlines). The meeting owner edits it, checks for anything sensitive, and publishes.
4. **Follow-up drafting** — owner uses an AI drafting feature to generate stakeholder follow-ups, reviews tone and accuracy, edits for context, sends manually.
5. **Archiving & search** — summaries are stored with project metadata; later searches surface related decisions across meetings. Strong examples feed back into training material.

---

## 4. Workflow Audit (illustrative)

**Workflow ID:** AI-MS-01 · **Name:** AI-assisted meeting summary & follow-up
**Business owner:** Director, Product Management · **Technical owner:** Productivity tools/IT
**Primary users:** PMs, EMs, marketing leads · **Secondary:** sales managers, HR project leads
**Systems involved:** productivity suite (calendar, notes, AI assistant), integrated email drafting, internal knowledge repository

**Process & controls:**
- A change-approval forum authorized the feature for internal use with specific guardrails
- Pilot cohort nominated by business owners; wider rollout gated on a post-implementation review
- A short playbook covered how to enable/disable AI capture, sample opening scripts disclosing recording, and edit guidelines
- Quarterly monitoring: % of meetings using AI summary, pilot-team satisfaction, incident log for mis-summaries or privacy concerns

**Illustrative 3-month snapshot:**
- ~55% of recurring project meetings in the pilot group using AI summaries at least weekly
- 3 minor incidents where sensitive content was captured and needed manual redaction
- Informal complaints about "robotic" tone in AI-drafted follow-ups where the owner under-edited

**Corrective actions taken:**
- Added an explicit "review and personalize" step to the workflow itself, not just guidance
- Defined categories where AI capture is disallowed by default (performance conversations, HR matters, certain customer-sensitive discussions)

---

## 5. Risk Tier Placement

Mapped against the [Governance & Risk Matrix](../toolkit/governance-risk-matrix.md):

- **Data sensitivity:** internal project information, occasional confidential material
- **Impact of error:** mis-summaries could misattribute actions or misstate decisions — but a human always reviews before anything is distributed
- **Regulatory exposure:** low-to-moderate; internal-only content
- **Automation level:** assistive, not autonomous

**Placement: Tier 2 (Medium risk).** Not Tier 1, because of the mis-communication and privacy surface; not Tier 3/4, because every output passes through a named human before it leaves the workflow. Tier 2 controls apply: mandatory human review, a clear way to opt out of being recorded, and defined no-AI meeting categories.

---

## 6. RACI (illustrative)

Using the [RACI Template](../toolkit/raci-template.md), extended with governance-specific roles for an org-wide rollout:

| Activity | Exec Sponsor | Governance Board | AI CoE | Business Owner | IT | Legal/Compliance | Internal Comms |
|---|---|---|---|---|---|---|---|
| Approve use case & risk tier | A | R | C | C | I | C | I |
| Configure tools & access | I | I | C | C | R | I | I |
| Define workflow steps & guardrails | I | C | R | A | C | C | C |
| Draft enablement & comms content | I | I | C | C | I | C | R/A |
| Deliver training & office hours | I | I | R | C | C | I | C |
| Monitor adoption & satisfaction | I | C | C | A/R | C | I | C |
| Handle incidents | I | C | C | R | C | A | C |
| Quarterly review | A | R | C | C | C | C | C |

One accountable owner per activity; Internal Comms is Responsible/Accountable specifically for the enablement content, not for the underlying policy — a distinction worth keeping explicit.

---

## 7. ROI (illustrative numbers)

Using the [ROI Measurement Template](../toolkit/roi-measurement-template.md), with a 400-user pilot cohort (out of 3,800 total) and abstracted cost units so the arithmetic is checkable without implying real currency figures.

**Baseline (pre-AI):** ~45 min/meeting on documentation, 4 relevant meetings/week/user → 3 hrs/user/week.
**Post-AI (6–9 months in):** ~25 min/meeting → 1.67 hrs/user/week.

| | Before | After | Change |
|---|---|---|---|
| Time per user per week on documentation | 3.0 hrs | 1.67 hrs | -1.33 hrs |
| Across 400-user cohort, per week | 1,200 hrs | 668 hrs | -532 hrs |

If roughly 60% of that recovered time converts to genuinely higher-value work (a deliberately conservative assumption — the rest is assumed lost to friction, context-switching, or simply not being reinvested), and annual running costs for licensing, enablement, and governance are netted out, the illustrative model lands at a **positive ROI in the range of ~150–220% over 12 months**, even under a more conservative 40% conversion assumption.

**Qualitative signals:** more consistent structure in leadership updates, meeting owners reporting less friction around documentation, a modest rise in perceived transparency because decisions were captured more systematically.

---

## 8. What this demonstrates

Run end to end, this scenario shows the Compass framework doing what it's meant to do: turning "we adopted an AI tool" into a structured account of readiness, workflow design, risk placement, decision rights, and measurable outcome — the four pillars working together rather than technology adoption happening in isolation.

If applying Compass to your own workflow, replace every number and finding here with your actual data. The value of this document is in the *shape* of the analysis, not the specific figures.
