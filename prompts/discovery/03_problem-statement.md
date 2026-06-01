# 03 — Problem Statement

## What this is for
Write a rigorous problem statement that holds up under pressure — 
from skeptical engineers, from executives who want ROI, and from 
customers who just want their lives to be easier.

## When to use it
- Before writing any PRD or brief
- When scope feels unclear or too broad
- When the team is debating solutions before aligning on the problem
- When a stakeholder asks "why are we building this?"

## The Prompt

<role>
You are a principal product manager and systems thinker who has seen 
hundreds of problem statements collapse in engineering handoffs because 
they were written as disguised solutions. You write problem statements 
that hold up under pressure — from skeptical engineers, from executives 
who want ROI, and from customers who just want their lives to be easier.
</role>

<context>
Here is what I know so far:

Who is affected: [e.g. small business owners, internal ops team, new users]
What they're struggling with: [describe in plain language — messy is fine]
Where this shows up: [product area, workflow, moment in the user journey]
What we've heard from customers: [paste quotes, interview notes, or tickets]
What we've tried before (if anything): [prior attempts or workarounds]
Business context: [relevant metric, OKR, or strategic pillar this connects to]
</context>

<task>
Write a rigorous problem statement I can use to align my team and 
start discovery. Think through each step before writing the final output:

STEP 1 — SEPARATE PROBLEM FROM SOLUTION
Read my context and flag any solution language hiding inside it.
Rewrite those phrases as pure problem observations.

STEP 2 — WHO EXACTLY
Sharpen the user definition. Push past the broad persona — 
identify the specific situation, trigger moment, and user state 
that makes this problem acute. Use this frame:
"A [specific user], in the moment of [trigger], 
who has already tried [workaround], experiences [friction]."

STEP 3 — THE ACTUAL PROBLEM STATEMENT
Write it in this structure:
- The problem: one crisp sentence, no solution language
- Why it matters to the user: the real cost (time, trust, money, emotion)
- Why it matters to the business: the metric or strategic risk if unsolved
- What we do NOT yet know: the open questions that discovery must answer

STEP 4 — STRENGTH TEST
Rate this problem statement on three dimensions (1–5):
- Specificity: is it narrow enough to act on?
- Evidence: is it grounded in real customer signal or still an assumption?
- Urgency: does solving this move something that matters, now?

For any dimension below 4, tell me exactly what's missing 
and what I'd need to find out to strengthen it.

STEP 5 — ONE-LINER VERSION
Write a single sentence version I can put at the top of a brief, 
a Jira epic, or say out loud in a standup without losing anyone.
</task>

<output_format>
Use a header for each step.
Be blunt — if my context is too thin to write a strong problem 
statement, tell me what's missing before you attempt it.
The final output should be something I can paste directly into a 
discovery brief or share with an engineer today.
</output_format>


## Notes
- The more customer quotes you paste in the better the output
- Step 4 is the most valuable — a score below 4 means more discovery first
- The one-liner in Step 5 is what you bring to your next standup
