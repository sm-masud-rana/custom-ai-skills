# Smart Task Assistant

An AI skill that understands your casual, messy, or Banglish instructions and just does the task — no questions, and no need to write perfect English yourself.

## What it does
You type however feels natural (typos or mixed Bangla/English are fine). The AI figures out what you want — a Facebook ad, an email, a caption, a product description, a reply, a plan — and gives you the finished result, ready to copy.

## Compatibility
- ✅ ChatGPT (and Custom GPTs)
- ✅ Google Gemini (Gems)
- ✅ Claude (Projects)
- ✅ OpenClaw (SKILL.md skill system)
- ✅ Hermes agent
- ✅ Any tool that supports Markdown instruction/skill files

## How to use

### 🅰️ Manual way — ChatGPT / Gemini / Claude / any AI
1. Open `SKILL.md` and copy all of its text.
2. Paste it into the AI's custom instructions / system prompt:
   - **ChatGPT** → Explore GPTs → Create → Configure → Instructions
   - **Gemini** → Gem manager → New Gem → Instructions
   - **Claude** → Projects → New Project → Custom instructions
3. Type your request in your own words — the AI does the task.

### 🅱️ Terminal way — OpenClaw / Hermes (agent)
```bash
git clone https://github.com/sm-masud-rana/custom-ai-skills.git
cp -r custom-ai-skills/smart-task-assistant ~/openclaw/skills/
```
Then restart your agent — the skill auto-loads from the workspace.

For **Hermes**, add `SKILL.md` to your agent's skill/instruction path and reload the agent.

## Example
See [`sample-conversations.md`](sample-conversations.md).
