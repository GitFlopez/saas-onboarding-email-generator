# Prompt 1: User Journey Map & Activation Blueprint

## Purpose
Before writing a single email, you need to know: who is the user, what does success look like for them in week 1, and where do they fall off? This prompt builds the strategic foundation for your entire onboarding system.

## The Prompt

```
You are a SaaS growth strategist with expertise in user onboarding and trial-to-paid conversion. I need you to build a User Journey Map and Activation Blueprint for my SaaS product.

Here is my product information:

**Product Name:** [PRODUCT NAME]
**One-line description:** [WHAT THE PRODUCT DOES IN ONE SENTENCE]
**ICP (Ideal Customer Profile):**
- Job title: [e.g., "Operations Manager", "Freelance Designer", "Engineering Lead"]
- Company size: [e.g., "solo", "2-10", "11-50", "51-200", "201-1000"]
- Primary pain point: [THE PROBLEM THEY HAVE BEFORE FINDING YOUR PRODUCT]
**Pricing model:** [free trial / freemium / paid only — with trial length if applicable]
**Moment of value ("aha moment"):** [THE SPECIFIC ACTION THAT SIGNALS A USER "GETS IT" — e.g., "first report generated", "first team member invited and accepted", "first automated workflow triggered"]
**3 core features:**
1. [Feature name]: [One sentence on what it does]
2. [Feature name]: [One sentence on what it does]
3. [Feature name]: [One sentence on what it does]
**Brand voice:** [formal / casual / playful / direct / expert]

---

Please deliver:

## 1. ICP Behavioral Profile
- What does this user do in the first 5 minutes after signup? (realistic, not ideal)
- What do they expect to see vs. what they actually find?
- What is their #1 question at the end of day 1?
- What external pressure (deadline, boss, client) is pushing them to solve this problem?

## 2. Activation Milestone Map (Day 0 → Day 30)
Create a timeline with these columns: Day | Milestone | What the User Does | What Success Looks Like | Churn Risk Signal

Include milestones at:
- Day 0: Signup + first login
- Day 1: First meaningful action
- Day 3: Return visit (or first churn signal)
- Day 7: Weekly habit forming (or abandonment)
- Day 14: Trial midpoint assessment
- Day 21: Decision window (renew or not)
- Day 30: Conversion or churn

## 3. Moment of Value Definition
- Define the "aha moment" in behavioral terms (what the user clicks/does, not what they feel)
- List 3 leading indicators that predict a user will reach the aha moment
- List 3 warning signs that a user is heading toward churn before reaching it

## 4. Drop-off Risk Points
Identify the 3 highest-risk drop-off moments and for each:
- When it happens (day/context)
- Why users drop off (cognitive load, missing feature, confusion, expectation mismatch)
- The email or in-app intervention that prevents it

## 5. Email Cadence Recommendation
Provide a send schedule for the 14-day welcome sequence:
- Which emails are time-based (send on Day X regardless of behavior)?
- Which emails are behavior-triggered (send when user does/doesn't do X)?
- What is the maximum email frequency to avoid unsubscribes in this ICP's inbox?
- Recommended platform note (Customer.io for behavior triggers / Mailchimp for time-based / etc.)
```

## Variables to Fill In
- `[PRODUCT NAME]` — your SaaS product name
- `[WHAT THE PRODUCT DOES IN ONE SENTENCE]` — e.g., "TaskFlow Pro helps project managers track deliverables across distributed teams without weekly status meetings"
- `[ICP job title, company size, pain point]` — be specific; "SMB owner" is worse than "Operations Manager at a 10-50 person agency"
- `[MOMENT OF VALUE]` — the single action that separates retained users from churned users; if you don't know it, your #1 priority is to find out (look at your retained cohort vs. churned cohort in your analytics)
- `[3 core features]` — the ones you most want users to adopt, not the full feature list
- `[BRAND VOICE]` — this flows into all 3 subsequent prompts

## Tips
- The more specific your ICP, the better the output. "Marketing director at a 20-person SaaS company" is 10x more useful than "small business owner."
- If you have real churn data (surveys, cancellation reasons), paste 2-3 verbatim quotes into the prompt — the AI will use them to sharpen the drop-off analysis.
- Run Prompt 1 before any other prompt. The moment of value definition and cadence recommendation directly inform Prompts 2-4.
