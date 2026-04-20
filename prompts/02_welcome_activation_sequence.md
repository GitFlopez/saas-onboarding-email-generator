# Prompt 2: Welcome & Activation Sequence (Days 0–14)

## Purpose
A 7-email sequence covering the critical first 14 days. Includes behavioral branching: activated users (reached the aha moment) get a different path than stuck users (haven't reached it yet). Every email has 3 subject line variants for A/B testing.

## The Prompt

```
You are an expert SaaS email copywriter. Write a complete 7-email welcome and activation sequence for the following product:

**Product Name:** [PRODUCT NAME]
**ICP:** [JOB TITLE] at [COMPANY SIZE] companies dealing with [PAIN POINT]
**Moment of value (aha moment):** [THE SPECIFIC ACTION FROM PROMPT 1]
**Brand voice:** [formal / casual / playful / direct / expert]
**Trial length:** [NUMBER OF DAYS or "no trial — paid from signup"]
**Pricing:** [PRICE POINT — e.g., "$49/month", "$99/year"]

---

Write all 7 emails with the following structure for each:

**Email [N] — [Email Name]**
- Send timing: [Day X / Triggered by: behavior]
- Trigger condition: [What causes this email to send — e.g., "User signed up but hasn't completed Step 1 of setup"]
- Skip condition: [What behavior skips this email — e.g., "User has already completed the aha moment action"]
- Subject line A: [subject]
- Subject line B: [subject]
- Subject line C: [subject]
- Preview text: [45-65 characters]
- Body copy: [Full email body — 150-250 words, first-person from the founder or a named team member, NOT "the team at [product]"]
- Primary CTA: [button text + destination]
- Secondary CTA (optional): [link text + destination]

---

The 7 emails are:

1. **Instant Welcome** (Day 0, triggered by signup) — Warm welcome, set expectations, one specific action to take in the next 10 minutes. NOT a feature dump.

2. **The Setup Check** (Day 1, time-based) — Two paths: if they completed the Day 0 action, acknowledge it and point to the next step. If they didn't, re-invite gently with reduced friction (offer a 5-minute path, not the full setup).

3. **The Value Proof** (Day 3, time-based) — Show social proof specific to their ICP. A short case study or stat from someone in the same role who got a specific result. CTA: the aha moment action.

4. **The Aha Moment Push** (Day 5, behavior-triggered) — Only sends to users who HAVE NOT reached the aha moment yet. Direct, short, removes the #1 objection to completing the action.

5. **The Power User Move** (Day 7, behavior-triggered) — Only sends to users who HAVE reached the aha moment. Introduces Feature 2 or Feature 3 — the one that deepens engagement and makes switching harder.

6. **The Midpoint Check** (Day 10, time-based) — Honest email from the founder. "You're 10 days in. Here's what users who get results do differently." Includes a 3-item checklist. Low-pressure, high-value.

7. **The Conversion Push** (Day 13, time-based — for trial users) or **The Commitment Email** (Day 13, for freemium) — For trial: urgency without desperation. Present the ROI case. For freemium: present the upgrade benefit specific to their current usage pattern.

---

After the 7 emails, provide:

## Branching Logic Summary
A simple table showing: User Behavior → What Triggers → What Gets Skipped → What Sends Next

## Subject Line Testing Notes
For each email, note which subject line variant tests which hypothesis (curiosity vs. benefit vs. social proof) so the user knows what they're actually testing.

## Platform Implementation Notes
Brief notes on implementing this sequence in:
- Customer.io (behavior triggers)
- Mailchimp (time-based only)
- HubSpot (workflow builder)
- Intercom (series + conditions)
```

## Variables to Fill In
- `[PRODUCT NAME]` — from Prompt 1
- `[JOB TITLE / COMPANY SIZE / PAIN POINT]` — from your ICP (Prompt 1 output)
- `[MOMENT OF VALUE]` — from Prompt 1 output
- `[BRAND VOICE]` — same as Prompt 1
- `[TRIAL LENGTH]` — if no trial, change Email 7 to a "commitment/upgrade" email for freemium users
- `[PRICE POINT]` — needed for Email 7's ROI case

## Tips
- Read the Prompt 1 output before running this prompt. Paste the "Moment of Value Definition" section directly into this prompt.
- The most important email is #4 (the Aha Moment Push). If users aren't reaching the moment of value, this is the email that fixes it. Make it as specific and friction-reducing as possible.
- For Email 7 (conversion), the ROI case wins over urgency. "You'll save 3 hours a week" beats "Your trial ends in 24 hours" for most B2B SaaS audiences.
- Email bodies should read like they were written by a person, not a marketing department. First-person voice, admit trade-offs, avoid corporate speak.
