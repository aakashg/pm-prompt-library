# Onboarding Flow Designer

**Category:** Execution
**Use when:** You need to design or improve a user onboarding flow.

## The Prompt

```
You are a growth PM designing an onboarding flow.

I'll describe the product and target user. Design the onboarding experience:

**Activation Metric**
- Define the moment the user "gets it" — the aha moment
- Metric: [specific action that indicates activation]
- Target: [% of new users who should reach this within X days]

**Onboarding Flow**
For each step:
| Step | Screen/Action | Purpose | User Effort | Skip Option? |
|------|--------------|---------|-------------|-------------|

**Step Details**
For each step:
- What the user sees
- What information we're collecting (and why we need it NOW vs later)
- What the user gets in return (value exchange)
- Estimated drop-off risk (high/medium/low)

**Progressive Disclosure**
- What do we show on day 1?
- What do we introduce on day 2-3?
- What waits until the user is activated?

**Empty States**
- What does the product look like before the user has any data?
- How do we make empty states useful instead of dead ends?

**Friction Audit**
- Every point where we ask the user to do work
- For each: is this essential? Can it be deferred? Can we pre-fill it?

**Fallback Paths**
- What if the user drops off at step 2?
- Re-engagement strategy: email, push, in-app nudge
- Timing of each re-engagement touchpoint

**Measurement Plan**
- Funnel metrics for each step (conversion rate)
- Time-to-complete for the full flow
- Cohort comparison: users who complete onboarding vs those who don't

Rules:
- Every step must deliver value, not just collect information
- The fastest path to the aha moment wins. Cut everything else.
- Don't ask questions you can infer from behavior
- Mobile and desktop flows may need to differ
- New users are impatient. You have 60 seconds of goodwill.

Product: [DESCRIBE YOUR PRODUCT]
Target user: [WHO IS SIGNING UP]
Current activation rate: [IF KNOWN]
Current onboarding: [DESCRIBE WHAT EXISTS TODAY, IF ANYTHING]
```

## Tips for Better Results

- The more specific context you provide, the better the output
- Paste real data rather than describing it abstractly
- Iterate on the output — use it as a starting point, not a final answer


---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
