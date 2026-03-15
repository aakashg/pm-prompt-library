# A/B Test Designer

**Category:** Analytics
**Use when:** You need to design an A/B test with proper hypothesis, variants, sample size, and success criteria.

## The Prompt

```
You are a product analyst designing an A/B test.

I'll describe the change we want to test. Design a complete A/B test plan:

**Hypothesis**
Format: "We believe [change] will [effect] for [users], measured by [metric], because [reasoning]."

**Variants**
- Control: [Exact current experience]
- Treatment: [Exact changed experience]
- Note any other variants if relevant

**Primary Metric**
- Metric name and exact definition
- Current baseline value
- Minimum detectable effect (MDE) — what's the smallest change worth shipping?
- Direction: are we looking for increase or decrease?

**Guardrail Metrics (2-3)**
- Metrics that must NOT degrade
- Acceptable tolerance range

**Sample Size & Duration**
- Required sample size per variant (assume 80% power, 95% significance)
- Estimated days to reach sample size given current traffic
- Minimum runtime (at least 1 full business cycle — usually 1-2 weeks)

**Segmentation**
- Who is included/excluded
- Any segments to analyze separately (new vs returning, mobile vs desktop)

**Decision Framework**
- If primary metric is positive AND guardrails hold → Ship
- If primary metric is positive BUT guardrail degrades → [Decision]
- If primary metric is neutral → Do not ship
- If primary metric is negative → Do not ship

**Risks & Gotchas**
- Novelty effects
- Selection bias
- Interaction with other running tests
- Seasonal factors

Feature change: [DESCRIBE THE CHANGE YOU WANT TO TEST]
Current state: [WHAT EXISTS TODAY]
Traffic: [APPROXIMATE DAILY USERS WHO WOULD SEE THIS]
```

## Tips for Better Results

- The more specific context you provide, the better the output
- Paste real data rather than describing it abstractly
- Iterate on the output — use it as a starting point, not a final answer


---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
