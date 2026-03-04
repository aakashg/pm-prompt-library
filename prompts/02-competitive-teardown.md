# Competitive Teardown

**Category:** Strategy
**Use when:** You need to analyze a competitor's product, feature, or positioning -- for product reviews, board prep, or competitive intel.

## The Prompt

```
You are a product strategist conducting a competitive analysis.

Analyze [COMPETITOR NAME]'s [PRODUCT/FEATURE]. Structure your analysis as:

**1. What They Built**
- Core functionality
- Target user
- Key differentiator

**2. How It Works**
- User flow (step-by-step for the primary task)
- Pricing model
- Integration points

**3. What's Smart**
- 3 product decisions they got right and why

**4. What's Weak**
- 3 gaps, friction points, or missed opportunities

**5. Implications for Us**
- What to copy (and why)
- What to avoid (and why)
- Where we can differentiate

Be specific. Never say "great UX" -- name the exact interaction and why it works.
If you lack information, say "[NEED: more info on X]" instead of guessing.

Competitor: [COMPETITOR NAME]
Product/feature: [WHAT YOU'RE ANALYZING]
Our product: [YOUR PRODUCT — for context on the "implications" section]
```

## Example

**Input:**
Competitor: Notion
Product/feature: Notion AI
Our product: Internal knowledge management tool for mid-market companies

**Output:** (key section)
> **What's Smart:**
> 1. Inline AI — it lives where you already write, no context switching. This reduces adoption friction to near zero.
> 2. Block-level AI actions — you can ask AI to act on a specific paragraph, not the whole doc. This gives users control and reduces hallucination anxiety.
> 3. Free tier inclusion — they let free users try it, creating bottom-up pressure for team upgrades.

## Tips for Better Results

- Paste screenshots or pricing page text when available
- Scope to a specific feature -- "Figma" is too broad, "Figma's Dev Mode" is right
- Include your product context so the "Implications" section stays actionable

---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
