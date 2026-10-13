---
name: marketing-emails
author: Laura Farbo
description: Use when writing or auditing automated marketing emails inside a HubSpot marketing workflow, such as nurtures, evergreen flows, webinar and event follow-ups, and re-engagement. Covers subject lines, copy, cadence, send eligibility, enrollment and exit logic, and a standing QA pass. Trigger words include "marketing email," "nurture emails," "workflow emails," "email cadence," "evergreen emails," "webinar follow-up emails," "re-engagement emails," "subject line," "audit this workflow," "QA this nurture," "send eligibility," "suppression," or a request to draft or fix specific emails in an automated flow. Assumes the architecture (entry signal, persona, stage, offer, exit condition) already exists from content-strategy, and hands back if it does not. Not for rep-led sales sequences (use inbound-sales-sequences), cold outbound, or one-off newsletters and landing pages (use copywriting).
metadata:
  version: 1.0.0
---

# Marketing Emails (Automated Workflows)

You write and audit the emails inside automated marketing flows. Nobody is sending these by hand. A workflow enrolls a contact, waits, branches and sends, and the marketing email has to do its job without a person nudging it. That makes eligibility, exits and cadence as much a part of the craft as the copy.

This skill covers the marketing side only. It runs alongside any rep-led sales sequence and never replaces one.

---

## Where this skill stops

| The work is... | Use |
|---|---|
| Deciding what the flow is for, who it is for, what it may ask | content-strategy |
| Automated marketing emails in a workflow | this skill |
| A rep-led cadence with calls, tasks and LinkedIn touches | inbound-sales-sequences |
| A landing page, a one-off send, a single social post | copywriting or the matching skill |

If a request mixes these, split it and say which part each skill owns. Do not let sales-sequence mechanics (task titles, personal-mailbox sends, auto-unenroll on reply) leak into a marketing workflow, because those concepts do not apply the same way here.

---

## Step 0: Confirm what exists before writing

Answer these before any copy. A gap here is the real blocker, not the wording.

1. **Architecture brief.** Do the five elements exist (entry signal, persona, stage, offer, exit condition)? Pull them from content-strategy. Do not infer them from the request. If they are missing, hand back.
2. **New build or audit.** Say which one you are doing. An audit of a live flow starts with the QA checklist and reports findings before proposing rewrites.
3. **Ownership.** Workflow logic, enrollment filters, suppression lists and contact status rules usually belong to RevOps or the client's admin. Propose changes, and do not imply you will edit live logic.
4. **Constraints from the stakeholder.** What did they rule out for tone or frequency ("not pushy," "not weekly")? These are hard limits on everything you draft.
5. **What runs in parallel.** Which other workflows and sales sequences can touch the same contact in the same window? Cadence is judged across all of them, not per flow.

---

## Baseline: what a good marketing flow does

Sketch this before you read the existing build, so you measure against principle and not against whatever is already live.

- **Qualification accumulates.** One open or one click is a first sign of life, not readiness. Do not let a single signal do both jobs.
- **Every branch has an exit.** The contact who neither qualifies nor disqualifies still needs somewhere to go. Name the destination for each branch, including the quiet end of the flow.
- **Handoffs carry context.** If a flow routes someone to sales, the receiving team sees what content triggered it, not only a status change.
- **Evergreen means the mechanism runs, not that a contact cycles forever.** A flow with no end state for the individual contact is unmanaged.
- **The flow earns each send.** If a touch has no reason to exist, cut it.

---

## Send eligibility

Check who can actually receive the email before judging the copy.

- **Marketing contact status.** Marketing email goes to marketing contacts. Contact status also affects cost, so confirm how contacts get that status and whether contacts entering this flow should hold it. Do not assume the default is right.
- **Suppression.** Confirm which suppression applies before launch: unsubscribed, hard-bounced, unengaged, internal and employee domains, test records, existing customers where the flow is not meant for them, and anyone in active sales conversation if the client wants them held out.
- **Unengaged contacts.** Find out how the account treats them and whether this flow should reach them or skip them.
- **Consent and compliance.** The footer, unsubscribe and any regional requirements are set per client and region. Flag what you cannot confirm.

---

## Flow mechanics

Confirm each of these with the person who owns the workflow. Names of settings change between HubSpot releases, so check the live UI before relying on a label.

- **Enrollment trigger.** One event or several treated as one? Be exact.
- **Re-enrollment.** Can a contact enter twice? If yes, what stops them from receiving the same series again?
- **Goal and exit criteria.** What removes someone mid-flow (a demo request, a reply to sales, becoming a customer, an unsubscribe)? A flow without these keeps emailing people it should have released.
- **Delays and send timing.** Business days, recipient time zone where the tool supports it, no weekend sends for B2B unless the client says otherwise.
- **Branches.** Each branch has its own exit, and the default branch has copy that works for people who matched nothing.
- **Overlap.** Map this flow against every other workflow and against any sales sequence for the same audience. Two flows firing on one contact the same day reads as a mistake.

---

## Email craft

### Subject line and preview text
- Clear beats clever, and specific beats vague.
- Aim for roughly 40 to 60 characters, then check how it actually renders. Personalization tokens and mobile clients cut lines that look fine in the editor.
- Preview text extends the subject and does not repeat it. Roughly 90 to 140 characters.
- Write it so it reads like a person sent it, not a campaign.

### Structure
1. **Hook.** The first line earns the rest.
2. **Context.** Why this matters to this persona, in their terms.
3. **Value.** The useful part, which should stand on its own.
4. **CTA.** One clear next step.
5. **Sign-off.** Human, from a named sender where the client allows it.

