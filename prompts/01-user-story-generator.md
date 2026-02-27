# User Story Generator

**Category:** Requirements
**Use when:** You have a vague feature request, Slack message, or customer quote and need to turn it into structured user stories with acceptance criteria.

## The Prompt

```
You are a senior product manager writing user stories for an engineering team.

I'll give you a feature description. Turn it into user stories following this format:

**User Story:**
As a [user type], I want to [action] so that [outcome].

**Acceptance Criteria:**
- Given [context], when [action], then [result]
- Given [context], when [action], then [result]
- [Add more as needed]

**Edge Cases:**
- [List 3-5 edge cases the engineering team should consider]

**Not In Scope:**
- [List what this story explicitly does NOT cover]

Rules:
- Each story should be independently shippable
- Acceptance criteria must be testable — no vague language
- If the feature is large, break it into multiple stories and note dependencies
- Flag any assumptions you're making with [ASSUMPTION: ...]

Feature description:
[PASTE YOUR FEATURE DESCRIPTION, SLACK MESSAGE, OR CUSTOMER REQUEST HERE]

Target user: [WHO IS THIS FOR]
Context: [ANY RELEVANT CONTEXT — EXISTING FEATURES, CONSTRAINTS, ETC.]
```

## Example

**Input:**
Feature description: "We need to let users export their data"
Target user: B2B SaaS customers
Context: We have a dashboard with analytics data. Customers have been asking for CSV exports. We also need to think about SOC 2 compliance.

**Output:** (truncated)
> **User Story 1:**
> As a B2B customer, I want to export my dashboard data as a CSV so that I can analyze it in my own tools.
>
> **Acceptance Criteria:**
> - Given I am on the analytics dashboard, when I click "Export," then a CSV file downloads containing all visible data
> - Given I have applied filters, when I export, then only filtered data is included
> - Given the export contains >10K rows, when I click export, then I see a progress indicator
>
> **Edge Cases:**
> - What happens if a user exports while data is still loading?
> - How do we handle special characters in data fields?
> - What's the max row limit before we need async/email delivery?

## Tips for Better Results

- The more context you give, the better the edge cases
- Paste the actual Slack message or customer quote — don't summarize it
- Add technical constraints if you know them (e.g., "we use PostgreSQL" or "max response time is 2s")

---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
