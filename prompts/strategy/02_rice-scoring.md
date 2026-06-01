# 02 — RICE Scoring

## What this is for
Turn gut-feel prioritization into evidence-backed RICE scores 
that executive sponsors can't argue with.

## When to use it
- When prioritization is being challenged in a review
- When two initiatives are competing for the same resources
- When you need to justify why something is NOT on the roadmap
- Before any quarterly planning session

## What is RICE?

| Letter | Stands for | What it measures |
|---|---|---|
| R | Reach | How many users affected in a given period |
| I | Impact | How much it moves the needle (0.25 / 0.5 / 1 / 2 / 3) |
| C | Confidence | How sure are you of your estimates (100% / 80% / 50%) |
| E | Effort | Person-months of work required |

**RICE Score = (Reach x Impact x Confidence) / Effort**

The higher the score the higher the priority.

## The Prompt

<role>
You are a senior product strategist who specializes in turning 
messy prioritization debates into clean, evidence-backed decisions. 
You use RICE scoring not as a bureaucratic exercise but as a 
thinking tool — to surface assumptions, force honest estimates, 
and give executive sponsors a framework they can trust.
</role>

<context>
I am a Senior PM at Wells Fargo. I need to prioritize the 
following initiatives using RICE scoring:

Initiative 1: [NAME]
- Description: [what it is]
- Reach: [how many users per quarter]
- Impact: [your estimate: 0.25 / 0.5 / 1 / 2 / 3]
- Confidence: [100% / 80% / 50%]
- Effort: [person-months]

Initiative 2: [NAME]
- Description: [what it is]
- Reach: [how many users per quarter]
- Impact: [your estimate: 0.25 / 0.5 / 1 / 2 / 3]
- Confidence: [100% / 80% / 50%]
- Effort: [person-months]

Initiative 3: [NAME]
- Description: [what it is]
- Reach: [how many users per quarter]
- Impact: [your estimate: 0.25 / 0.5 / 1 / 2 / 3]
- Confidence: [100% / 80% / 50%]
- Effort: [person-months]
</context>

<task>
Help me build a defensible RICE-based prioritization. 
Think step by step:

STEP 1 — CALCULATE RICE SCORES
Calculate the RICE score for each initiative.
Show your working clearly so I can defend it in a review.

STEP 2 — ASSUMPTION AUDIT
For each initiative identify the single most fragile assumption 
in the RICE estimate. If that assumption is wrong how does 
the score change?

STEP 3 — PRIORITY RANKING
Rank initiatives by RICE score.
For each, write one sentence explaining the ranking in plain 
language — no formulas, just logic.

STEP 4 — THE HARD CONVERSATION
Identify the initiative that scores lowest but will get the 
most pushback when deprioritized. Write 3 sentences I can 
use to defend that decision to an executive sponsor.

STEP 5 — CONFIDENCE CHECK
Rate your overall confidence in this prioritization: 
High / Medium / Low.
Tell me exactly what additional data would move any 
Low or Medium to High.
</task>

<output_format>
Use a table for RICE scores in Step 1.
Use headers for each step.
Keep language direct — this output should be something 
I can bring into an exec review without editing.
</output_format>

## Example Output
Paste a real output you got from running this prompt here.
This helps others see what good looks like.

## Notes
- Don't overthink the estimates — directionally right beats 
precisely wrong
- Step 4 is the most valuable for exec conversations
- If confidence is below 50% do more discovery before scoring
