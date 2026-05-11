# Copy Reference

Copy Reference is a senior-writer review skill for improving marketing and product copy before it reaches a final human editor. It gives an AI agent a structured way to check whether a draft is clear, persuasive, specific, and ready for a senior writer to review.

Use it after the first draft and before final humanisation. The skill does not try to make copy sound more natural. Its job is to strengthen the message: the promise, hook, structure, objection handling, CTA, emotional trigger, and platform fit.

Best paired with [Humaniser](https://github.com/kastrah/humaniser), which should run after Copy Reference to remove AI tells and make the final copy sound more human.

## What it helps with

- Weak hooks that do not earn attention
- CTAs that are vague, repeated, or trying to do too much
- Copy that explains features but does not make the value feel urgent
- Missing emotional triggers or buyer motivation
- Drafts that are clear but not persuasive
- Platform mismatch, especially when the same copy is reused across email, social, landing pages, SMS, and ads
- Objections that a reader will have but the draft ignores

## Recommended workflow

```text
Research → Draft → Copy Reference → Humaniser → Senior writer review → Publish
```

Run Copy Reference before Humaniser. Copy Reference adds persuasion structure, and that can reintroduce patterns that sound like AI writing. Humaniser should clean the final draft after the persuasive edits are in place.

## Installation

### Claude Code

```bash
git clone https://github.com/kastrah/copy-reference.git ~/.claude/skills/copy-reference
```

### OpenCode / Codex / other agents

Copy `SKILL.md` into your agent's skills directory, or paste the contents into your system instructions. Keep the `references/` folder beside it so the agent can load the right checklist, CTA guide, hook guide, and objection-handling notes when needed.

## Usage

Ask your agent to run Copy Reference on a draft:

```text
Run Copy Reference on this landing page copy before we send it to the senior writer.
```

Or:

```text
Review this campaign copy using Copy Reference. Strengthen the hook, CTA, objections, and emotional trigger, then give me the revised version.
```

## What the agent should return

For each review, the agent should give you:

1. A short diagnosis of what is weak and why
2. The specific reference areas used, such as hooks, CTAs, objections, platform fit, or persuasion formulas
3. A revised draft
4. Notes for the senior writer, only where judgment is still needed

The final copy should not include internal audit notes. Keep production notes in the review summary, not inside the public-facing copy.

## Included reference files

- `references/review-checklist.md` — 18-point review checklist
- `references/principles.md` — core copy principles
- `references/headline-hooks-openers.md` — hooks and openers
- `references/cta-framework.md` — CTA hierarchy and action clarity
- `references/triggers-and-motives.md` — emotional triggers and buyer motivations
- `references/persuasion-formulas.md` — structure formulas for different copy types
- `references/objection-handling.md` — finding and resolving reader objections
- `references/social-platform-guide.md` — platform-specific execution notes
- `references/index.md` — quick map of the reference system

## License

MIT
