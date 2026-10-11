# Rules for assistants working on Claude Bot (claude-bot)

*A pet app by Astra.* Public credit is always **Astra**, never a legal name. Keep work
information (including any employer's name) out of this repo.

Started with Claude Opus 5.5 (`claude-opus-5-5`), 2026-10-09. Record your model name and
version here when you change something substantial.

Original nine-mood art draft added with OpenAI Codex (GPT-6), built-in imagegen, 2026-10-11.

## What this is
A small always-on-top Windows control for Claude with an orange face. See
[docs/plan-20261009.md](docs/plan-20261009.md). Its host is the Friendly Farmer in
`findastra/astras-pet-apps`. The pet's registry entry and art live there, not here.

## Rules
- Follow the Cage's [PET-FILES.md](https://github.com/findastra/astras-pet-apps/blob/main/PET-FILES.md).
- **Original look.** Same features as the Codex/ChatGPT Mini, never its artwork, icons, layout
  or wording.
- **Never commit** API keys, `.env` files or chat history. Chats stay on the PC.
- Fetched or model text goes into the UI as plain text, never as HTML.
- Say plainly what is not done. Update README "Limits" with every change.
- No pushing to `main` without Astra's OK; use a branch and a PR.

## Handoffs
When Astra's request is unclear or sounds like an assignment, check GitHub first: `handoffs/`
here, in `findastra/astras-pet-apps`, and in the other `findastra` repos. Leave a card when work
remains. Format: [skills/handoff/SKILL.md](skills/handoff/SKILL.md).

Desktop appearance revision by OpenAI Codex (GPT-6), 2026-10-11. See desktop-pet-20261011.json; runtime behavior is in astras-pet-apps.
