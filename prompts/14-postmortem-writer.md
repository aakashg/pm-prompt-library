# Postmortem Writer

**Category:** Execution
**Use when:** Something went wrong and you need to write a structured postmortem.

## The Prompt

```
You are a senior PM writing a postmortem after an incident.

I'll describe what happened. Structure a blameless postmortem:

**Incident Summary**
- What happened (1-2 sentences, plain language)
- Severity: [SEV1 / SEV2 / SEV3]
- Duration: [start time] to [resolution time]
- Users affected: [number and segment]
- Business impact: [revenue, reputation, SLA, etc.]

**Timeline**
| Time | Event |
|------|-------|
(Chronological sequence from first signal to full resolution)

**Root Cause**
- Technical root cause (what broke)
- Process root cause (why it wasn't caught earlier)
- Be specific. "Human error" is not a root cause. What system allowed the error?

**What Went Well**
- 2-3 things that worked in our response
- Detection, communication, or recovery that was effective

**What Went Wrong**
- 2-3 things that failed or were too slow
- For each: why it happened and what would have prevented it

**Action Items**
| # | Action | Owner | Priority | Due Date | Type |
|---|--------|-------|----------|----------|------|
Type: Prevent (stop recurrence), Detect (catch earlier), Mitigate (reduce impact)

**Lessons Learned**
- 2-3 takeaways for the broader team
- What would we tell another team to avoid this?

Rules:
- Blameless. Focus on systems, not individuals.
- Be honest about what happened. Downplaying erodes trust.
- Action items need owners and dates. "We should improve monitoring" is not an action item.
- Include the near-misses. What almost went wrong but didn't?
- If this is a repeat incident, call that out explicitly.

What happened:
[DESCRIBE THE INCIDENT — WHAT BROKE, WHEN, WHAT YOU DID]
```

## Tips for Better Results

- The more specific context you provide, the better the output
- Paste real data rather than describing it abstractly
- Iterate on the output — use it as a starting point, not a final answer


---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
