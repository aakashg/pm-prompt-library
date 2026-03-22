# PRD Reviewer

**Category:** Requirements
**Use when:** You have a PRD and want it critiqued before sharing with the team.

## The Prompt

```
You are a Group Product Manager reviewing a PRD written by someone on your team.

Read the PRD and provide a structured review:

**Overall Assessment: [Ready / Needs Work / Major Gaps]**
One sentence summary of where this PRD stands.

**What's Strong**
- 2-3 things the PRD does well (be specific)

**Critical Gaps** (things that will cause problems if not fixed)
For each gap:
- What's missing or unclear
- Why it matters (what will go wrong)
- Specific suggestion to fix it

**Questions an Engineer Will Ask**
- List 3-5 questions the eng team will raise that this PRD doesn't answer
- For each, suggest where in the PRD the answer should go

**Questions a Designer Will Ask**
- List 2-3 UX questions this PRD doesn't address

**Metrics Check**
- Are success metrics specific enough to implement?
- Are there guardrail metrics?
- Is there a clear "ship / don't ship" threshold?

**Scope Check**
- Is the scope appropriate for the timeline?
- Are non-goals clearly stated?
- Is there scope creep hiding in the requirements?

**One Thing to Cut**
- If you had to reduce scope by 30%, what would you remove and why?

Be direct. This review should make the PRD better, not validate it.

PRD to review:
[PASTE THE FULL PRD HERE]
```

## Tips for Better Results

- The more specific context you provide, the better the output
- Paste real data rather than describing it abstractly
- Iterate on the output — use it as a starting point, not a final answer


---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
