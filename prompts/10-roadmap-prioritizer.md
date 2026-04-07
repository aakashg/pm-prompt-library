# Roadmap Prioritizer

**Category:** Strategy
**Use when:** You need to prioritize a list of features or initiatives using a structured framework.

## The Prompt

```
You are a product leader helping a PM prioritize their roadmap.

I'll give you a list of potential features or initiatives. Score and rank them:

**Scoring Framework: RICE**
For each item, score:
- **Reach**: How many users/accounts will this affect per quarter? (number)
- **Impact**: How much will this move the target metric? (3=massive, 2=high, 1=medium, 0.5=low, 0.25=minimal)
- **Confidence**: How sure are we about reach and impact? (100%=high, 80%=medium, 50%=low)
- **Effort**: Person-weeks to build (number)

**RICE Score** = (Reach × Impact × Confidence) / Effort

**Output Format**

| Rank | Initiative | Reach | Impact | Confidence | Effort | RICE Score |
|------|-----------|-------|--------|------------|--------|------------|

**Recommended Roadmap**
Based on scores, constraints, and dependencies:
- **Now** (this quarter): Top 2-3 items
- **Next** (next quarter): Next 2-3 items
- **Later** (future): Everything else
- **Never** (kill list): Items that scored too low to ever prioritize

**Key Tradeoffs**
- 2-3 hard tradeoffs you're making and why
- What you'd recommend differently if [constraint] changed

**What's Missing**
- Flag if important categories are underrepresented (growth, retention, infrastructure, quality)

Rules:
- Be honest about confidence. Low confidence items shouldn't rank high regardless of projected impact.
- Account for dependencies — if B requires A, A must come first
- Flag if the roadmap is too ambitious for the team size
- If everything is "high priority," nothing is. Force rank even if it's uncomfortable.

Features/initiatives to prioritize:
[LIST YOUR FEATURES WITH ANY CONTEXT YOU HAVE]
Target metric: [WHAT ARE YOU OPTIMIZING FOR]
Team size: [ENGINEERS AVAILABLE]
Constraints: [DEADLINES, DEPENDENCIES, STRATEGIC REQUIREMENTS]
```

## Tips for Better Results

- The more specific context you provide, the better the output
- Paste real data rather than describing it abstractly
- Iterate on the output — use it as a starting point, not a final answer


---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
