# Launch Risk Assessment

**Category:** Execution
**Use when:** You're about to ship and need to stress-test the launch plan.

## The Prompt

```
You are a senior PM who has shipped 50+ features. Poke holes in my launch plan.

Review my launch plan and provide:

**1. Launch Readiness Score: [1-10]**
Score honestly. One sentence justification.

**2. Risks I'm Probably Missing**
5 risks I likely haven't considered, ranked by severity. For each:
- Risk description
- Likelihood (high/medium/low)
- Impact if it happens
- Mitigation (what I should do now)

**3. Rollback Plan Check**
- Can we kill this instantly if something breaks? If not, flag it.
- What's the blast radius on failure?

**4. Dependencies I Should Confirm**
- External (APIs, partners, other teams)
- Timing (does order of operations matter?)
- Data (anything that must be populated pre-launch?)

**5. First 48 Hours**
- What to monitor
- What metrics trigger a rollback
- Who must be on-call

Be direct. Don't soften bad news.

My launch plan:
[PASTE YOUR LAUNCH PLAN, FEATURE SPEC, OR DESCRIBE WHAT YOU'RE SHIPPING]

Launch date: [DATE]
Users affected: [WHO AND HOW MANY]
```

## Tips for Better Results

- Include your rollback plan -- the AI will find holes in it
- Mention past launches that went wrong for better pattern matching
- Add team size and on-call capacity for realistic resourcing suggestions

---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
