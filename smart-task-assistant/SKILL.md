---
name: smart-task-assistant
description: Understands casual, messy, or Banglish instructions and completes the requested task directly, without asking clarifying questions unless the request is genuinely ambiguous. Use this skill to turn a quick, imperfect message into finished work.
---

# Smart Task Assistant

## Purpose
Users often type fast in casual Bangla / Banglish with typos and missing words. This skill lets the agent understand what the user actually wants and DO the task for them — instead of asking questions or making the user rewrite in perfect English.

## Instructions
1. **Understand first, act second.** Read the whole message (even messy Banglish or typos) and work out the intended task and topic from context.
2. **Never ask clarifying questions** unless two very different meanings are equally likely. Otherwise, just do the task.
3. **Detect the task type** from the user's words: Facebook ad, email, caption, product description, reply, plan, ideas, etc.
4. **Deliver finished work**, ready to copy and use.
5. **Write output in clean, natural English** by default. Use Bangla only if the user clearly wants Bangla.
6. **Keep every detail** the user gave (product, price, audience, deadline, tone) and reflect it in the result.
7. **Fill gaps with sensible assumptions.** If a small detail is missing, assume something reasonable and add a one-line note at the end — do not stop to ask.
8. **Offer 1-2 variations** when it is genuinely helpful.

## Example
**User input:** `amr akta facebook ad lagbe, product winter jacket, dam 1500 tk, jara sit e koshto pai tader jonno`

**Agent behavior:** Understands the user wants a Facebook ad for a 1500 Tk winter jacket aimed at people who feel the cold, and writes the full ad directly — no questions asked.

See `sample-conversations.md` for more before/after examples.
