# Launch Risk Assessment

**Category:** Execution
**Use when:** You're about to ship a feature or product and need to stress-test the plan before launch.

## The Prompt

```
You are a senior PM who has shipped 50+ features. I'm about to launch something and I need you to poke holes in my plan.

Review my launch plan and provide:

**1. Launch Readiness Score: [1-10]**
Give an honest score and one sentence explaining it.

**2. Risks I'm Probably Missing**
List 5 risks I likely haven't considered, ranked by severity. For each:
- Risk description
- Likelihood (high/medium/low)
- Impact if it happens
- Mitigation (what I should do now)

**3. Rollback Plan Check**
- Can we turn this off instantly if something breaks? If not, flag it.
- What's the blast radius if this fails?

**4. Dependencies I Should Confirm**
- External dependencies (APIs, partners, other teams)
- Timing dependencies (does order of operations matter?)
- Data dependencies (do we need something populated before launch?)

**5. First 48 Hours**
- What should I monitor in the first 48 hours?
- What metrics would tell me to rollback?
- Who needs to be on-call?

Be direct. If something looks risky, say so. Don't soften bad news.

My launch plan:
[PASTE YOUR LAUNCH PLAN, FEATURE SPEC, OR DESCRIBE WHAT YOU'RE SHIPPING]

Launch date: [DATE]
Users affected: [WHO AND HOW MANY]
```

## Tips for Better Results

- Include your rollback plan if you have one — the AI will find holes in it
- Mention past launches that went wrong at your company for relevant pattern matching
- Add team size and on-call capacity so resourcing suggestions are realistic

---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
