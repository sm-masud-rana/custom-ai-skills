# Brand Voice Creator

Defines a clear, documented brand voice guide from a short description.

## What it does
Describe your brand and audience, and it returns a voice guide — personality traits, tone, do's and don'ts, "say this, not that" phrases, and a sample paragraph — so all your content sounds consistent.

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
3. Describe your brand — the AI builds the voice guide.

### For OpenClaw
```bash
git clone https://github.com/sm-masud-rana/custom-ai-skills.git
cd custom-ai-skills
cp -r brand-voice-creator ~/openclaw/skills/
```
Restart your OpenClaw agent — the skill will auto-load.

### For Hermes Agent
```bash
wget https://raw.githubusercontent.com/sm-masud-rana/custom-ai-skills/main/brand-voice-creator/SKILL.md
```
Add it to your Hermes agent's skill path and reload.

## How it works
The skill instructs the AI to define personality traits, tone, do's and don'ts, example phrases, and a sample paragraph — turning a rough brand idea into a reusable voice guide.

See [`sample-conversations.md`](sample-conversations.md) for examples.

## Contributing
Pull requests are welcome — sharper instructions or more examples.

## License
MIT — see the repository [LICENSE](../LICENSE).
