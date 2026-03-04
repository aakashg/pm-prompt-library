# PM Prompt Library

[![Stars](https://img.shields.io/github/stars/aakashg/pm-prompt-library?style=flat-square)](https://github.com/aakashg/pm-prompt-library/stargazers)
[![License](https://img.shields.io/github/license/aakashg/pm-prompt-library?style=flat-square)](LICENSE)

5 battle-tested AI prompts for product managers. Copy, paste, customize, ship.

Works in ChatGPT, Claude, and any LLM. Each prompt tested across 50+ real PM scenarios.

**These 5 cover the essentials. The full library has 82 prompts across 12 categories, with advanced variants, chaining techniques, and domain-specific versions for B2B, B2C, marketplace, and AI products.**

**[Get the full PM Prompt Library (82 prompts) →](https://www.news.aakashg.com/p/pm-prompt-library)**

---

## What's Inside

| # | Prompt | Category | Use When |
|---|--------|----------|----------|
| 1 | [User Story Generator](prompts/01-user-story-generator.md) | Requirements | Turn vague requests into structured user stories |
| 2 | [Competitive Teardown](prompts/02-competitive-teardown.md) | Strategy | Analyze a competitor's product or feature |
| 3 | [Launch Risk Assessment](prompts/03-launch-risk-assessment.md) | Execution | Stress-test a launch plan before shipping |
| 4 | [Metric Definer](prompts/04-metric-definer.md) | Analytics | Define success metrics for a feature or initiative |
| 5 | [Stakeholder Update](prompts/05-stakeholder-update.md) | Communication | Write a status update fast |

## How to Use

1. Open the prompt file
2. Copy the prompt
3. Replace the `[BRACKETED]` sections with your specifics
4. Paste into ChatGPT, Claude, or your LLM of choice

Every prompt includes:
- Full prompt text (ready to copy)
- When to use it
- Example input/output
- Tips for better results

## Want More?

These 5 prompts are fully functional -- use them as-is. The full library of 82 prompts covers:

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

Apply these whether you use prompts from this library or write your own.

### 1. Set the role and audience

Tell the LLM who it is and who the output is for. "You are a senior PM writing for an engineering team" produces vastly different output than no role at all.

### 2. Be specific about format

Not "give me a summary." Instead: "3-5 bullet points, each under 20 words, suitable for a Slack update." Tighter format constraints produce more usable output.

### 3. Provide context, not just instructions

Bad: "Write user stories for a calendar feature."
Good: "Write user stories for a calendar feature in a B2B project management tool. Users are mid-market teams (50-200 people). The calendar should sync with Google Calendar and show project deadlines."

### 4. Use the "do / don't" pattern

Add explicit constraints after your main instruction:
- DO: use concrete metrics, cite the data I provided, flag assumptions
- DON'T: use jargon without defining it, make up statistics, exceed 2 pages

### 5. Ask for reasoning before conclusions

For analytical prompts (prioritization, trade-off analysis), require the LLM to show reasoning before the recommendation. This surfaces flawed logic early.

### 6. Iterate in the same conversation

First drafts are rarely final. Follow up:
- "Make the success metrics more specific"
- "Rewrite the problem statement with more urgency"
- "Add a section on risks"

Faster than crafting the perfect prompt upfront.

### 7. Include examples of good output

Show a snippet of what great looks like. LLMs pattern-match well -- even one example of the tone, depth, and format you want dramatically improves output.

### 8. Use placeholders consistently

Stick to `[BRACKET CAPS]` for user inputs: `[PRODUCT NAME]`, `[TARGET METRIC]`, `[TIME PERIOD]`. Keeps prompts scannable and reusable.
