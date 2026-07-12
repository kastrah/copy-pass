---
name: copy-pass
description: >
  Use when reviewing marketing, product, campaign, landing page, email, SMS, ad,
  or social copy before senior writer review. Strengthens persuasion, hooks, CTAs,
  objection handling, emotional triggers, platform fit, and message clarity. Run
  after drafting and before humaniser. Best paired with humaniser: https://github.com/kastrah/humaniser
version: 1.0.0
author: Kastrah
license: MIT
metadata:
  hermes:
    tags: [copywriting, persuasion, marketing, editing, senior-review, content-strategy]
    related_skills: [humaniser]
---

# copy-pass

## Overview

## Source scope

copy-pass is condensed from marketing, advertising, copywriting, argumentation, and behaviour-change books/playbooks listed in `references/index.md`. Full extracted framework notes live in `references/source-frameworks/`.

copy-pass is a pre-senior-writer review skill. Use it to make a draft more persuasive, specific, and commercially useful before a senior writer reviews it.

This skill is not a grammar pass. It is not a generic rewrite pass. It checks whether the copy gives the reader a clear reason to care, believe, and act.

The output should improve the copy while preserving the underlying strategy. Do not invent claims, offers, audiences, statistics, product features, or campaign mechanics that were not provided. If an important detail is missing, mark it as a senior-writer question instead of filling the gap with a guess.

## Correct workflow

Run this sequence:

```text
Research → Draft → copy-pass → humaniser → Senior writer review → Publish
```

copy-pass must run before humaniser.

Why: copy-pass may add structure, urgency, objection handling, or CTA pressure. Those edits can introduce patterns that sound like AI writing. humaniser should run after the persuasion work so the final draft sounds natural.

## When to use this skill

Use copy-pass when the user asks to:

- review copy before a senior writer sees it
- improve landing page copy
- sharpen a campaign concept or launch message
- create or evaluate email, SMS, WhatsApp, ad, or social copy
- strengthen hooks, CTAs, benefits, objections, or positioning
- turn a draft from clear-but-flat into something more persuasive
- check whether copy is ready for publication

Do not use it for:

- purely factual documentation
- legal, medical, or compliance review
- final AI-tell cleanup after all edits are done; use humaniser for that
- inventing campaign strategy from scratch without a brief

## Inputs to collect before reviewing

Read the draft and identify:

1. Audience: who is this for?
2. Desired action: what should the reader do next?
3. Context: where will this appear?
4. Offer or promise: what value is being made concrete?
5. Constraints: claims, tone, product details, legal or medical boundaries
6. Stage of awareness: unaware, problem-aware, solution-aware, product-aware, or ready to act

If those details are in the draft or surrounding context, proceed. Ask only if the missing information changes the review materially.

## Review process

### 1. Run the 18-point checklist

Open `references/review-checklist.md` first. Use it to check the draft across structure, persuasion, voice, proof, CTA, objection handling, and platform fit.

Return only the failures that matter. Do not pad the review with every minor issue.

### 2. Diagnose the main weakness

Name the problem before rewriting. Common diagnoses:

- The hook is descriptive, not motivating.
- The copy explains the feature but does not show why it matters now.
- The CTA asks for too many actions at once.
- The copy makes a claim without proof or context.
- The emotional trigger is missing or too abstract.
- The objection is obvious but unanswered.
- The platform format is wrong for how the reader will encounter it.

### 3. Load the right reference file

Do not load every reference by default. Pick based on the failure:

| Problem | Reference file |
|---|---|
| Weak or generic hook | `references/headline-hooks-openers.md` |
| Weak CTA or too many CTAs | `references/cta-framework.md` |
| No emotional pull | `references/triggers-and-motives.md` |
| Poor structure | `references/persuasion-formulas.md` |
| Reader doubts unanswered | `references/objection-handling.md` |
| Wrong channel execution | `references/social-platform-guide.md` |
| Copy feels generally flat | `references/principles.md` |

### 4. Rewrite with restraint

Improve the copy without making it sound over-crafted.

Prefer:

- concrete benefits over abstract claims
- one primary CTA over multiple competing CTAs
- specific context over generic urgency
- direct sentences over rhetorical throat-clearing
- proof where a claim needs support
- reader language over internal product language

Avoid:

- invented statistics
- fake testimonials
- exaggerated urgency
- clever hooks that bury the point
- generic taglines
- repeating the same CTA in every section
- adding claims the business cannot defend

### 5. Prepare the senior-writer handoff

After rewriting, include a short note for the senior writer:

- what was changed
- which parts still need human judgment
- any claim that needs verification
- any strategic decision that was not clear from the brief

Do not put these notes inside the final public copy.

## Output format

Return:

```text
Diagnosis:
- [The 1-3 most important issues]

References used:
- [Specific reference files or frameworks]

Revised copy:
[Clean revised draft]

Senior-writer notes:
- [Only if needed]
```

For small assets like SMS, ads, banners, or flyers, use a fielded structure:

```text
Angle:
Headline:
Body:
Primary CTA:
Secondary CTA:
Footer / compliance note:
```

For multiple variations, use a table if the platform supports it. If the delivery channel does not support tables, use clean labeled groups.

## Platform guidance

### Landing pages

Check that the page has:

- one clear promise above the fold
- enough proof to make the claim believable
- objection handling before the main conversion point
- a CTA that matches the reader's readiness
- no generic hero section that could belong to any company

### Email

Check that the subject line earns the open, the first line earns the next sentence, and the CTA gives one next step. Avoid making the email do too many jobs.

### SMS and WhatsApp

Keep the message short, concrete, and action-led. The reader should understand the value and next step without scrolling.

### Social posts

Do not force a landing-page structure into a social post. Lead with the tension, observation, or useful idea. Put the CTA where it feels earned.

### Ads and banners

Prioritise clarity. Use one idea, one audience, one action. Remove secondary arguments unless they directly support the click or walk-in behavior.

## Quality bar before humaniser

Before handing off to humaniser, confirm:

- The reader knows why this matters.
- The reader knows what to do next.
- The CTA hierarchy is clear.
- The main objection has been addressed.
- The copy does not depend on vague claims.
- The copy is persuasive without being inflated.
- No internal notes are embedded in the public-facing copy.

## Common pitfalls

1. Running humaniser first. That makes the draft cleaner before the persuasion work, then copy-pass can reintroduce AI-sounding patterns.
2. Treating every draft like a landing page. A WhatsApp message, SMS, social post, and banner need different pressure and structure.
3. Adding persuasion by adding more words. Often the stronger edit is shorter.
4. Inventing proof. If the claim needs evidence and none is available, flag it.
5. Overwriting the brand voice with copywriter rhythm. The point is to make the copy more effective, not more theatrical.
6. Leaving three CTAs competing for attention. Decide the primary action.
7. Shipping the audit notes as part of the copy. The reader should only see the polished message.

## Verification checklist

Before returning the final answer:

- [ ] I ran the review checklist.
- [ ] I loaded only the reference files needed for the actual weaknesses.
- [ ] I fixed the highest-impact persuasion problems.
- [ ] I preserved the brief and did not invent unsupported claims.
- [ ] I made the CTA hierarchy clear.
- [ ] I kept internal notes out of the public copy.
- [ ] I stated that humaniser should run after this pass.

## Pair with humaniser

copy-pass strengthens the message. humaniser cleans the voice.

After this skill improves the hook, structure, CTA, and persuasion logic, run [humaniser](https://github.com/kastrah/humaniser) to remove AI tells, smooth the rhythm, and make the final draft sound like a person wrote it.
