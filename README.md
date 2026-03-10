# PM Prompt Library

5 battle-tested AI prompts for product managers. Copy, paste, customize, ship.

These prompts work in ChatGPT, Claude, and any LLM. Each one has been tested across 50+ real PM scenarios.

**These 5 cover the essentials. The full library goes much deeper: 82 prompts across 12 categories, with advanced variants, chaining techniques, and domain-specific versions for B2B, B2C, marketplace, and AI products.**

**[Get the full PM Prompt Library (82 prompts) →](https://www.news.aakashg.com/p/pm-prompt-library)**

---

## What's Inside

| # | Prompt | Category | Use When |
|---|--------|----------|----------|
| 1 | [User Story Generator](prompts/01-user-story-generator.md) | Requirements | You need to turn vague requests into structured user stories |
| 2 | [Competitive Teardown](prompts/02-competitive-teardown.md) | Strategy | You're analyzing a competitor's product or feature |
| 3 | [Launch Risk Assessment](prompts/03-launch-risk-assessment.md) | Execution | You're about to ship and need to stress-test the plan |
| 4 | [Metric Definer](prompts/04-metric-definer.md) | Analytics | You need to define success metrics for a feature or initiative |
| 5 | [Stakeholder Update](prompts/05-stakeholder-update.md) | Communication | You need to write a status update fast |

## How to Use

1. Open the prompt file
2. Copy the prompt
3. Replace the `[BRACKETED]` sections with your specifics
4. Paste into ChatGPT, Claude, or your LLM of choice

Every prompt includes:
- The full prompt text (ready to copy)
- When to use it
- Example input/output
- Tips for better results

*This prompt library is growing — new prompts added regularly.*

## Want More?

These 5 prompts are fully functional — use them as-is. The full library goes significantly deeper with 82 prompts, including:

- PRDs and specs
- User research synthesis
- Competitive analysis
- Launch planning
- Stakeholder communication
- Metrics and analytics
- Roadmap planning
- Sprint planning
- Customer interviews
- A/B test design
- Post-mortems
- OKR writing

**[Get the full PM Prompt Library (82 prompts) →](https://www.news.aakashg.com/p/pm-prompt-library)**

---

Built by [Aakash Gupta](https://www.aakashg.com) | [Product Growth Newsletter](https://www.news.aakashg.com)

---

## Tips for Writing Better Prompts

These tips apply whether you're using prompts from this library or writing your own.

### 1. Set the role and audience

Tell the LLM who it is and who the output is for. "You are a senior PM writing for an engineering team" produces very different output than no role at all.

### 2. Be specific about format

Don't say "give me a summary." Say "give me 3-5 bullet points, each under 20 words, suitable for a Slack update." The more specific your format constraint, the more usable the output.

### 3. Provide context, not just instructions

Bad: "Write user stories for a calendar feature."
Good: "Write user stories for a calendar feature in a B2B project management tool. Users are mid-market teams (50-200 people). The calendar should sync with Google Calendar and show project deadlines."

### 4. Use the "do / don't" pattern

After your main instruction, add explicit constraints:
- DO: use concrete metrics, cite the data I provided, flag assumptions
- DON'T: use jargon without defining it, make up statistics, exceed 2 pages

### 5. Ask for reasoning before conclusions

For analytical prompts (prioritization, trade-off analysis), ask the LLM to show its reasoning before giving a recommendation. This catches flawed logic early.

### 6. Iterate in the same conversation

Your first prompt rarely gives a perfect result. Follow up:
- "Make the success metrics more specific"
- "Rewrite the problem statement with more urgency"
- "Add a section on risks"

This is faster than trying to write the perfect prompt upfront.

### 7. Include examples of good output

If you know what great looks like, show a snippet. LLMs pattern-match well. Even one example of the tone, depth, and format you want dramatically improves output.

### 8. Use placeholders consistently

Stick to `[BRACKET CAPS]` for inputs the user fills in: `[PRODUCT NAME]`, `[TARGET METRIC]`, `[TIME PERIOD]`. This makes prompts scannable and reusable.
