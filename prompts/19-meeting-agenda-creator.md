# Meeting Agenda Creator

**Category:** Communication
**Use when:** You need to create a focused meeting agenda that respects everyone's time.

## The Prompt

```
You are a PM who runs meetings that people actually want to attend.

I'll describe the meeting purpose. Create an agenda:

**Meeting: [Title]**
**Duration:** [30/45/60 minutes]
**Required attendees:** [roles, not names]
**Optional attendees:** [roles]

**Pre-Read** (send 24 hours before)
- [Document or context attendees must review before the meeting]
- Expected prep time: [X minutes]

**Agenda**

| Time | Topic | Owner | Type | Output |
|------|-------|-------|------|--------|
| 0:00 | [Topic] | [Role] | [Info/Discussion/Decision] | [What we walk away with] |

**Type definitions:**
- **Info**: One-way update, no discussion needed
- **Discussion**: Need input from the room
- **Decision**: Must leave with a decision made

**Parking Lot**
- Topics that might come up but are out of scope for this meeting
- Where those topics will be addressed instead

**Decision Framework**
If we can't reach consensus:
- Who is the decision maker?
- What's the fallback if we run out of time?

Rules:
- Every agenda item needs a TIME BOX. Meetings fail when one topic eats all the time.
- Every agenda item needs an OWNER. Someone drives each section.
- Every agenda item needs an OUTPUT. If there's no output, why are we discussing it?
- Put the most important decision first, not last (energy is highest at the start)
- Info items should be pre-reads, not presentations. Don't read slides to people.
- End 5 minutes early for action item recap
- Max 6 people in a decision meeting. More than that = nobody decides.

Meeting purpose: [WHAT DO YOU NEED FROM THIS MEETING]
Attendees: [WHO WILL BE THERE]
Duration: [TIME AVAILABLE]
Context: [ANY BACKGROUND THE AGENDA SHOULD ACCOUNT FOR]
```

## Tips for Better Results

- The more specific context you provide, the better the output
- Paste real data rather than describing it abstractly
- Iterate on the output — use it as a starting point, not a final answer


---

*This prompt covers the basics. The full library version includes advanced variants, chaining patterns with other prompts, and domain-specific versions. [See all 82 prompts →](https://www.news.aakashg.com/p/pm-prompt-library)*
