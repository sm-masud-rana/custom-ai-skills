# Social Media Planner

Plans social media content calendars with post ideas, captions, and hashtags.

## What it does
Tell it your brand, platform, and goal, and it returns a ready-to-post calendar — a balanced content mix, a day-by-day table, sample captions, and hashtags.

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
3. Describe your brand and goal — the AI builds the plan.

### For OpenClaw
```bash
git clone https://github.com/sm-masud-rana/custom-ai-skills.git
cd custom-ai-skills
cp -r social-media-planner ~/openclaw/skills/
```
Restart your OpenClaw agent — the skill will auto-load.

### For Hermes Agent
```bash
wget https://raw.githubusercontent.com/sm-masud-rana/custom-ai-skills/main/social-media-planner/SKILL.md
```
Add it to your Hermes agent's skill path and reload.

## How it works
The skill instructs the AI to balance the content mix, lay out a day-by-day calendar, and write ready captions with hooks and hashtags — all in a consistent brand voice.

See [`sample-conversations.md`](sample-conversations.md) for examples.

## Contributing
Pull requests are welcome — sharper instructions or more examples.

## License
MIT — see the repository [LICENSE](../LICENSE).
