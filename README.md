# marketing-content-hub

A growing set of Claude skills for B2B lifecycle marketing, built from real client work in HubSpot and shared so you can use them, adapt them and make them your own.

Each skill is a plain `SKILL.md` that tells Claude how to do one job well. They are written for sales-assisted B2B teams, where marketing automation warms people up and a human takes it from there.

## What's in here

| # | Skill | Use it when | Version |
|---|---|---|---|
| 1 | [Auditing Your Content Strategy](./1.%20Auditing%20Your%20Content%20Strategy) (`content-strategy`) | You're planning or auditing a nurture, evergreen flow, webinar follow-up or re-engagement flow, and need to decide what it's for, who it's for and what it can ask | 1.1.1 |
| 2 | [Writing Marketing Emails](./2.%20Writing%20Marketing%20Emails) (`marketing-emails`) | You're writing or auditing the emails inside an automated HubSpot workflow, including send eligibility, exits, cadence and a QA pass | 1.0.0 |

More are coming and I'll add them to this table as they're built.

## How the skills fit together

Start with strategy and move to the emails.

1. **content-strategy** sets the architecture: entry signal, persona, stage, offer and exit condition, plus the reciprocity rules.
2. **marketing-emails** takes that architecture and writes or audits the emails, and hands the work back to content-strategy if the architecture isn't there yet.

Each skill says where it stops and which skill owns the next job, so you can use one on its own or both together.

## How to use a skill

Every folder has two things: a `.skill` file and an unpacked folder with the `SKILL.md` inside.

**In Claude:** add the `.skill` file as a skill and start a chat with something like "audit this nurture" or "QA this workflow". The skill's description tells Claude when to switch it on.

**In Claude Code:** unzip the `.skill` file, or copy the unpacked skill folder, into your skills directory (`~/.claude/skills/` for all projects, or `.claude/skills/` inside one project).

**Anywhere else:** open the `SKILL.md`, read it and paste it into a chat or project as instructions. It's just text.

## Make it yours

These skills are opinionated and they assume HubSpot. A few things to change before you rely on them:

- **Naming conventions.** Swap in your own email and template naming.
- **Voice rules.** Add your own tone and copy rules, since these skills defer to whatever the project says.
- **Platform.** The HubSpot mechanics are written for HubSpot, and setting names change between releases, so check labels in your live portal.
- **Anything marked "not yet covered."** Each skill lists what it leaves out on purpose, such as transactional email and A/B test design, so you can see what was cut and what was forgotten.

Fork the repo and edit the files, or copy a skill into your own library and rename it.

## How the repo is organized

```
marketing-content-hub/
  1. Auditing Your Content Strategy/
    content-strategy.skill
  2. Writing Marketing Emails/
    marketing-emails.skill
    marketing-emails/SKILL.md
```

New skills get the next number and their own folder, in the order they're built.

## Feedback

If something reads wrong or breaks in your setup, open an issue. If you've adapted a skill for a different platform or team, I'd love to hear how it went.

## Author and license

Built by [Laura Farbo](https://github.com/lauradfarbo). Released under the [MIT License](./LICENSE), so use it, change it and share it.
