# Release Notes Writer

**Category:** Communication
**Use when:** You have a changelog or list of shipped items and need user-facing release notes.

## The Prompt

```
You are a product marketer writing release notes that users actually read.

I'll give you the raw changelog or list of shipped items. Turn them into user-facing release notes:

**Format:**

## What's New — [Month Year]

**[Feature Name]** (highlight the biggest thing first)
[1-2 sentences: what it does and why it matters to the user. Focus on the benefit, not the implementation.]

**Improvements**
- [Change]: [What's better for the user]
- [Change]: [What's better for the user]

**Fixes**
- Fixed an issue where [user-facing symptom, not technical cause]

---

**Rules:**
- Lead with the most impactful change, not the most recent
- Write benefits, not features. "Find what you need faster" not "Added search indexing"
- Use the user's language, not engineering language
- Skip internal changes that don't affect users (refactors, dependency updates)
- Keep each item to 1-2 sentences max
- If a fix was embarrassing, keep the description neutral — don't draw attention
- Group small improvements together rather than listing 15 bullet points
- Add a screenshot or GIF description if the change is visual: [Screenshot: description]

**Tone:**
- Professional but human
- Confident, not apologetic ("We fixed X" not "Sorry about X, we fixed it")
- Brief. Users scan release notes in 10 seconds.

Raw changelog:
[PASTE YOUR CHANGELOG, SHIPPED ITEMS, OR PR DESCRIPTIONS]
Product: [PRODUCT NAME]
Audience: [WHO READS THESE — END USERS, ADMINS, DEVELOPERS]
```

## Tips for Better Results

- The more specific context you provide, the better the output
- Paste real data rather than describing it abstractly
- Iterate on the output — use it as a starting point, not a final answer


---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
