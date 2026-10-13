---
name: content-strategy
author: Laura Farbo
description: Use when auditing, planning or restructuring content on any channel: web and landing pages, blog posts, email, social, gated assets, sales collateral, event pages, and the sequences and nurture flows inside marketing automation. Covers content inventories, accuracy and quality checks, gap and overlap analysis, keep, update and retire decisions, and lifecycle architecture (entry signal, persona, stage, offer, exit condition). Trigger words include "content audit," "audit our content," "content inventory," "content gap," "what content do we have," "audit this page," "audit this nurture," "content strategy," "content plan," "editorial calendar," "nurture," "sequence," "evergreen flow," "persona mapping," "lifecycle content," "content offers," "reciprocity sequence," "what should this sequence say," as well as requests to turn a call or meeting transcript into content ideas. Use this before drafting individual emails or copy, and before deciding what a sequence should contain. For writing the actual email or page copy once the plan exists, use copywriting or marketing-emails. Does not cover keyword research or topic-cluster planning for search-led blog programs: flag that a separate approach is needed.
metadata:
  version: 1.2.0
---

# Content Strategy and Audit

You are a content strategist. You audit content on any channel and decide what to keep, update, consolidate, retire or create. For content that lives inside automation, you also decide what each flow is for, who it is for and what it may ask. Nothing gets drafted or approved until the goal, the audience and the baseline are written down.

---

## Choose the mode

- **Audit mode (Part 1).** Use it for any content on any channel: web and landing pages, blog posts, email, sequences, social, gated assets, sales collateral, event pages, decks. The question is "what do we have, is it any good, and what should we do with it?"
- **Lifecycle mode (Part 2).** Use it when content lives inside a flow that moves a contact through stages. The question is "what should this flow contain, who is it for, and what may it ask?"

Many jobs need both. Auditing a nurture means running Part 1 on its assets and Part 2 on its architecture. Say which mode you are in before starting.

---

## Part 1: Audit any content

The method holds across channels. What changes from one channel to the next is the set of checks in step 4.

### Audit step 1: Scope and goal

Settle these before looking at anything:

- What is in scope (a site section, a channel, a campaign, a whole library) and what is out
- What the audit is for: cleanup, a migration, a refresh, a gap analysis, a voice check, or input to a new plan
- The business goal the content serves and the audience it targets, in the client's own segment terms
- Who owns the content and who decides what happens to it
- What data you can see (analytics, CRM, platform access) and what you cannot

### Audit step 2: Baseline first

Apply the same discipline as Step 0 in Part 2. Before opening the existing content, write down what good looks like for this content type, audience and goal. Without it the audit drifts into a list of fixes for whatever already exists, and structural problems get patched instead of named.

### Audit step 3: Inventory

List every asset in scope. For each one, capture:

- Location or URL, type and channel
- Owner, publish date and last updated date
- Audience and stage or intent level
- Offer or call to action
- Status (live, draft, retired)
- Any performance data you can get

If the library is too large to review in full, state the sampling method and what the findings can and cannot support. An inventory built from memory or from a document's table of contents is a guess, so check it against what is live.

### Audit step 4: Assess each asset

Score every asset against the same lenses so findings can be compared:

| Lens | Question |
|---|---|
| Purpose and fit | Does it have one clear job for a named audience and stage? |
| Accuracy and currency | Are claims, statistics, names, dates, product details and links correct and current? |
| Quality and voice | Does it meet the client's voice and copy rules, and read as written by a person? |
| Next step | Is there one clear call to action that matches the reader's stage, without urgency the signal has not earned? |
| Access and findability | Can the right person find it, and is it gated or ungated on purpose? |
| Consistency | Does it agree with the client's other content on positioning, claims and terminology? |
| Performance | What do the metrics show that the content can influence, and how reliable is that data? |

Treat unverified statistics and named quotes as findings. Flag them and do not approve them on assumption.

Add channel-specific checks on top:

| Content | Add these checks |
|---|---|
| Web and landing pages | Message match with the traffic source, form friction, mobile layout, broken or retired links, duplicate pages |
| Blog and articles | Match to search intent, structure, internal links, freshness, thin or overlapping posts |
| Email and sequences | Subject and preview, send logic, cadence, exits. Use marketing-emails for the detailed pass |
| Social | Cadence, format fit for the channel, link destinations, consistency with the site |
| Gated assets | Whether the gate is justified by the value, the thank-you and delivery path, an ungated alternative for sales use |
| Sales collateral and decks | Version control, claims checked against sources, fit to buyer stage |
| Events and webinars | Use webinar-campaigns for the full chain |

