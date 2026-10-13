---
name: webinar-campaigns
author: Laura Farbo
description: Use when planning, building or auditing a webinar or event campaign in HubSpot, from first promotion through registration, the live event, attendee and no-show follow-up, and the replay. Covers audience segmentation, promo cadence, registration forms and branching, follow-up logic, replay assets, co-hosted and partner events, reporting limits and a QA pass. Trigger words include "webinar campaign," "webinar series," "event promotion," "promo emails," "registration form," "no-show emails," "attendee follow-up," "replay page," "recording email," "on-demand webinar," "co-hosted webinar," "event follow-up," or a request to audit a webinar flow. Assumes the audience and offer are already defined in content-strategy, and uses marketing-emails for the copy and send checks on each email. Not for rep-led sales follow-up cadences, in-person event logistics or paid media.
metadata:
  version: 1.0.0
---

# Webinar and Event Campaigns

A webinar campaign is a small system. A registration form feeds promo emails, the event feeds two follow-up paths, and the recording feeds a replay path that runs for months. If the pieces are built one at a time, they contradict each other. This skill builds and audits the whole chain so every piece knows what came before it and what comes after.

Written for sales-assisted B2B teams on HubSpot. A webinar here earns attention and a next step, and a human takes it from there when the signal is strong enough.

---

## Where this skill stops

| The work is... | Use |
|---|---|
| Deciding who the event is for, what it offers and what it may ask | content-strategy |
| The whole event chain: audiences, promo, registration, follow-up, replay | this skill |
| Writing and QA on each individual marketing email | marketing-emails |
| A rep-led cadence with calls and tasks after a high-intent signal | a sales sequence skill |
| Venue, travel, speakers and run-of-show logistics | outside this skill |

This skill decides what gets sent to whom and when. marketing-emails decides how each email is written and checked. Do not duplicate its checklist here, apply it.

---

## Step 0: Confirm before building

Answer these first. A gap here blocks the build more than any copy problem does.

1. **The event itself.** Single event, or a series? Live, on demand, or both? One session per registration or several? Dates, times and time zones.
2. **The architecture.** Audience, stage, offer and exit conditions from content-strategy. Do not infer them.
3. **The goal of the event.** Awareness, pipeline, customer education or something else? The goal decides what counts as success and which follow-up path matters most.
4. **Hosting.** Who is the webinar tool, and how does it connect to HubSpot? Confirm what the integration actually passes (see Reporting limits).
5. **Co-hosts and partners.** Is anyone else promoting, and does their list enter HubSpot by form or by upload? Both change reporting.
6. **Ownership.** Workflow logic, forms, lists and integrations usually belong to RevOps or the portal admin. Propose changes and do not imply you will edit live logic.
7. **Stakeholder limits.** What was ruled out for frequency, tone or number of sends?

---

## The anatomy of an event campaign

Build and review the chain in this order. Each phase names what it hands to the next.

| Phase | What it does | Hands off |
|---|---|---|
| 1. Registration | Form, landing page and confirmation | A registered contact with the right session data |
| 2. Promotion | Announce, build, remind | Reminder for registered contacts, more promo for the rest |
| 3. Pre-event | Confirmation and day-before and day-of reminders | Attendance |
| 4. Post-event | Attendee path and no-show path | Replay viewers, or routing to sales or nurture |
| 5. Replay | Recording page and on-demand access | A long-running path with its own exit |

Map all five before drafting any email. A flow that is clean in phase 2 and has no plan for phase 5 is unfinished.

---

## Audiences

Segment promotion by each contact's relationship to the company. A common set:

- **Previous attendees.** They know the format. Lead with what is new.
- **Customers.** They need to know why it matters to their own results, and they should not be sold to.
- **Prospects and cold contacts.** They need the problem and the reason to spend an hour.

Each audience gets its own promo copy and, where the pool allows, its own cadence. Reminder touches especially should not share identical body copy across audiences. Keep customers out of prospect-style asks, and confirm suppression for anyone in active sales conversation.

