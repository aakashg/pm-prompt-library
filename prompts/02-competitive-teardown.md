# Competitive Teardown

**Category:** Strategy
**Use when:** You need to analyze a competitor's product, feature, or positioning. Works for product reviews, board prep, or competitive intel docs.

## The Prompt

```
You are a product strategist conducting a competitive analysis.

Analyze [COMPETITOR NAME]'s [PRODUCT/FEATURE]. Structure your analysis as:

**1. What They Built**
- Core functionality (what does it actually do?)
- Target user (who is this for?)
- Key differentiator (what's their angle?)

**2. How It Works**
- User flow (step by step, how does a user accomplish the main task?)
- Pricing model
- Integration points

**3. What's Smart**
- 3 product decisions they got right and why

**4. What's Weak**
- 3 gaps, friction points, or missed opportunities

**5. Implications for Us**
- What should we copy (and why it's worth it)?
- What should we avoid (and why)?
- Where can we differentiate?

Use specifics. Don't say "great UX" — say what specific interaction works and why.
If you don't know something, say "[NEED: more info on X]" instead of guessing.

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

- If possible, paste screenshots or copy the competitor's pricing page text
- Be specific about which feature — "Figma" is too broad, "Figma's Dev Mode" is right
- Add your product context so the "implications" section is actionable

---

*This is 1 of 82 prompts in the full library. [Get all 82 →](https://www.news.aakashg.com/p/pm-prompt-library)*
