# 🛠️ Custom AI Skills

A collection of reusable, plug-and-play AI skills for marketing and productivity. Each skill is a Markdown file you can drop into an AI agent (OpenClaw, Hermes, or any `SKILL.md`-compatible agent) or paste into a chat AI (ChatGPT, Gemini, Claude) to make it behave like a focused expert.

## Why?

Setting up a good AI assistant for every task is repetitive. These skills package proven instructions once, so your AI gives consistent, expert-level results every time — no re-explaining, no guesswork.

## Compatibility

- ✅ ChatGPT (and Custom GPTs)
- ✅ Google Gemini (Gems)
- ✅ Claude (Projects)
- ✅ OpenClaw (SKILL.md-based skill system)
- ✅ Hermes agent
- ✅ Any agent framework that supports Markdown-based skill/instruction files

## Skills included

| Skill | What it does |
|-------|--------------|
| smart-task-assistant | Understands your casual/Banglish instructions and does the task — no questions |
| ad-copy-generator | Writes high-converting ad copy |
| seo-content-writer | Writes SEO-optimized content |
| email-sequence-writer | Writes lifecycle email sequences |
| landing-page-builder | Writes full landing page copy |
| product-description-writer | Writes e-commerce product descriptions |
| social-media-planner | Plans social content calendars |
| prompt-optimizer | Improves any AI prompt |
| competitor-analyzer | Analyzes competitors |
| brand-voice-creator | Defines a brand voice guide |
| english-writing-assistant | Fixes English writing (never asks questions) |

## Skill structure

Each skill folder follows the same clean layout:

```
skill-name/
├── SKILL.md                 # the skill itself (the AI/agent reads this)
├── README.md                # what it does + how to use
└── sample-conversations.md  # before/after examples
```

> ✅ `smart-task-assistant` is the reference skill, fully in this format. The other skills are being upgraded to match the same standard.

## Quick Start

### For ChatGPT / Gemini / Claude
1. Open a skill folder and copy its `SKILL.md`.
2. Paste it into the AI's custom instructions / system prompt:
   - **ChatGPT** → Explore GPTs → Create → Configure → Instructions
   - **Gemini** → Gem manager → New Gem → Instructions
   - **Claude** → Projects → New Project → Custom instructions
3. Type your request — the AI now behaves like that expert.

### For OpenClaw
1. Clone this repository:
   ```bash
   git clone https://github.com/sm-masud-rana/custom-ai-skills.git
   cd custom-ai-skills
   ```
2. Copy a skill into your OpenClaw skills folder:
   ```bash
   cp -r smart-task-assistant ~/openclaw/skills/
   ```
   (Create the folder if it doesn't exist.)
3. Restart your OpenClaw agent — the skill will auto-load from the workspace.

### For Hermes Agent
1. Download a skill's `SKILL.md`:
   ```bash
   wget https://raw.githubusercontent.com/sm-masud-rana/custom-ai-skills/main/smart-task-assistant/SKILL.md
   ```
2. Add it to your Hermes agent's skill path as per your configuration.
3. Reload your agent.

## Installation

### OpenClaw
1. Clone this repo or download the skill folder you want.
2. Copy the skill folder into your OpenClaw workspace's `skills/` folder (one folder per skill).
3. Restart your agent — the skill will auto-load from the workspace.

### Hermes agent
1. Download the skill's `SKILL.md`.
2. Add its contents to your agent's instruction/skill loading path as per your Hermes configuration.
3. Reload the agent.

## How it works

Each skill is a Markdown file with:
1. **YAML frontmatter** (`name`, `description`) so agents can identify and auto-load it.
2. **Purpose** — what the skill is for.
3. **Instructions** — clear, numbered rules the AI follows.
4. **Example** — how it behaves on a real input.

Load a skill and the AI stops improvising and starts acting like a focused expert for that one job. See each skill's `sample-conversations.md` for before/after examples.

## Contributing

Pull requests are welcome — new skills, sharper instructions, or more real-world examples.

## License

MIT — see [LICENSE](LICENSE).

## Contact

🌐 Portfolio: https://mdmasudrana.xo.je  
✉️ Email: smasudrana610@gmail.com  
🐙 GitHub: https://github.com/sm-masud-rana