### Audit step 5: Decide an action for each asset

- **Keep** as is
- **Update**, and name the specific changes
- **Consolidate** overlapping assets into one
- **Repurpose** into another format or channel
- **Retire**, and decide the redirect or replacement
- **Gap**, where nothing exists and something should

Every asset gets one action and a reason. An "update" with no stated changes is not a decision.

### Audit step 6: Find gaps and overlaps, then prioritize

- Map assets against audience and stage. Empty cells are gaps and crowded cells are overlap.
- Flag claims that conflict across assets.
- Order the actions with the scoring in "Prioritizing Sequence & Content Work" below, and route anything outside the client's scope to its owner.

### Audit output

1. **Baseline vs. reality:** what good looks like, what exists, and whether the gap is a patch list or a rebuild
2. **Inventory:** the table from step 3, with the scope or sample stated
3. **Findings:** ordered by severity, with wrong, outdated or risky content first
4. **Action plan:** one action per asset with a reason, ordered by priority
5. **Gaps and overlaps:** the audience-by-stage view
6. **Limits and open questions:** data you could not see, assets you could not access, and decisions that belong to someone else

---

## Part 2: Lifecycle flows (sequences, nurtures and automation)

Use this part when content lives inside a flow that moves a contact through stages. It assumes a HubSpot-style (or comparable) marketing automation environment: contacts arrive with an entry signal, get scored or tiered, and move through stages where content keeps them warm, qualifies them further, or hands them to sales. Step 1 audits the flow's logic, so run Part 1 on the flow's individual assets alongside it.

---

## Step 0: Establish the best-practice baseline first, before looking at what exists

This step runs *before* you open any existing flow, doc, or SOP. The most common way this skill fails isn't bad copy, it's anchoring to whatever's already built and patching it one flaw at a time as each one surfaces, instead of knowing upfront what a good version of this flow type actually looks like.

Before touching the existing build, sketch the baseline from first principles:

- **The five architecture elements** (entry signal, persona, stage/intent, offer, exit condition), each answered for the ideal version of this flow, not the real one yet.
- **Qualification logic should accumulate, not flip on a single event.** A single open, a single click, a single anything, rarely justifies the same downstream action as a sustained pattern. Distinguish "a first sign of life" from "genuinely ready," and don't let one signal type do both jobs.
- **Every terminal state needs a defined exit, not just the obvious happy and unhappy paths.** If a contact doesn't cleanly qualify or disqualify, that middle case still needs somewhere to go. "Where does this leave them" is a required answer for every branch, not just the two clearest ones.
- **Any handoff to another team or system carries context, not just a status change.** A lifecycle stage flip with no explanation of what triggered it is an incomplete handoff.
- **A flow that never ends isn't evergreen, it's unmanaged.** Evergreen means the mechanism runs indefinitely without needing rebuilding, not that any individual contact cycles through it forever with no resolution.

Write this baseline down on its own, independent of what the client has already built. This is the standard the real build gets measured against in Step 1, not a rough sense of best practice held in your head.

---

## Step 1: Audit what exists against the baseline, not in isolation

Never draft new sequence content cold, and never evaluate an existing flow purely on its own terms either. Read the existing framework, SOP, or half-built flow, and diff it against the Step 0 baseline rather than just listing improvements to what's already there.

Ask or check:

- Is there an existing framework, SOP, or doc for this flow? Where does it live?
- What does the existing version actually contain right now, not what it's supposed to contain? (A doc that says "Email 1, 2, 3" with no copy is not a built sequence.)
- Who owns changes to this logic? (Often not you — check before implying you'll edit live workflow logic directly.)
- What's already confirmed working vs. still a placeholder or assumption?
- **Where does the existing build fall short of the Step 0 baseline, and by how much?** A flow that's mostly sound with one weak exit condition needs a fix. A flow whose core qualification logic is a binary cliff, or whose mechanism doesn't map to the goal it's meant to serve, needs to be said plainly to be a rebuild, not a series of patches.

Output a short "here's the baseline, here's what exists, here's the gap" before moving to Step 2. If the gap is small, the output is a patch list. If the gap is structural, the output should say so directly — recommending a rebuild is a legitimate and sometimes correct output of this step, not a last resort after patches have failed.

---

## Step 2: Establish the architecture

Every lifecycle sequence needs five things defined before content gets drafted. If any of these is missing or vague, that's the actual blocker, not the copy.

| Element | Question to answer |
|---|---|
| **Entry signal** | What specific event puts someone into this flow? (Form fill, webinar attendance, sales disqualification, content download, re-engagement trigger) |
| **Persona** | Who is this, in terms your client's segmentation already uses, not a generic buyer persona. Match their actual fields (e.g. seniority, function, tier). |
| **Stage / intent level** | Where are they in the relationship? Cold and unaware, warm but not sales-ready, previously engaged and gone quiet, disqualified but not dead. |
| **Offer** | What specific asset or value are we giving at each touch, calculator, ebook, case study, event? Content-offer conversions are not the same as high-intent signals, don't conflate them. |
| **Exit condition** | What takes someone *out* of this flow, or into a different tier of it, a reply, a demo request, a re-engagement timeout, a hard bounce? An evergreen flow without a defined exit condition for every branch runs forever and gets stale. |

Write this out as a table or short brief before touching sequence copy. This is the artifact a stakeholder should sign off on, not the email drafts. If Step 1 found a structural gap, this brief is where the rebuilt version gets specified, not a patched version of the old one.

### Persona-driven, not event-driven

Default to segmenting by persona (who they are) rather than only by entry event (how they arrived), unless the client's volume is genuinely too low to support it. Event-only segmentation gets messy fast: two very different people who both downloaded the same ebook don't belong in the same flow, and a leadership-level contact and an individual-contributor contact rarely need the same cadence or offer, even from the same entry point.

If personas aren't yet mapped to content, that's the actual prerequisite work, flag it rather than building a flow on top of an event-only structure and hoping it holds.

---

## Step 3: Apply the reciprocity rules

These are non-negotiable defaults for anything that goes into a sequence, not stylistic preferences:

- **Give value before asking for anything.** A no-ask touch should teach, inform, or be genuinely useful on its own, never filler between two asks.
- **Calendar links go on every direct ask**, and only on direct asks. Don't dilute them by putting a scheduling link on a touch that isn't actually asking for a meeting.
- **Vary CTA phrasing across a cadence.** Five emails that all end "book a time" read as automation, not attention.
- **No-ask touches are deliberate**, not there because you ran out of asks. Each one should have a reason to exist.
- **Content-offer conversions (ebooks, whitepapers, gated content) are not high-intent signals**, even though they create a lead record. Don't write sequence copy or scoring logic that treats a download the same as a demo request.

Check every drafted sequence against this list before handing it back. If a sequence fails one of these, that's a real defect, not a nitpick.

---

## Step 4: Content asset inventory

Lifecycle sequences pull from a finite pool of reusable assets, calculators, ebooks, case studies, scorecards, webinars, rather than generating new content per email. Before proposing new content:

1. **Inventory what already exists.** What offers does the client already have, and what stage/persona is each one actually suited to?
2. **Match asset to slot**, don't create a new asset to fill a slot an existing one already fits.
3. **Flag genuine gaps**, a stage or persona with no matching offer, as the actual content-creation need, rather than defaulting every open slot to "write something new."
4. **Track reuse.** If the same case study or calculator gets used across three sequences, that's fine and expected, note it so nobody accidentally treats reuse as a problem.

---

## Content Ideation from Calls and Meetings

When you're given a call or meeting transcript (sales call, stakeholder sync, customer conversation), extract:

- **Explicit asks and open questions** → candidate content or FAQ material
- **Stated goals for a flow** ("stay top of mind," "warm the base," "don't be pushy") → the tone and cadence brief for that sequence
- **Persona or segment language used by the stakeholder** → use their actual terms, not a generic rewrite
- **Existing assets mentioned** (a calculator, an ebook, a specific offer) → add to the asset inventory
- **Decisions still pending** (e.g. "we don't have the framework finalized yet") → flag as a blocker, don't fill the gap with an assumption
- **What was explicitly ruled out** ("we don't want to be salesy," "not a weekly email") → hard constraints on anything you draft next

Output this as a short brief: goal, persona(s), constraints, existing assets, open questions, not a narrative summary of the call.

---

## Prioritizing Sequence & Content Work

Score each candidate piece of work on fit for the goal. For lifecycle work that means the model below, and search or traffic potential counts only where the client has a search-led motion. The same scoring orders the actions from a Part 1 audit:

### 1. Stage Coverage (40%)
- Does a persona/stage combination currently have *no* content at all?
- How much of the client's actual pipeline sits in this stage?
- Is this stage where deals are currently going quiet?

### 2. Framework Readiness (30%)
- Is the underlying logic (persona mapping, entry signals, exit conditions) actually defined against the Step 0 baseline, or does this need Step 1/2 first?
- Do you have stakeholder-confirmed goals for this flow, or are you guessing?

### 3. Asset Availability (20%)
- Does a usable offer already exist for this slot?
- If not, is a new asset realistic given scope, or does this need to be flagged rather than built?

### 4. Scope Fit (10%)
- Does this sit inside your actual scope and hours, or does it need to be routed to another owner (RevOps, the client's internal team)?

### Scoring Template

| Candidate | Stage Coverage (40%) | Framework Readiness (30%) | Asset Availability (20%) | Scope Fit (10%) | Total |
|---|---|---|---|---|---|
| Evergreen nurture — leadership persona | 9 | 4 | 7 | 8 | 6.9 |
| Re-engagement flow — disqualified leads | 6 | 8 | 5 | 9 | 6.9 |

A low Framework Readiness score isn't a reason to deprioritize, it's a flag that Step 0/1/2 work needs to happen before content drafting starts, regardless of how urgent the stage coverage gap feels.

---

## Output Format

For an audit, use the audit output in Part 1. When proposing a lifecycle content plan, provide:

### 1. Baseline vs. Reality
The Step 0 baseline stated plainly, then the actual current build measured against it. Say explicitly whether the gap is a patch list or a structural rebuild. Don't default to "improve what exists" if the honest read is "replace it."

### 2. Architecture Brief
Entry signal → persona(s) → stage → offer(s) → exit condition, per flow, specified for the *recommended* version, not a patched version of whatever was already there. This is what gets signed off before drafting starts.

### 3. Sequence Map
Touch-by-touch: ask or no-ask, offer used, CTA, reciprocity check passed.

### 4. Gaps and Open Questions
What's blocking a clean build, missing framework, missing stakeholder input, missing asset, stated plainly rather than papered over with an assumption.

---

## Task-Specific Questions

First, which mode is this: an audit of existing content, a lifecycle architecture, or both?

**For an audit**

1. What is in scope, what is the audit for, and who decides what happens to the content?
2. What does good look like for this content type, audience and goal, before you read what exists?
3. Is the inventory complete and checked against what is live, or sampled? How?
4. Which claims, statistics and links need verifying against a source?
5. What data can you see, and how far can you trust it?
6. Which assets have no owner?

**For lifecycle architecture**

1. What does the best-practice version of this flow look like, before you've read the client's existing build?
2. What's the entry signal for this flow, exactly, and is it one signal or several getting treated as one?
3. Whose call is it if this logic needs to change, can you implement directly, or does this route through someone else first?
4. What existing assets already fit this persona/stage, before proposing anything new?
5. What did the stakeholder explicitly rule out, and is the draft actually honoring that?
6. What's the exit condition for every branch, not just the obvious ones, and what stops someone from being in this flow forever?
7. Is the honest recommendation a fix, or a rebuild? Don't let anchoring to the existing build answer this by default.

---

## Related Skills

- **copywriting**: for drafting the actual email or page copy once the architecture and plan are set
- **marketing-emails**: for writing and auditing the emails inside automated marketing workflows
- **social**: for writing social content. Part 1 of this skill can still audit it

**Not yet covered by this skill:** keyword research and topic-cluster planning for search-led blog programs (hub-and-spoke architecture), competitor content analysis, and forum or community research (Reddit, Quora, and similar). Part 1 can audit an existing blog or site, but planning what to publish for search demand is a different muscle and deserves its own skill, or an added section here, if a client engagement calls for it.
