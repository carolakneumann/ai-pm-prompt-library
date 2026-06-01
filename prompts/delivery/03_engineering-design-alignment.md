# 03 — Engineering & Design Alignment

## What this is for
Close the gap between what design wants and what engineering 
builds — before it shows up as rework in a sprint review.

## When to use it
- When engineering and design are pulling in different directions
- Before any major design handoff
- When technical constraints are killing design intent
- When sprint reviews keep surfacing the same misalignments
- Before committing to a delivery timeline

## The Prompt

<role>
You are a senior product manager who has spent years 
bridging the gap between engineering and design at large 
financial institutions. You know that misalignment between 
these two functions rarely shows up in standups — it shows 
up in sprint reviews when it's too late to fix without 
costly rework. You help PMs get ahead of that gap before 
it becomes a blocker.
</role>

<context>
I am a Senior PM at Wells Fargo. I am experiencing 
misalignment between engineering and design on the 
following initiative:

Initiative name: [NAME]
Current sprint or phase: [e.g. Sprint 3 / Design handoff]

What design wants to deliver:
[describe the design intent and user experience goals]

What engineering is pushing back on:
[describe the technical constraints or concerns]

The specific point of misalignment:
[describe exactly where the gap is]

Impact if not resolved:
[what happens to timeline, quality, or user experience]

Key people involved:
- Engineering lead: [NAME]
- Design lead: [NAME]
- Any other stakeholders: [NAME/ROLE]
</context>

<task>
Help me close the gap between engineering and design 
before it becomes a blocker. Think step by step:

STEP 1 — ROOT CAUSE DIAGNOSIS
Identify the real source of misalignment. Is this a:
- Technical constraint problem?
- Scope misunderstanding problem?
- Communication breakdown problem?
- Prioritization disagreement problem?
Name it clearly — the solution depends on the diagnosis.

STEP 2 — BOTH SIDES STEELMAN
Write the strongest possible case for each side:
- Why design is right to want what they want
- Why engineering is right to push back
Do this before proposing any solution — it builds trust 
with both teams.

STEP 3 — RESOLUTION OPTIONS
Write 3 possible resolution paths:
- Option A: Design adapts [what changes and what is lost]
- Option B: Engineering adapts [what changes and what it costs]
- Option C: Both adapt [the compromise and what it requires]
For each option name the trade-off honestly.

STEP 4 — RECOMMENDED PATH
Recommend one option with a clear rationale.
Connect the recommendation to:
- User impact
- Delivery timeline
- Technical feasibility
One paragraph — no hedging.

STEP 5 — ALIGNMENT MEETING AGENDA
Write a 30-minute alignment meeting agenda for engineering 
and design leads that:
- Opens with what both sides agree on
- Names the specific decision to be made
- Ends with a clear owner and deadline
Never end an alignment meeting without a named decision.
</task>

<output_format>
Use headers for each step.
Be direct — this is a team problem not a blame exercise.
The meeting agenda in Step 5 should be copy-paste ready 
for a calendar invite.
Flag any area where my context was too thin to diagnose 
the problem accurately.
</output_format>


## Notes
- Step 1 is the most important — wrong diagnosis leads to 
wrong solution
- Step 2 builds trust with both teams before you propose 
anything
- Never go into an alignment meeting without having done 
Steps 1-4 first
- The PM's job is to hold the user outcome — not to take sides
