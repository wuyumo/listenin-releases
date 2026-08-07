# ListenIn — dictation for bilingual brains

**Hold `fn`, think out loud in English + 中文 mixed, and cleaned-up text lands wherever your cursor is** — Claude Code, Cursor, Mail, Slack, anywhere.

→ **[Download the latest DMG](https://listenin.dev/download)** · [Website](https://listenin.dev) · [FAQ](https://listenin.dev/faq) · [Compare](https://listenin.dev/compare)

## What it does

- **Voice → written text at the cursor.** An LLM cleanup pass removes fillers, repairs sound-alike recognition errors, and formats the result the way you would have typed it.
- **Mixed Chinese–English is the home turf.** 「我用 Claude Code 写了个 component」 comes out exactly like that — no mode switching, technical terms survive.
- **Speaks AI.** A dedicated mode turns rambling into a structured prompt — goal, numbered steps, constraints — and sends it straight to Claude Code or Cursor.
- **Translate & Ask Anything.** Speak in one language and paste in another; or select text in any app and speak an instruction to rewrite it in place.
- **Learns your vocabulary.** Correct a word once and it goes into your personal dictionary.

## Privacy

Speech recognition runs **entirely on-device** (Apple's engine) — audio never leaves the Mac. Only recognized text is sent for cleanup, never stored, never used for training. A fully offline mode (local model via Ollama) and bring-your-own-key are available. See [PRIVACY.md](PRIVACY.md).

## Pricing

Free: 2,000 cleaned words/week, no account. Pro: $12/month or $96/year.

## Requirements

macOS 14.4+ on Apple Silicon. macOS 26 recommended (enables the next-generation recognition engine). Updates ship automatically via Sparkle.