### Format and length
- Short paragraphs, white space, sparing bold, mobile first.
- About 50 to 125 words for a short check-in, 150 to 300 for an educational touch, up to 500 for a story or case study.
- Always include a plain-text version and a working unsubscribe.
- Every personalization token has a fallback, and the fallback reads naturally.

### Links
- Link to ungated pages whenever the contact already has the gated asset.
- Every link is live, and UTM or campaign tagging follows the client's convention.
- Never fake urgency for contacts who arrived through a content download.

---

## Reciprocity, enforced per email

The rules live in content-strategy (Step 3). Apply them to every drafted email, not just the sequence as a whole:

- Give before asking.
- Calendar links on direct asks, and only on direct asks.
- Vary CTA phrasing across the cadence.
- Make every no-ask touch deliberate.
- Treat a content download as a first sign of life, not high intent.

Point to that file instead of restating it, so the two skills cannot drift apart.

---

## Cadence

- Set it from the brief and the stakeholder's limits, not from a template length.
- Evergreen and stay-top-of-mind flows run low frequency, usually every two weeks to monthly. Restraint is the skill.
- Event flows are tight around the event: before, right after, and a short follow-up window.
- Re-engagement runs short, with an honest check-in, what has changed, and a last-chance framing. Confirm the inactivity threshold with the client and do not assume one.
- Fewer, sharper emails beat a longer flow padded to a target length.

---

## QA checklist

A standing pass. Run it on every draft and every audit, and report results before calling anything done.

### Eligibility
- [ ] Contact status for this audience is confirmed, not assumed
- [ ] Suppression lists are named and applied (unsubscribed, bounced, unengaged, internal, test, customers)
- [ ] Compliance footer and unsubscribe are present and correct for the region

### Flow logic
- [ ] Enrollment trigger is one exact event, matching the brief
- [ ] Re-enrollment is set on purpose
- [ ] Goal and exit criteria release people who should stop receiving emails
- [ ] Every branch, including the default and the quiet end, has a defined exit
- [ ] Any sales handoff carries the triggering content and date
- [ ] Overlap with other workflows and sales sequences is mapped

### Each email
- [ ] Internal email name follows the client's naming convention and is set on every email
- [ ] Subject line renders in full and is not cut off or shortened past its point
- [ ] Preview text extends the subject
- [ ] One job and one primary CTA
- [ ] Calendar link on direct asks only
- [ ] Personalization tokens have natural fallbacks
- [ ] All links are live, ungated where they should be, and tagged
- [ ] Plain-text version exists
- [ ] Copy follows the project's voice rules

### Across the sequence
- [ ] No two emails land on the same contact the same day, across all flows
- [ ] CTA phrasing varies when you scan all of them together
- [ ] No-ask touches each have a reason to exist
- [ ] Nothing contradicts a stakeholder constraint

### Before launch
- [ ] Test sends reviewed on mobile and desktop
- [ ] Test records used, and removed from real lists afterwards
- [ ] Anything unverified (statistics, quotes, links) is flagged, not shipped

---

## Auditing a live flow

1. Run the checklist first and list findings before proposing any rewrite.
2. Sort findings by impact: **wrong audience or wrong send** (fix first), **logic gaps** (missing exits, re-enrollment), then **polish** (naming, subject lines).
3. Say plainly whether the gap is a patch list or a rebuild. Do not default to patching because the build already exists.
4. Route anything that changes live logic to whoever owns it.

---

## Measurement

- Clicks and replies carry the signal. Treat opens as directional only, since mail privacy features inflate them.
- Watch unsubscribe and bounce rates per email, because a spike points at one touch.
- Where the client scores or qualifies on engagement, prefer a click-based trigger over an open-based one.
- Review a live flow at 30 to 60 days. Cut or rewrite touches that earn nothing.

---

## Output format

### 1. Baseline vs. reality
The baseline stated plainly, what exists, and whether the gap is a patch list or a rebuild.

### 2. Sequence overview
```
Flow name:
Entry signal:
Audience / persona:
Goal:
Length and timing:
Exit and goal criteria:
Suppression and contact status:
Runs alongside:
```

### 3. Per email
```
Email [#]: [Purpose]
Internal name:
Send: [timing]
From:
Subject:
Preview:
Body:
CTA: [text] -> [destination]
Ask or no-ask:
Reciprocity check: [pass / what failed]
```

### 4. QA pass
Checklist results, with anything failed or unconfirmed called out.

### 5. Before it goes live
Placeholders, unverified claims, links to check, and decisions that route to the workflow owner.

---

## Task-specific questions

1. Does the architecture brief exist, or does this go to content-strategy first?
2. New build or audit of a live flow?
3. What is the exact entry signal, and is it one event or several?
4. Who owns workflow logic, and can you change it or only propose?
5. What did the stakeholder rule out for tone or frequency?
6. What else can email this contact in the same window?
7. What happens to a contact who never qualifies and never opts out?

---

## Related skills

- **content-strategy**: the architecture brief and reciprocity rules this skill depends on
- **inbound-sales-sequences**: the rep-led sales cadence that runs alongside marketing flows
- **copywriting**: landing pages and one-off copy the emails link to

**Not yet covered:** transactional and billing email, product-led onboarding and usage emails, NPS, newsletters and broadcast sends, platforms other than HubSpot, and A/B test design. Add any of these when an engagement calls for it, and not before.
