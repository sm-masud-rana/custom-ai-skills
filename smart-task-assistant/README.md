# Smart Task Assistant

An AI skill that understands your casual, messy, or Banglish instructions and just does the task — no questions, and no need to write perfect English yourself.

## What it does

You type however feels natural (typos or mixed Bangla/English are fine). The AI figures out what you want — a Facebook ad, an email, a caption, a product description, a reply, or a plan — and returns the finished result, ready to copy and use.

## Why?

Most assistants stop and ask "what do you mean?" whenever your message isn't perfect. That is slow and frustrating. This skill makes the AI read your message like a smart human would: understand the intent first, and only ask a question if the request is genuinely ambiguous.

## Compatibility

- ✅ ChatGPT (and Custom GPTs)
- ✅ Google Gemini (Gems)
- ✅ Claude (Projects)
- ✅ OpenClaw (SKILL.md-based skill system)
- ✅ Hermes agent
- ✅ Any agent framework that supports Markdown-based skill/instruction files

## Quick Start

### For ChatGPT / Gemini / Claude
1. Open [`SKILL.md`](SKILL.md) and copy all of its text.
2. Paste it into the AI's custom instructions / system prompt:
   - **ChatGPT** → Explore GPTs → Create → Configure → Instructions
   - **Gemini** → Gem manager → New Gem → Instructions
   - **Claude** → Projects → New Project → Custom instructions
3. Type your request in your own words — the AI does the task.

### For OpenClaw
1. Clone the repository:
   ```bash
   git clone https://github.com/sm-masud-rana/custom-ai-skills.git
   cd custom-ai-skills
   ```
2. Copy this skill into your OpenClaw skills folder:
   ```bash
   cp -r smart-task-assistant ~/openclaw/skills/
   ```
   (Create the folder if it doesn't exist.)
3. Restart your OpenClaw agent — the skill will auto-load from the workspace.

### For Hermes Agent
1. Download the skill file:
   ```bash
   wget https://raw.githubusercontent.com/sm-masud-rana/custom-ai-skills/main/smart-task-assistant/SKILL.md
   ```
2. Add it to your Hermes agent's skill path as per your configuration.
3. Reload your agent.

## How it works

The skill instructs the AI to:
1. Read the whole message — even Banglish, typos, or missing words — and infer the intended task.
2. Detect the task type (ad, email, caption, description, reply, plan).
3. Complete the task directly, using a confidence rule: do it silently when clear, add a one-line note when a detail is assumed, and ask ONE question only when genuinely ambiguous.
4. Reply with polished English by default and never force the user to write English.

See [`sample-conversations.md`](sample-conversations.md) for before/after examples.

## Contributing

Pull requests are welcome — sharper instructions, more task types, or extra examples.

## License

MIT — see the repository [LICENSE](../LICENSE).
