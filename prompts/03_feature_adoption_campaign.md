# Prompt 3: Feature Adoption Campaign

## Purpose
Most users activate one feature and never discover the rest. This prompt generates a 3-email drip for each underused feature — plus in-app message variants for Intercom, Appcues, or Pendo. A fully adopted user is 5x less likely to churn than a one-feature user.

## The Prompt

```
You are a SaaS email copywriter specializing in feature adoption. Write a feature adoption campaign for the following product and feature:

**Product Name:** [PRODUCT NAME]
**ICP:** [JOB TITLE] at [COMPANY SIZE] companies
**Feature name:** [FEATURE NAME]
**What it does:** [ONE SENTENCE — the job it does for the user]
**Why users don't adopt it:** [e.g., "They don't know it exists", "Setup seems complex", "They're happy with their current workflow", "They tried it once and got confused"]
**Who uses it successfully:** [Describe a power user type — role, company size, use case]
**Result a power user gets:** [SPECIFIC, MEASURABLE OUTCOME — e.g., "saves 2 hours per week", "closes deals 30% faster", "reduces support tickets by 40%"]
**Brand voice:** [formal / casual / playful / direct / expert]

---

Deliver a 3-email feature adoption sequence using the Problem → Proof → Invitation framework:

**Email 1 — The Problem**
- Send timing: Day 21 (or 7 days after activation, whichever comes first)
- Trigger condition: User has not used [FEATURE NAME] in the last 14 days
- Subject line A: [curiosity angle]
- Subject line B: [problem angle — name the pain this feature solves]
- Subject line C: [outcome angle]
- Preview text: [45-65 characters]
- Body copy: [120-180 words] — Open with the pain the feature solves. Don't mention the feature yet. End with a question or teaser that sets up Email 2.
- Primary CTA: [Something soft — not "try the feature". A resource, a tip, a question.]

**Email 2 — The Proof**
- Send timing: 3 days after Email 1
- Trigger condition: User did not use [FEATURE NAME] after Email 1
- Subject line A: [social proof angle]
- Subject line B: [specific result angle]
- Subject line C: [story angle]
- Preview text: [45-65 characters]
- Body copy: [150-200 words] — A mini case study. Real customer (or ICP-matched archetype). Specific result. Written as a short story, not a testimonial block. End with the feature named explicitly and a direct CTA.
- Primary CTA: ["Try [Feature Name]" or equivalent — direct, action-forward]

**Email 3 — The Invitation**
- Send timing: 5 days after Email 2
- Trigger condition: User still has not used [FEATURE NAME]
- Subject line A: [direct offer angle]
- Subject line B: [help angle — offer to assist]
- Subject line C: [scarcity/context angle — e.g., "this is the last time I'll mention this"]
- Preview text: [45-65 characters]
- Body copy: [100-150 words] — Short and direct. Remove the #1 friction point (link to tutorial, offer a Calendly call, provide a one-click setup path). Low pressure. High respect for their attention.
- Primary CTA: [One-click setup or calendar link]
- Exit: If user still doesn't engage after Email 3, pause the feature campaign for this feature for 60 days.

---

Also deliver:

## In-App Messages (for Intercom / Appcues / Pendo)

**Tooltip Variant**
- Trigger: User hovers near the [FEATURE NAME] button/nav item for the first time
- Headline: [10-15 words]
- Body: [25-40 words]
- CTA button: [5-8 words]

**Modal Variant**
- Trigger: User logs in for the 5th time without using [FEATURE NAME]
- Headline: [10-15 words]
- Body: [40-60 words]
- Primary button: [action-forward CTA]
- Secondary link: ["Maybe later" — always include a dismiss option]

## Repeat Instructions
Run this prompt once for each core feature you want to drive adoption of. Replace [FEATURE NAME] and its details each time. For a product with 3 features, you'll run this prompt 3 times.
```

## Variables to Fill In
- `[PRODUCT NAME]` — your SaaS product
- `[ICP]` — same as Prompts 1 and 2
- `[FEATURE NAME]` — the feature with low adoption you want to drive
- `[WHAT IT DOES]` — one sentence, user-benefit framing (not "this feature allows you to..." but "you can...")
- `[WHY USERS DON'T ADOPT IT]` — be honest; this shapes Email 1's opening. "They don't know it exists" → tease it. "Setup seems complex" → Email 3 removes friction.
- `[SPECIFIC, MEASURABLE OUTCOME]` — if you don't have data, talk to 3 power users and get a real number. Vague outcomes produce weak Email 2s.

## Tips
- The 3-email Problem → Proof → Invitation framework is based on the principle that most users need to understand WHY before they'll try something new. Email 1 sells the problem (not the feature). Email 2 sells the possibility (via proof). Email 3 sells the specific action.
- The in-app modal is often more effective than the email for this type of adoption. If you're using Intercom or Appcues, implement the modal first and only use the email sequence for users who dismiss the modal 2+ times.
- Don't run feature adoption campaigns for features users find confusing. Fix the UX first. The email will just expose the bad experience.
