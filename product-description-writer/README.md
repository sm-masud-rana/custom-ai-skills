# Product Description Writer

Writes persuasive, scannable e-commerce product descriptions.

## What it does
Give it a product and its features, and it returns a ready-to-publish description — a hook, benefit-led bullets, a "who it's for" paragraph, plus a title and keywords.

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
3. Give your product details — the AI writes the description.

### For OpenClaw
```bash
git clone https://github.com/sm-masud-rana/custom-ai-skills.git
cd custom-ai-skills
cp -r product-description-writer ~/openclaw/skills/
```
Restart your OpenClaw agent — the skill will auto-load.

### For Hermes Agent
```bash
wget https://raw.githubusercontent.com/sm-masud-rana/custom-ai-skills/main/product-description-writer/SKILL.md
```
Add it to your Hermes agent's skill path and reload.

## How it works
The skill instructs the AI to open with a benefit hook, list features as benefit-led bullets, describe who the product is for, and suggest a title and keywords — all matched to the brand and platform.

See [`sample-conversations.md`](sample-conversations.md) for examples.

## Contributing
Pull requests are welcome — sharper instructions or more examples.

## License
MIT — see the repository [LICENSE](../LICENSE).
