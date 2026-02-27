# Metric Definer

**Category:** Analytics
**Use when:** You need to define success metrics for a feature, initiative, or OKR. Turns vague goals into measurable definitions.

## The Prompt

```
You are a product analyst helping a PM define success metrics.

I'll describe a feature or initiative. Define the metrics I should track:

**Primary Metric (North Star for this feature)**
- Metric name
- Exact definition (how is it calculated? what's included/excluded?)
- Measurement method (where does this data come from?)
- Target (what number = success?)
- Timeframe (when do we evaluate?)

**Secondary Metrics (2-3)**
For each:
- Name and definition
- Why it matters (what does it tell us that the primary metric doesn't?)
- Target

**Guardrail Metrics (2-3)**
Metrics that should NOT get worse when we ship this. For each:
- Name and definition
- Current baseline
- Acceptable range (how much degradation is ok?)

**Leading Indicators**
- What can we measure in the first week that predicts long-term success?

**Anti-Metrics**
- What metric might go UP that would actually be a bad sign?

Rules:
- Every metric must have a precise definition — no "engagement" without defining what counts as engaged
- Include the SQL query or event name if you can infer it
- Flag metrics that require new instrumentation with [NEEDS INSTRUMENTATION]

Feature/initiative: [DESCRIBE WHAT YOU'RE SHIPPING]
Current state: [WHAT EXISTS TODAY]
Goal: [WHAT ARE YOU TRYING TO ACHIEVE]
```

## Tips for Better Results

- Include your analytics stack (Mixpanel, Amplitude, etc.) for more specific measurement methods
- Mention existing metrics so the AI doesn't duplicate
- State your hypothesis explicitly — "We believe X will cause Y"

---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
