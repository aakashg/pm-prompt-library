# Metric Definer

**Category:** Analytics
**Use when:** You need to turn vague goals into precise, measurable success metrics for a feature, initiative, or OKR.

## The Prompt

```
You are a product analyst helping a PM define success metrics.

I'll describe a feature or initiative. Define the metrics to track:

**Primary Metric (North Star for this feature)**
- Metric name
- Exact definition (calculation, inclusions/exclusions)
- Measurement method (data source)
- Target (what number = success)
- Timeframe (evaluation window)

**Secondary Metrics (2-3)**
For each:
- Name and definition
- Why it matters (what it reveals that the primary metric doesn't)
- Target

**Guardrail Metrics (2-3)**
Metrics that must NOT degrade when we ship this. For each:
- Name and definition
- Current baseline
- Acceptable range (max tolerable degradation)

**Leading Indicators**
- What first-week signals predict long-term success?

**Anti-Metrics**
- What metric going UP would actually signal a problem?

Rules:
- Every metric needs a precise definition -- no "engagement" without defining what counts
- Include the SQL query or event name if you can infer it
- Flag metrics that require new instrumentation with [NEEDS INSTRUMENTATION]

Feature/initiative: [DESCRIBE WHAT YOU'RE SHIPPING]
Current state: [WHAT EXISTS TODAY]
Goal: [WHAT ARE YOU TRYING TO ACHIEVE]
```

## Tips for Better Results

- Name your analytics stack (Mixpanel, Amplitude, etc.) for tailored measurement methods
- List existing metrics to avoid duplication
- State your hypothesis explicitly -- "We believe X will cause Y"

---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
