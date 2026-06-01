# 02 — PRD Writing

## What this is for
Write a PRD that cross-functional squads — engineering, 
design, and stakeholders — actually read, understand, 
and act on without a follow-up meeting.

## When to use it
- Before any engineering handoff
- When scope needs to be locked before sprint planning
- When design and engineering need a single source of truth
- When stakeholders keep asking "what exactly are we building?"

## The Prompt

<role>
You are a principal product manager who has written hundreds 
of PRDs for cross-functional squads at large financial 
institutions. You know that a PRD isn't a novel — it's a 
decision document. Every word either clarifies or confuses. 
You write PRDs that engineers bookmark, designers reference, 
and executives can skim in 3 minutes.
</role>

<context>
I am a Senior PM at Wells Fargo writing a PRD for the 
following initiative:

Initiative name: [NAME]
Problem we are solving: [one sentence]
Target user: [who specifically]
Success metric: [how we'll know it worked]
Launch target: [date or sprint]

What we are building:
[describe in plain language — messy is fine]

What we are NOT building:
[list explicit scope exclusions]

Key constraints:
- Technical: [e.g. must work within existing API]
- Compliance: [e.g. must meet Wells Fargo data privacy standards]
- Design: [e.g. must follow existing design system]

Open questions:
- [QUESTION 1]
- [QUESTION 2]

Key stakeholders:
- Engineering lead: [NAME]
- Design lead: [NAME]
- Executive sponsor: [NAME]
</context>

<task>
Write a PRD that cross-functional squads will actually use.
Think step by step:

STEP 1 — PROBLEM STATEMENT
Write a crisp one-paragraph problem statement that answers:
- Who has this problem?
- What is the cost of not solving it?
- Why now?

STEP 2 — SUCCESS METRICS
Write 3 success metrics using this format:
"We will know this worked when [measurable outcome] 
by [date or sprint]."
One metric for users, one for the business, 
one for the team.

STEP 3 — SCOPE DEFINITION
Write a clear scope table:

| In Scope | Out of Scope |
|---|---|
| [ITEM] | [ITEM] |

Flag any scope item that is likely to cause debate 
and write one sentence pre-empting that debate.

STEP 4 — FUNCTIONAL REQUIREMENTS
Write the functional requirements in plain language — 
not technical specs. Use this format for each:
"When [user does X], the system should [do Y], 
so that [outcome Z]."
Write as many as needed — no padding, no gaps.

STEP 5 — OPEN QUESTIONS LOG
For each open question write:
- The question
- Who owns answering it
- The deadline for resolution
- What we do if it isn't resolved in time

STEP 6 — ONE PAGE SUMMARY
Write a one-paragraph TL;DR I can put at the top of the PRD 
for executive sponsors who will only read the first 
3 sentences.
</task>

<output_format>
Use headers for each step.
Write in plain language — no jargon, no passive voice.
The full PRD should be scannable in under 3 minutes.
Flag any section where my context was too thin to write 
confidently — tell me what's missing.
</output_format>

## Example Output
Paste a real output you got from running this prompt here.
This helps others see what good looks like.

## Notes
- The scope table in Step 3 prevents 80% of mid-sprint 
scope creep
- Step 5 is your insurance policy — never ship with 
unresolved open questions
- The TL;DR in Step 6 is what your executive sponsor 
actually reads
- Share the PRD with engineering lead before design 
handoff — not after
