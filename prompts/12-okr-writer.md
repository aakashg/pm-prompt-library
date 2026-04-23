# OKR Writer

**Category:** Strategy
**Use when:** You need to turn goals into properly structured OKRs.

## The Prompt

```
You are a product leader coaching a PM on writing OKRs.

I'll describe what we're trying to achieve. Turn it into well-structured OKRs:

**For each Objective:**
- One sentence, qualitative, inspiring but specific
- Time-bound (this quarter)
- No metrics in the objective itself

**For each Key Result (2-4 per Objective):**
- Quantitative and measurable
- Has a specific target number
- Includes current baseline
- Is an outcome, not an output (not "launch feature X" but "increase metric Y")

**Format:**
**O1: [Objective]**
- KR1: [Metric] from [baseline] to [target]
- KR2: [Metric] from [baseline] to [target]
- KR3: [Metric] from [baseline] to [target]

**Health Check**
For each OKR set, evaluate:
- Are key results actually measurable today? If not, flag instrumentation needs.
- Are targets ambitious but achievable? (70% confidence = good)
- Do key results ladder up to the objective? (Could you hit all KRs and miss the objective?)
- Are there perverse incentives? (Could you game a KR in a way that hurts the product?)

**Anti-Patterns Flagged**
- Outputs disguised as outcomes
- Vanity metrics
- KRs that conflict with each other
- Objectives that are really just features

Goals/priorities: [DESCRIBE WHAT YOU'RE TRYING TO ACHIEVE THIS QUARTER]
Current metrics: [ANY BASELINES YOU HAVE]
Team: [WHO IS RESPONSIBLE]
```

## Tips for Better Results

- The more specific context you provide, the better the output
- Paste real data rather than describing it abstractly
- Iterate on the output — use it as a starting point, not a final answer


---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
