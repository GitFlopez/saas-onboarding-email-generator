# Example Output — Prompt 1: User Journey Map & Activation Blueprint
## Product: TaskFlow Pro

**Inputs used:**
- Product: TaskFlow Pro — project management SaaS that eliminates weekly status meetings by making project health visible in real time
- ICP: Operations Manager at 10-50 person agencies and consulting firms
- Pain point: Endless status meetings and no single source of truth for project health
- Pricing: 14-day free trial, then $79/month (up to 10 users)
- Moment of value: First automated status report generated and shared with a client
- Core features: (1) Live project dashboards, (2) Automated weekly status reports, (3) Client portal with controlled access
- Brand voice: Direct, confident, no fluff

---

## 1. ICP Behavioral Profile

**What they do in the first 5 minutes after signup:**
They click around looking for an import option. They want to bring in their existing Asana/Monday/Trello projects. When they can't find it immediately, half of them leave the setup wizard and start poking at the dashboard. The other half fill out the "Add your first project" form with a real current project — this group is 3x more likely to reach the aha moment.

**What they expect vs. what they find:**
They expect to see a dashboard full of their existing data (it's empty). They expect a 30-minute setup (actual full setup is 45-60 minutes for a real project). They're pleasantly surprised by the client portal — they didn't know that was in the product.

**Their #1 question at end of Day 1:**
"Is this actually going to replace my Monday meetings, or is it just another thing I have to maintain?"

**External pressure driving urgency:**
A client just complained about communication gaps, or the ops manager's boss has asked for a project status report for the third time this week and they're still pulling it together manually.

---

## 2. Activation Milestone Map (Day 0 → Day 30)

| Day | Milestone | What the User Does | What Success Looks Like | Churn Risk Signal |
|---|---|---|---|---|
| 0 | Signup + first login | Creates account, sees empty dashboard | Adds first project within 10 minutes | Leaves setup wizard without adding a project |
| 1 | First project active | Adds tasks, assigns team members | At least 5 tasks added, 2 team members assigned | Only 1-2 tasks added, no team members |
| 3 | Return visit | Logs back in to check/update tasks | Project has been updated since Day 1 | No login in 48 hours |
| 7 | **Aha moment** | Generates first automated status report and shares with client | Client portal accessed by at least 1 external viewer | Report generated but not shared; or not generated at all |
| 10 | Habit forming | Checks dashboard as first action on Monday morning | Weekly login cadence established | Logged in fewer than 3 times total |
| 14 | Trial midpoint | Assesses whether to continue | Has used all 3 core features at least once | Still only using 1 feature; asking "how do I export data?" |
| 21 | Decision window | Evaluates upgrade vs. cancel | Has had at least 1 positive client interaction via portal | No client portal activity; negative reply to any email |
| 30 | Conversion or churn | Enters payment method OR cancels | Subscribed, team members active, >2 reports generated | Cancelled; or trial expired with no action |

---

## 3. Moment of Value Definition

**Behavioral definition of the aha moment:**
User generates a status report (via Automated Reports > Generate), views the preview, and clicks "Share with client" — resulting in at least 1 client portal view within 24 hours.

**3 leading indicators a user will reach the aha moment:**
1. Added a real project (not "Test Project") with 5+ tasks by Day 1
2. Invited at least 2 team members (not just themselves) by Day 3
3. Viewed the "Automated Reports" feature within the first 5 days (even if they haven't used it yet)

**3 warning signs heading toward churn:**
1. Only one project with fewer than 3 tasks after 48 hours — they're evaluating, not implementing
2. No return login after Day 1 — common precursor to abandonment; email intervention must go out by Day 2
3. Used the CSV export feature on Day 5-7 — they're extracting data to bring elsewhere, not committing

---

## 4. Drop-off Risk Points

**Risk Point 1: Empty dashboard at first login (Day 0)**
- Why: Cognitive load. There's no data, no context, no obvious first step.
- Intervention: In-app onboarding checklist (3 steps: Add project → Invite team → Generate first report). Make Step 1 a single-click to a pre-filled "Add Project" form with sample data to show what it looks like when populated.

**Risk Point 2: First-time report generation (Day 5-7)**
- Why: The report setup has 6 fields. Users open it, see the options, and close it because they're not sure what to put. They don't come back.
- Intervention: Email on Day 5 (Aha Moment Push) that shows the exact 3 fields that matter and says "leave the rest at defaults." In-app tooltip on the report builder confirming this.

**Risk Point 3: Client sharing hesitation (Day 7-10)**
- Why: Users aren't sure what the client will see. They're afraid the portal looks unprofessional or exposes internal notes.
- Intervention: Add a "Preview as client" button. Email on Day 8 showing a screenshot of what a client sees. This single change removes 60% of the sharing hesitation.

---

## 5. Email Cadence Recommendation

| Email | Timing Type | Send Condition | Day |
|---|---|---|---|
| Welcome | Behavior-triggered | Immediately on signup | Day 0 |
| Setup Check | Time-based | 24 hours after signup | Day 1 |
| Value Proof | Time-based | 72 hours after signup | Day 3 |
| Aha Moment Push | Behavior-triggered | Day 5, ONLY if no report generated | Day 5 |
| Power User Move | Behavior-triggered | Day 7, ONLY if report has been shared | Day 7 |
| Midpoint Check | Time-based | Day 10 | Day 10 |
| Conversion Push | Time-based | Day 13 (1 day before trial ends) | Day 13 |

**Maximum frequency:** No more than 1 email every 2 days. Operations Managers have high-volume inboxes. More than that and they'll filter or unsubscribe.

**Platform recommendation:** Customer.io for this sequence — it's the only affordable platform with the behavioral branching needed for Emails 4 and 5 (send if/don't send if based on product event). Mailchimp can handle the time-based emails only.
