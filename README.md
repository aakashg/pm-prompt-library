# PM Prompt Library

[![Stars](https://img.shields.io/github/stars/aakashg/pm-prompt-library?style=flat-square)](https://github.com/aakashg/pm-prompt-library/stargazers)
[![License](https://img.shields.io/github/license/aakashg/pm-prompt-library?style=flat-square)](LICENSE)
[![Prompts](https://img.shields.io/badge/prompts-25-blue?style=flat-square)](prompts/)

25 battle-tested AI prompts for product managers. Copy, paste, customize, ship.

Works in ChatGPT, Claude, and any LLM. Each prompt tested across 50+ real PM scenarios.

**These 25 cover the core PM workflow. The full library has 82 prompts across 12 categories, with advanced variants, chaining techniques, and domain-specific versions for B2B, B2C, marketplace, and AI products.**

**[Get the full PM Prompt Library (82 prompts) →](https://www.news.aakashg.com/p/pm-prompt-library)**

---

## What's Inside

### Requirements
| # | Prompt | Use When |
|---|--------|----------|
| 1 | [User Story Generator](prompts/01-user-story-generator.md) | Turn vague requests into structured user stories with acceptance criteria |
| 8 | [PRD Reviewer](prompts/08-prd-reviewer.md) | Critique a PRD before sharing it with the team |
| 25 | [API Spec Reviewer](prompts/25-api-spec-reviewer.md) | Review an API spec from a product (not code) perspective |

### Strategy
| # | Prompt | Use When |
|---|--------|----------|
| 2 | [Competitive Teardown](prompts/02-competitive-teardown.md) | Analyze a competitor's product, feature, or positioning |
| 10 | [Roadmap Prioritizer](prompts/10-roadmap-prioritizer.md) | Prioritize a list of features using a structured framework |
| 12 | [OKR Writer](prompts/12-okr-writer.md) | Turn goals into properly structured OKRs |
| 16 | [Pricing Page Reviewer](prompts/16-pricing-page-reviewer.md) | Get feedback on a pricing page before launch |
| 21 | [Go-to-Market Planner](prompts/21-go-to-market-planner.md) | Plan a feature or product launch |
| 23 | [Competitive Moat Analyzer](prompts/23-competitive-moat-analyzer.md) | Analyze what makes a competitive advantage defensible |

### Execution
| # | Prompt | Use When |
|---|--------|----------|
| 3 | [Launch Risk Assessment](prompts/03-launch-risk-assessment.md) | Stress-test a launch plan before shipping |
| 9 | [Sprint Planner](prompts/09-sprint-planning.md) | Plan a sprint from a backlog of tickets and priorities |
| 14 | [Postmortem Writer](prompts/14-postmortem-writer.md) | Write a structured postmortem after something went wrong |
| 15 | [Onboarding Flow Designer](prompts/15-onboarding-flow-designer.md) | Design or improve a user onboarding flow |
| 17 | [Feature Flag Planner](prompts/17-feature-flag-planner.md) | Plan a feature flag rollout strategy |
| 20 | [Bug Report Writer](prompts/20-bug-report-writer.md) | Turn a vague user complaint into a clear engineering ticket |

### Analytics
| # | Prompt | Use When |
|---|--------|----------|
| 4 | [Metric Definer](prompts/04-metric-definer.md) | Define success metrics for a feature or initiative |
| 7 | [A/B Test Designer](prompts/07-ab-test-designer.md) | Design an A/B test with hypothesis, variants, and sample size |
| 18 | [Data Request Writer](prompts/18-data-request-writer.md) | Write a clear data request for your analytics team |
| 24 | [Retention Analyzer](prompts/24-retention-analyzer.md) | Diagnose why users are churning or not coming back |

### Communication
| # | Prompt | Use When |
|---|--------|----------|
| 5 | [Stakeholder Update](prompts/05-stakeholder-update.md) | Write a status update fast |
| 13 | [Release Notes Writer](prompts/13-release-notes-writer.md) | Turn a changelog into user-facing release notes |
| 19 | [Meeting Agenda Creator](prompts/19-meeting-agenda-creator.md) | Create a focused meeting agenda that respects everyone's time |

### Research
| # | Prompt | Use When |
|---|--------|----------|
| 6 | [User Interview Guide](prompts/06-user-interview-guide.md) | Prepare for user interviews with a structured script |
| 11 | [Customer Feedback Analyzer](prompts/11-customer-feedback-analyzer.md) | Identify patterns in a pile of customer feedback |
| 22 | [User Persona Builder](prompts/22-user-persona-builder.md) | Build user personas from research data, not assumptions |

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

These 25 prompts are fully functional -- use them as-is. The full library of 82 prompts covers:

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

## Contributing

Found a bug, have a better variant, or want to add a new prompt? See [CONTRIBUTING.md](CONTRIBUTING.md) and start from [prompts/TEMPLATE.md](prompts/TEMPLATE.md).

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
