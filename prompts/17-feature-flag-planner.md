# Feature Flag Planner

**Category:** Execution
**Use when:** You're planning a feature flag rollout strategy.

## The Prompt

```
You are a senior PM planning a feature flag rollout.

I'll describe the feature. Create a rollout plan:

**Rollout Stages**
| Stage | % of Users | Duration | Criteria to Advance | Rollback Trigger |
|-------|-----------|----------|--------------------|--------------------|

**Stage Details**

**Stage 1: Internal (dogfooding)**
- Who: internal team only
- Duration: [X days]
- What to watch: functional bugs, edge cases
- Advance when: no P0/P1 bugs for [X] days

**Stage 2: Beta (opt-in)**
- Who: [X]% of users, prioritize [segment]
- Duration: [X days]
- What to watch: [metrics]
- Advance when: [criteria]

**Stage 3: Gradual rollout**
- Ramp: 5% → 25% → 50% → 100%
- Time at each step: minimum [X] days
- What to watch: [metrics]
- Advance when: [criteria]

**Monitoring Dashboard**
Metrics to watch at every stage:
- Primary: [feature-specific metric]
- Error rate: [acceptable threshold]
- Performance: [latency, load time]
- Guardrails: [metrics that must not degrade]

**Rollback Plan**
- Who can trigger rollback: [roles]
- How fast can we roll back: [seconds/minutes]
- What happens to user data created during the flag-on period?
- Communication plan if rollback happens

**Kill Criteria**
Automatically disable if:
- Error rate exceeds [X]%
- [Metric] drops below [threshold]
- [X] support tickets about this feature in [Y] hours

Feature: [DESCRIBE THE FEATURE]
Risk level: [HIGH / MEDIUM / LOW]
Users affected: [HOW MANY]
```

## Tips for Better Results

- The more specific context you provide, the better the output
- Paste real data rather than describing it abstractly
- Iterate on the output — use it as a starting point, not a final answer


---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
