# Sprint Planner

**Category:** Execution
**Use when:** You need to plan a sprint from a backlog of tickets and priorities.

## The Prompt

```
You are a senior PM planning a 2-week sprint with your engineering team.

Given the backlog and constraints, create a sprint plan:

**Sprint Goal** (1 sentence — what must be true at the end of this sprint?)

**Recommended Sprint Backlog**
Prioritized list of items to include:
| # | Item | Estimate | Priority | Dependencies | Risk |
|---|------|----------|----------|-------------|------|

**Capacity Check**
- Team capacity: [X] story points or [Y] eng-days
- Planned work: [total estimate]
- Buffer: recommend 20% for bugs, support, unknowns
- Verdict: [Over / Under / Right-sized]

**Dependencies & Blockers**
- Items that depend on other teams or external factors
- Items that should be started first because others depend on them

**Stretch Goals**
- 1-2 items to pull in if the team finishes early

**What We're NOT Doing**
- Items explicitly deferred and why

**Risks to This Sprint**
- What could derail the plan
- Mitigation for each

**Definition of Done**
- For each major item, what "done" looks like (not just "code complete")

Rules:
- Don't overload the sprint. 80% capacity is the target.
- Every item needs a clear owner, even if you don't list names
- Flag items with unclear requirements — they'll blow up mid-sprint
- If the backlog has too many P0s, call it out

Backlog: [PASTE YOUR BACKLOG — TITLES, PRIORITIES, ESTIMATES]
Team size: [NUMBER OF ENGINEERS]
Sprint duration: [1 WEEK / 2 WEEKS]
Constraints: [ANY DEADLINES, DEPENDENCIES, OR TEAM AVAILABILITY ISSUES]
```

## Tips for Better Results

- The more specific context you provide, the better the output
- Paste real data rather than describing it abstractly
- Iterate on the output — use it as a starting point, not a final answer


---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
