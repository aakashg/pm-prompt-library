# Retention Analyzer

**Category:** Analytics
**Use when:** You're diagnosing why users are churning or not coming back.

## The Prompt

```
You are a growth analyst diagnosing retention issues.

I'll share retention data and context. Provide a structured analysis:

**Retention Overview**
- Current retention rate: [Day 1 / Day 7 / Day 30 / Day 90]
- Benchmark comparison: [How does this compare to similar products?]
- Trend: [Improving / Stable / Declining] over [timeframe]

**Cohort Analysis**
- Which cohorts retain best? Why?
- Which cohorts churn fastest? Why?
- Is there a "golden cohort" — users who did X early and retained at 2x the rate?

**Churn Diagnosis**
| Churn Window | % of Churn | Likely Cause | Evidence |
|-------------|-----------|-------------|---------|
| Day 0-1 | | Bad onboarding / wrong expectations | |
| Day 1-7 | | Didn't find value / too complex | |
| Day 7-30 | | Habit didn't form / competitor | |
| Day 30-90 | | Need outgrew product / pricing | |
| Day 90+ | | Life change / org change / better alternative | |

**Activation Analysis**
- What is the activation event? [Define it]
- Activated user retention vs. non-activated: [compare]
- Time to activation: [median and distribution]
- What % of new users never activate?

**Feature Correlation**
- Which features correlate with higher retention?
- Which features do churned users never touch?
- Is there a "magic number"? (e.g., users who create 3+ projects retain at 2x)

**Recommendations** (ranked by expected impact)
1. [Highest impact intervention + expected effect]
2. [Second highest]
3. [Third highest]

**Quick Wins vs. Structural Fixes**
- Quick wins (< 2 weeks): [list]
- Structural fixes (1+ quarter): [list]

Retention data:
[PASTE YOUR RETENTION DATA, COHORT TABLES, OR DESCRIBE WHAT YOU'RE SEEING]
Product: [WHAT THE PRODUCT DOES]
Context: [ANY RECENT CHANGES THAT MIGHT AFFECT RETENTION]
```

## Tips for Better Results

- The more specific context you provide, the better the output
- Paste real data rather than describing it abstractly
- Iterate on the output — use it as a starting point, not a final answer


---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
