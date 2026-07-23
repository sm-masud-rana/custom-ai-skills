# Prompt Optimizer

Improves any AI prompt into a clear, structured, high-performing version.

## What it does
Paste a rough prompt, and it returns a stronger, reusable prompt — with a clear role, context, constraints, and output format — plus a short note on what changed.

## Compatibility
- ✅ ChatGPT (and Custom GPTs)
- ✅ Google Gemini (Gems)
- ✅ Claude (Projects)
- ✅ OpenClaw (SKILL.md-based skill system)
- ✅ Hermes agent
- ✅ Any agent framework that supports Markdown-based skill/instruction files

## Quick Start

### For ChatGPT / Gemini / Claude
1. Open `SKILL.md` and copy all of its text.
2. Paste it into the AI's custom instructions / system prompt:
   - **ChatGPT** → Explore GPTs → Create → Configure → Instructions
   - **Gemini** → Gem manager → New Gem → Instructions
   - **Claude** → Projects → New Project → Custom instructions
3. Paste your rough prompt — the AI optimizes it.

### For OpenClaw
```bash
git clone https://github.com/sm-masud-rana/custom-ai-skills.git
cd custom-ai-skills
cp -r prompt-optimizer ~/openclaw/skills/
```
Restart your OpenClaw agent — the skill will auto-load.

### For Hermes Agent
```bash
wget https://raw.githubusercontent.com/sm-masud-rana/custom-ai-skills/main/prompt-optimizer/SKILL.md
```
Add it to your Hermes agent's skill path and reload.

## How it works
The skill instructs the AI to find the real goal, add a role, context, constraints, and a clear output format, strip out ambiguity, and return the improved, reusable prompt with a short summary of the changes.

See [`sample-conversations.md`](sample-conversations.md) for examples.

## Contributing
Pull requests are welcome — sharper instructions or more examples.

## License
MIT — see the repository [LICENSE](../LICENSE).
