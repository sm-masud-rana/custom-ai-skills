---
name: prompt-optimizer
description: Improve any AI prompt by clarifying the goal, adding role and context, specifying format and constraints, and removing ambiguity — returning a stronger, reusable prompt.
---

# Prompt Optimizer

## Purpose
Take a rough prompt and rewrite it into a clear, structured, high-performing prompt that gets better results.

## Instructions
1. Identify the user's real goal behind the prompt.
2. Add a clear role or persona for the AI where it helps.
3. Add the missing context, inputs, and constraints.
4. Specify the desired output format (length, structure, tone).
5. Remove vague or conflicting wording.
6. Return two things: (a) the optimized prompt, and (b) a short note on what you improved.
7. Keep the prompt reusable with placeholders like [TOPIC] and [AUDIENCE].

## Example
**Input:** `write a post about marketing`

**Agent behavior:** Returns a structured prompt with a role, context, and output format, plus a short note explaining the improvements.

See `sample-conversations.md` for more examples.
