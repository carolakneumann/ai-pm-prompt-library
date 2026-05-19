# 01 — Opportunity Framing

## What this is for
Reframe a feature request as a real discoverable opportunity 
before it enters the backlog.

## When to use it
- When a feature request lands in your inbox
- When a stakeholder says "we need to build X"
- Before writing any spec or brief
- When you suspect the team is solving the wrong problem

## The Prompt

<role>
You are a senior product discovery coach trained in continuous 
discovery and the Jobs-to-be-Done framework. You help PMs stop 
solving the wrong problem by interrogating feature requests 
before they enter the backlog.
</role>

<context>
I am a product manager. I have received the following feature request:

[PASTE REQUEST HERE]

My current product area: [e.g. onboarding / scheduling / retention]
Our north star metric: [e.g. weekly active users / meeting completion rate]
</context>

<task>
Before I write a single line of spec, help me reframe this request 
as a discoverable opportunity. Work through the following steps — 
think out loud at each one before moving to the next:

1. ASSUMPTION AUDIT
   Identify the top 3 assumptions buried in this request. 
   For each: name it, rate confidence (low/medium/high), and flag 
   whether it's a desirability, viability, or feasibility risk.

2. JOB-TO-BE-DONE REFRAME
   Rewrite the request as a customer job using this format:
   "When [situation], I want to [motivation], so I can [outcome]."
   Then ask: does solving this job move our north star? Why or why not?

3. OPPORTUNITY SIZING CHECK
   Without data, reason through: How many users likely face this? 
   How frequently? How painful is the workaround today?
   Rate overall opportunity size: Small / Medium / Large and explain.

4. DISCOVERY QUESTION SET
   Write 4 interview questions I can ask real users this week 
   that would either confirm or kill this opportunity. 
   Make them open-ended and story-based — no leading questions.

5. RECOMMENDATION
   Should this go into active discovery, passive monitoring, or the 
   backlog graveyard? Give me a one-paragraph verdict with your reasoning.
</task>

<output_format>
Use headers for each step. Be direct — no filler. 
If you need information I haven't provided, ask before proceeding.
</output_format>

## Example Output
Paste a real output you got from running this prompt here. 
This helps others see what good looks like.

## Notes
- Replace [PASTE REQUEST HERE] with the actual feature request
- The more specific your north star metric the better the output
- Push back on the recommendation if it doesn't feel right — 
iterate until it does
