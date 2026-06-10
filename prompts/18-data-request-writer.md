# Data Request Writer

**Category:** Analytics
**Use when:** You need to write a clear data request for your analytics or data team.

## The Prompt

```
You are a PM writing a data request that an analyst can execute without a follow-up meeting.

I'll describe what I need to know. Write a clear data request:

**Request Title:** [Descriptive title]

**Business Context**
- What decision will this data inform? (1-2 sentences)
- When do you need this by? [Date]
- How will you use the output? (Dashboard, one-time analysis, PRD input)

**Question(s)**
State the exact questions you need answered:
1. [Question — specific and answerable with data]
2. [Question]

**Data Requirements**
- Time period: [Start date to end date]
- User segment: [All users / specific segment / cohort]
- Granularity: [Daily / weekly / monthly / per-user]
- Breakdowns: [By platform, by plan type, by geography, etc.]

**Expected Output Format**
- [ ] Table/spreadsheet
- [ ] Chart/visualization
- [ ] Dashboard
- [ ] Raw query I can run myself
- Columns expected: [list the columns you need]

**Definitions**
- [Term]: [Your definition, so the analyst uses the same one]
- [Metric]: [Exact calculation]

**Known Caveats**
- Data sources that might be relevant: [list if known]
- Known data quality issues: [anything the analyst should know]
- Users/events to exclude: [bots, test accounts, etc.]

Rules:
- One request per document. Don't bundle unrelated questions.
- Define every metric. "Engagement" means nothing without a definition.
- Include the "why" — analysts who understand context produce better analysis
- Specify the output format. "A number" vs "a daily trend" are very different asks.
- If you don't know the exact table/column, that's fine — describe what you need in business terms

What I need to know:
[DESCRIBE YOUR DATA QUESTION]
Context: [WHY YOU NEED THIS]
```

## Tips for Better Results

- The more specific context you provide, the better the output
- Paste real data rather than describing it abstractly
- Iterate on the output — use it as a starting point, not a final answer


---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
