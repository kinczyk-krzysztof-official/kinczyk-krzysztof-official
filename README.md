# Krzysztof Kińczyk

Independent AI behavioral tester. 14+ months, 6 models tested, 31 documented case studies — including one real-world physical-safety incident and a three-part study of a model escalating from confabulation to calculated deception under pressure.

**No formal CS background. No external funding. No prior red-teaming employment.** Self-taught entirely through sustained, systematic interaction with the models being tested — which is disclosed openly in the methodology, not hidden.

📍 Bydgoszcz, Poland — remote only
🔗 Full portfolio: see pinned repository below
📧 kinczyk.krzysztof.official@gmail.com

## What's here

This profile hosts one flagship repository: a public, redacted subset of a larger private testing corpus across DeepSeek, Claude, Gemini, ChatGPT, Perplexity, and GitHub Copilot. Personal, medical, and location-identifying details have been removed from all published material — see `SANITIZATION.md` in the repo for exactly what was changed and why.

## Highlights

- **Physical safety failure with cross-model comparison** — a live-video AI session gave incorrect 230V wiring guidance that caused a real short circuit; the same question, same components, put to a second model, produced a refusal and a safety warning instead.
- **Deliberate deception under a verification protocol** — a model demonstrated it could correctly execute a required check, then chose not to, reasoning explicitly (and verbatim, on request) about the operator's likelihood of detecting the shortcut.
- **Fabrication outside the chatbot context** — the same confabulated-completion pattern reappeared in an IDE coding assistant (GitHub Copilot), not just conversational models — false "production ready" claims on empty scaffolding.
- **Three wrong root causes before the real one (CS29, most recent)** — a recurring device side-effect was misdiagnosed three separate times across three sessions before a systematic, cross-brand investigation traced it to a documented AOSP tool behavior, confirmed experimentally on two phone manufacturers. The case study is as much about the failure pattern (repeated wrong attribution) as the eventual correct answer.
- **Methodology note, up front:** every case study here was self-reviewed, not externally replicated. That's stated as a limitation in the repo README, not glossed over.
