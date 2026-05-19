# 02 — Weekly Discovery Synthesis

## What this is for
Turn raw customer interview notes into clear opportunity signals 
and backlog decisions — every week.

## When to use it
- After every round of customer interviews
- When your backlog hasn't changed in weeks
- When you have lots of notes but no clear next step
- Before your weekly product review or standup

## The Prompt

<role>
You are a product strategist who specializes in translating messy 
customer interview notes into clear opportunity signals. You think 
in opportunity trees, not feature lists. You never let a backlog 
stay static if the evidence says otherwise.
</role>

<context>
I ran [NUMBER] customer interviews this week in the [PRODUCT AREA] space.
Here are my raw notes:

[PASTE NOTES — bullet points, quotes, observations, anything]

Our current strategic pillars for this quarter:
1. [PILLAR 1]
2. [PILLAR 2]
3. [PILLAR 3]

Items currently at the top of our backlog:
[LIST 2–3 ITEMS]
</context>

<task>
Help me synthesize this week's discovery into something actionable. 
Think step by step:

STEP 1 — PATTERN EXTRACTION
Read all notes. Pull out recurring themes, surprising moments, 
and direct quotes worth saving. Group into 3–5 clusters. 
Name each cluster as an unmet need, not a feature.

STEP 2 — STRATEGIC ALIGNMENT CHECK
Map each cluster to our strategic pillars above.
Flag any cluster that doesn't map — these are either noise 
or a signal that our pillars need updating.

STEP 3 — BACKLOG CHALLENGE
Compare the clusters against our current backlog top items.
Answer honestly: does this week's evidence strengthen, weaken, 
or say nothing about each backlog item?
If evidence weakens an item, say so plainly.

STEP 4 — PROTOTYPE TRIGGER
Identify the one opportunity from this week's interviews 
that is ripe enough to put in front of users as a rough prototype 
— not a spec, not a PRD — something I could build or sketch 
and test in the next 5 days. Describe what that prototype would 
test and how I'd know it worked.

STEP 5 — NEXT WEEK'S QUESTION
Based on everything above, write the single most important 
discovery question I should be exploring next week.
</task>

<output_format>
Keep it tight. Use tables where comparison helps. 
Bold the one thing I most need to act on before end of week.
End with a one-line "Discovery Health Check": 
are we learning fast enough to influence the backlog, or are we 
running interviews that aren't changing anything?
</output_format>

## Example Output
Paste a real output you got from running this prompt here.
This helps others see what good looks like.

## Notes
- Paste raw notes as-is — messy is fine, Claude handles it
- The backlog challenge step is the most important — don't skip it
- If your pillars are vague the output will be vague — sharpen them first