Prefer the word your client uses for segments, and use it consistently.

---

## Promotion

Every promo touch has one distinct job.

- **Announce.** What it is, who it is for, when it happens.
- **Build.** Why it is worth the time: a sharper problem statement, a speaker, a specific takeaway, a short proof point.
- **Remind.** Date, time, one reason, and a one-click path to register.

Rules that hold across audiences:

- Vary the angle between touches. Five emails that restate the same invitation read as automation.
- A registered contact leaves the promo path immediately and enters the reminder path.
- Expect response to fall across a series as the remaining pool gets smaller and colder. That decline is not proof of a copy or suppression problem, so read it against the pool before rewriting.
- Webinar registration is a low-effort ask. Do not use urgency framing meant for demo requests.
- Send business days at the recipient's local time where the tool allows it.

---

## Registration forms and branching

The form is where most event data goes wrong, so build it deliberately.

- **One event or several.** For a series, decide whether people register for individual sessions or the whole series, and what the form does with each choice.
- **Default selections shape your data.** If the form pre-selects every session, per-session registration counts mostly reflect total submissions and say little about interest in a given session. Either avoid pre-selecting, or do not use per-session counts as a demand signal.
- **Branching.** Each form choice should trigger the right workflow, confirmation and calendar invite. Test every combination, including a contact who registers for one session and later adds another.
- **Fields.** Ask only for what the next step uses. Every extra field costs registrations.
- **Confirmation page and email.** State the session, date, time zone and how to join. Offer a calendar add.
- **Consent and compliance.** Confirm the wording and footer with the client for the region.

---

## Pre-event

- Confirmation goes out immediately.
- Reminders land close to the event, usually the day before and the day of. Keep them short and make the join link impossible to miss.
- Check the join link, time zone and session name in every send.
- If the webinar tool announces itself or joins automatically through a connected note-taking or recording feature, tell the admin before a live event. Registrants can see it.

---

## Post-event: two paths

Attendance and no-show are different relationships. Build both before the event.

### Attendee path
- **Thank-you email within a day.** Thank them, give the recording or slides if you are sharing them, and offer one next step that matches how engaged they were.
- **Attendance is not high intent.** Do not write the first follow-up as if attending means they want a call. An explicit request for sales follow-up, made in the form or during the event, is the high-intent signal.
- If follow-up was explicitly requested, route to the rep path with context: which event, what they attended and what they asked for.
- If not, route into the relevant nurture. Follow-up should offer more of what they came for.

### No-show path
- **Send the replay and keep it warm.** Be short and specific about what they missed and where to watch it.
- A no-show who watches the replay is a real signal. Track it separately from live attendance.
- Do not stack the no-show email on top of other sends to the same contact on the same day.

---

## Replay and on-demand

- A replay page needs the recording, a short summary, the next step and nothing that competes with it.
- Each announcement email links to its own session's page, and every link is checked.
- Decide what the replay path does after the event: how long it runs, what removes someone from it and what happens to people who never watch. A replay flow with no end is an unmanaged flow.
- If an on-demand version sends emails automatically, add a short delay after registration so enrichment and status updates finish first. Sending in the first minutes after a contact is created can read stale data and suppress or misroute the email.

---

## Co-hosted and partner events

- **Which list is it?** Contacts that arrive by upload can be undercounted in reports built on form submissions. State this when you report on partner-driven registrations.
- **Same content, different sender.** If tracks for different partners share copy, use a placeholder for the partner name and keep one master version so edits do not drift.
- **Agree on who emails whom** and who owns the unsubscribe and compliance footer for each send.
- **Set expectations on data.** Confirm in advance what registration and attendance data the partner will receive and what you will receive.

---

## Reporting limits

Report what the data can support, and name what it cannot.

