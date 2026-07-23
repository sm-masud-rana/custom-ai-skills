# English Writing Assistant

Fixes your English writing instantly — and never asks questions.

## What it does
Type anything, even with typos or mixed Bangla and English, and it returns a clean version in a simple 4-part format: what's corrected, what you meant, the small fixes, and a better version.

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
3. Type your message — the AI fixes it, no questions asked.

### For OpenClaw
```bash
git clone https://github.com/sm-masud-rana/custom-ai-skills.git
cd custom-ai-skills
cp -r english-writing-assistant ~/openclaw/skills/
```
Restart your OpenClaw agent — the skill will auto-load.

### For Hermes Agent
```bash
wget https://raw.githubusercontent.com/sm-masud-rana/custom-ai-skills/main/english-writing-assistant/SKILL.md
```
Add it to your Hermes agent's skill path and reload.

## How it works
The skill instructs the AI to read the intended meaning from any messy or Banglish input, fix grammar and spelling while keeping the tone, and always reply in a simple 4-part format — never asking a clarifying question.

See [`sample-conversations.md`](sample-conversations.md) for examples.

## Contributing
Pull requests are welcome — sharper instructions or more examples.

## License
MIT — see the repository [LICENSE](../LICENSE).
