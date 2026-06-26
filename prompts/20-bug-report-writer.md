# Bug Report Writer

**Category:** Execution
**Use when:** You got a vague user complaint and need to turn it into a clear bug report for engineering.

## The Prompt

```
You are a PM translating user complaints into actionable bug reports.

I'll give you the raw user complaint or support ticket. Turn it into a bug report:

**Title:** [Clear, specific — not "Something is broken"]

**Severity:** [P0: System down / P1: Major feature broken / P2: Minor feature broken / P3: Cosmetic]

**Environment**
- Platform: [Web / iOS / Android]
- Browser/Version: [if known]
- User segment: [plan type, account age, etc.]
- Frequency: [Always / Intermittent / One-time]

**Steps to Reproduce**
1. [Specific step]
2. [Specific step]
3. [Specific step]

**Expected Behavior**
[What should happen]

**Actual Behavior**
[What actually happens]

**Impact**
- Users affected: [number or estimate]
- Business impact: [revenue, retention, SLA implications]
- Workaround available: [Yes — describe it / No]

**Evidence**
- [Screenshot description or error message]
- [Relevant logs, URLs, or user IDs for debugging]

**Context**
- When did this start? [If known]
- Related recent changes: [Any deploys, config changes, or incidents]
- Related bugs: [Links to similar past issues]

Rules:
- Be specific. "The app is slow" → "Dashboard takes 12 seconds to load for accounts with >10K contacts"
- Include the user's exact words as a quote, then translate to technical terms
- Don't diagnose the cause — that's engineering's job. Describe the symptom.
- Always include severity. Engineering prioritizes based on this.
- If you can't reproduce it, say so — intermittent bugs are still bugs

User complaint:
[PASTE THE RAW USER COMPLAINT, SUPPORT TICKET, OR SLACK MESSAGE]
Product area: [WHICH PART OF THE PRODUCT]
```

## Tips for Better Results

- The more specific context you provide, the better the output
- Paste real data rather than describing it abstractly
- Iterate on the output — use it as a starting point, not a final answer


---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
