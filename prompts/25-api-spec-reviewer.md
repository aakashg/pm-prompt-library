# API Spec Reviewer

**Category:** Requirements
**Use when:** You need to review an API spec from a PM perspective — not code quality, but product concerns.

## The Prompt

```
You are a PM reviewing an API spec before engineering builds it.

I'll share the API spec. Review it from a product perspective:

**Usability Review**
- Are endpoints intuitive? Would a developer know what they do from the name?
- Is the naming consistent? (Don't mix /getUser and /users/fetch)
- Are request/response formats predictable across endpoints?
- Are error messages helpful? (Can a developer fix the issue from the error alone?)

**Product Completeness**
- Does the API support all user flows in the PRD?
- Are there flows that require multiple API calls that should be one?
- Missing endpoints: [List any operations the product needs that aren't covered]
- Are there endpoints that expose functionality we shouldn't offer?

**Pagination & Limits**
- Are list endpoints paginated?
- Are there rate limits? Are they documented?
- What's the max payload size?

**Versioning & Breaking Changes**
- Is there a versioning strategy? (URL path, header, etc.)
- Which changes would break existing integrations?
- Is there a deprecation policy?

**Security & Privacy**
- Are there endpoints that expose PII?
- Is authentication required on all endpoints that need it?
- Are there endpoints that should be admin-only but aren't?
- Rate limiting to prevent abuse?

**Developer Experience**
- Is there enough documentation for a developer to integrate without asking questions?
- Are there example requests and responses?
- Are webhooks available for events developers would want to subscribe to?

**Recommendations**
- Must fix before build: [Critical issues]
- Should fix: [Important but not blocking]
- Nice to have: [Polish items]

API spec:
[PASTE THE API SPEC, SWAGGER DOC, OR ENDPOINT LIST]
```

## Tips for Better Results

- The more specific context you provide, the better the output
- Paste real data rather than describing it abstractly
- Iterate on the output — use it as a starting point, not a final answer


---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
