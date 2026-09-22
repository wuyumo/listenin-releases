# ListenIn — AI dictation for Mac, built for bilingual speech

**Hold `fn`, think out loud in English + 中文 mixed, and cleaned-up text lands wherever your cursor is** — Claude Code, Cursor, Terminal, Mail, Slack, anywhere on macOS.

→ **[Download the latest DMG](https://listenin.dev/download)** · [Website](https://listenin.dev) · [FAQ](https://listenin.dev/faq) · [Privacy](https://listenin.dev/privacy)

This repository hosts the release downloads and the Sparkle update feed. The app itself is closed source; bug reports and feature requests are welcome in Issues.

## What it does

- **Voice → written text at the cursor.** An LLM cleanup pass removes fillers, repairs sound-alike recognition errors, and formats the result the way you would have typed it.
- **Mixed Chinese–English is the home turf.** 「我用 Claude Code 写了个 component」 comes out exactly like that — no mode switching, and technical terms survive the switch instead of being translated or transliterated.
- **Speaks AI.** A dedicated key turns rambling into a structured prompt — goal, numbered steps, constraints — and sends it straight to Claude Code or Cursor.
- **Translate & Ask Anything.** Speak in one language and paste in another; or select text in any app and speak an instruction to rewrite it in place.
- **Learns your vocabulary.** Correct a misheard word once and it enters your personal dictionary, with an offer to fix the remaining occurrences in the same field.

## Privacy

Speech recognition is handled by **Apple's speech engine**, not by a ListenIn server — audio never reaches one. On the next-generation on-device path, recognition stays on your Mac; on the classic fallback path Apple may use its speech service, under Apple's privacy policy.

Only the recognized **text** goes to ListenIn's cleanup service, where it is never stored and never used for training. Two ways to remove even that hop: bring your own API key, which sends text straight to the provider you chose, or run cleanup on a local model through Ollama, which keeps everything on the machine.

Full mode-by-mode account in [PRIVACY.md](PRIVACY.md) and at [listenin.dev/security](https://listenin.dev/security).

## Pricing

- **Free** — 8,000 AI-cleaned words per week, forever. No account, no email, no card. Raw dictation without cleanup is unlimited.
- **Pro** — $12/month, $96/year, or $149 once.

## Requirements

macOS 14 or later. Universal build: Apple Silicon and Intel. macOS 26 is recommended — it enables the next-generation on-device recognition engine. Signed with a Developer ID and notarized by Apple. Updates ship automatically through Sparkle.

## How it compares

Honest, sourced comparisons with the other Mac dictation apps — each one also lists where that app beats ListenIn:

- [ListenIn vs Typeless](https://listenin.dev/vs/typeless)
- [ListenIn vs Wispr Flow](https://listenin.dev/vs/wispr-flow)
- [ListenIn vs superwhisper](https://listenin.dev/vs/superwhisper)
- [ListenIn vs MacWhisper](https://listenin.dev/vs/macwhisper)
- [ListenIn vs Aqua Voice](https://listenin.dev/vs/aqua-voice)
- [All of them side by side](https://listenin.dev/compare)

## Support

Open an issue here, or use **Send Feedback** in the menu bar.