- **Registration conversion rate** settles more questions than opens and clicks. Use it when you have the data, including for judging whether suppression or copy is the problem.
- **Webinar integration granularity.** Some integrations pass only a webinar identifier and not the individual session. For a multi-session series, that means session-level registration and attendance may not be reliable. Check what your integration passes before promising session-level reports.
- **Opens are directional.** Mail privacy features inflate them.
- **Attendance and watch time** come from the webinar tool and may not sync to every contact. Spot-check before reporting.
- **Sales outcomes** such as call connects and meetings depend on rep behavior and sit outside the campaign's control. Report them separately from email metrics.

---

## Naming and organization

Pick one convention and apply it to every asset in the campaign: emails, forms, workflows, landing pages and banners. A workable pattern puts the fiscal period, the asset type, the event name, the audience and the step or session in a fixed order. Use the same order everywhere, and keep the convention in the client's project notes, not in this skill. A campaign you can search by name is a campaign you can audit later.

---

## QA checklist

Run it on every build and audit. Apply the marketing-emails checklist to each email on top of this one.

### Event and registration
- [ ] Session names, dates and time zones are identical across the form, page, emails and calendar invites
- [ ] Every form choice triggers the intended workflow, confirmation and invite
- [ ] Pre-selected form options are either removed or acknowledged in reporting
- [ ] Registration data reaches HubSpot for every route (form, upload, partner)

### Promotion
- [ ] Each audience has its own copy and each touch has a distinct job
- [ ] Registered contacts leave promo and enter reminders at once
- [ ] Customers, partners, vendors and employees are suppressed from the wrong asks
- [ ] No urgency framing meant for high-intent actions

### Event and follow-up
- [ ] Join links and the right session link work in every pre-event email
- [ ] Attendee and no-show paths both exist and are tested
- [ ] The attendee path does not treat attendance as high intent
- [ ] Sales routing, where used, carries event and request context
- [ ] No contact receives two campaign emails the same day

### Replay
- [ ] Replay pages, recordings and links work and are ungated where they should be
- [ ] On-demand sends have a delay after registration
- [ ] The replay path has an end state and an exit for every branch

### Reporting and handoff
- [ ] Reporting limits are stated, including session granularity and upload gaps
- [ ] Asset names follow the convention
- [ ] Unverified claims, links and speaker details get flagged before anything ships
- [ ] Anything that changes live logic is routed to the workflow owner

---

## Output format

### 1. Baseline vs. reality
What a good chain looks like for this event, what exists and whether the gap is a patch list or a rebuild.

### 2. Event brief
```
Event or series:
Format and dates:
Goal:
Audiences:
Registration route:
Hosting and integration:
Co-hosts and list sources:
Owners and approvals:
Limits from the stakeholder:
```

### 3. Campaign map
Phase by phase: audiences, assets, sends, timing, exits and what each phase hands to the next.

### 4. Assets and copy
Registration form and page, promo emails per audience, pre-event emails, attendee and no-show follow-ups, replay page and announcement.

### 5. QA pass
Checklist results, with failures and unconfirmed items called out.

### 6. Before it goes live
Placeholders, unverified details, links to check and decisions that route to others.

---

## Task-specific questions

1. Is this one event, a series or an evergreen on-demand webinar?
2. Does the architecture from content-strategy exist for this audience?
3. What does the webinar integration actually pass into HubSpot?
4. Does the form pre-select sessions, and what does that do to your data?
5. Do attendee and no-show follow-ups already exist, and who gets which?
6. Who else emails this contact in the same window?
7. What happens to someone who registers and never engages again?
8. Who owns the workflow, and can you change it or only propose?

---

## Related skills

- **content-strategy**: audience, stage, offer and exit conditions for the event
- **marketing-emails**: copy, send eligibility and QA for each email in the chain

**Not yet covered:** in-person event logistics, paid promotion, speaker and panel coordination, live-event moderation, post-event reporting dashboards and platforms other than HubSpot. Add these when an engagement calls for them.
