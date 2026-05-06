# Permis IA Adulte

> Self-contained AI literacy workshop for adults. Drop the markdown file into any chat AI (Claude, ChatGPT, Gemini, Mistral, Copilot) and get a 2h30 guided training. Covers prompting, AI limits, and EU AI Act compliance. Provider-agnostic, no facilitator required.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Language: French](https://img.shields.io/badge/language-FR-blue.svg)](#)
[![EU AI Act](https://img.shields.io/badge/EU_AI_Act-Article_4-green.svg)](https://artificialintelligenceact.eu/)
[![Format](https://img.shields.io/badge/format-single_markdown_file-orange.svg)](#)
[![With love by Zenika](https://img.shields.io/badge/With%20%E2%9D%A4%EF%B8%8F%20by-Zenika-b51432.svg)](https://oss.zenika.com)

---

## What is this?

A complete AI literacy workshop packaged as **a single markdown file**.

The learner copies the file into their preferred chat AI (Claude, ChatGPT, Gemini, Mistral, Copilot, or any other), and the assistant becomes their interactive trainer for 2h30.

No installation. No platform lock-in. No facilitator. No backend.

The thesis is simple: in 2026, the challenge for adult learners is not learning to use AI. It's **unlearning** what they already think it does.

## Why this exists

The EU AI Act fully applies from **August 2, 2026**. Article 4 mandates AI literacy for any organization deploying AI systems. Most existing trainings focus on tool usage. This workshop focuses on **lucid usage** - what the AI does and doesn't do, what the law requires, what the learner commits to.

The pedagogy is inspired by an actual workshop run with 25 fifth-graders (CM2) in 2026. The kids understood instantly because they had nothing to unlearn. Adults arrive with a backpack - this workshop helps sort it.

## Who is it for?

Any adult professional, regardless of:
- job (white collar, field worker, craftsperson, healthcare, education, freelance, in transition)
- hierarchy (manager, individual contributor, no team)
- prior experience with AI (heavy user to total beginner)
- background, language, accessibility needs

The workshop adapts to the learner's profile through built-in instructions to the chat AI.

## How it works

### For learners

1. Open a new conversation in your chat AI of choice
2. Copy the entire content of `PERMIS-IA-ADULTE-AXE2.md` into the chat
3. Send it - the AI becomes your trainer
4. Type `SUIVANT` (or `NEXT`) to progress through modules
5. At the end, you receive your **AI License** + your **Personal Charter**

Total duration: **2h30**, splittable into 5 sessions of 30 min.

### For trainers / consultants

You can use this file as:
- a self-paced asynchronous training to send to clients
- a guided workshop framework you facilitate live
- a baseline you fork and adapt to your industry

The file contains explicit instructions to the chat AI on how to behave as a trainer (`INSTRUCTIONS POUR L'ASSISTANT IA` section). Customize as needed.

## What it covers

### 5 modules

| Module | Duration | Focus |
|---|---|---|
| 1 - Miroir (Mirror) | 30 min | Self-diagnosis: actual usage vs stated beliefs |
| 2 - Déconstruction (Deconstruction) | 30 min | 5 demonstrated AI limits (hallucination, bias, inference, prediction, human choice) |
| 3 - Reconstruction (Reconstruction) | 40 min | 4 prompting patterns: CRAFT, Examples, Reasoning, Guardrails |
| 4 - Conformité (Compliance) | 25 min | EU AI Act articles 4, 13, 14 |
| 5 - Certification | 25 min | 10-question synthesis quiz + Personal Charter |

### Final deliverables

The learner leaves with:
- **AI License** (Permis IA) - certificate with score and 3 rules: VERIFY / CITE / IMAGINE
- **Personal Charter** - 6 written commitments on transparency, verification, decision boundaries, learning, limits, and sharing

## Compatibility

Tested and runnable in:
- Claude (Anthropic)
- ChatGPT (OpenAI)
- Gemini (Google)
- Le Chat (Mistral)
- Copilot (Microsoft)
- Any chat-based assistant capable of following structured instructions

The workshop uses **no external tools, no file system access, no API calls, no artifacts**. Pure conversational text.

## Inclusivity & sensitivity

Built-in safeguards:
- No assumptions about gender, origin, hierarchy, employment status, accessibility needs
- Inclusive writing (gender-neutral French where possible)
- `VOUVOIEMENT` / `TUTOIEMENT` toggle for formal/informal address
- `SKIP MODULE X` to bypass any module
- `PAUSE` / `REPRENDRE` / `ARRÊT` commands
- Emotional withdrawal clause if learner mentions distress
- Accessibility adaptations (cognitive load, dyslexia, screen readers, non-native French speakers)
- Examples cover diverse professional contexts (artisan, healthcare, freelance, retraining, manager, etc.) - no white-collar default

The bias demonstration in Module 2 uses culturally-rooted but human-category-free examples (food, sports) to avoid reinforcing the stereotypes the workshop aims to expose.

## Repository structure

```
.
├── README.md                          # This file
├── CERTIFICATION-IA-ADULTE-AXE2.md    # The workshop file (drop this into any chat AI)
└── docs/
    └── (optional - mockups, demo screens, slide decks)
```

## Roadmap

- [x] **Axe 2 - "Unlearn before you learn"** - released
- [ ] **Axe 3 - "EU AI Act in practice"** - compliance-focused standalone workshop
- [ ] English version of Axe 2
- [ ] Sector-specific forks (healthcare, public sector, education)
- [ ] Train-the-trainer companion guide

## License

This work is released under the [MIT License](LICENSE).

You are free to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of this workshop, including for commercial purposes. Attribution to the original author is appreciated but not legally required - see the LICENSE file for full terms.

## Background

This workshop is the adult-format counterpart of an in-classroom workshop run with 25 fifth-graders (CM2) in 2026. The pedagogical structure (Discover → Experiment → Debate → Certify) is preserved, with an additional first module dedicated to **unlearning** - which kids don't need but adults do.

It is also informed by a corpus of **522 open-ended responses on AI** collected from professionals in career transition at Zenika Academy between 2018 and 2024. 83% of the concerns spontaneously raised by these non-experts overlap with the EU AI Act adopted in 2024 - a finding that supports the workshop's thesis: most adults already have valid intuitions about AI. They just need to organize them.

## Author

**Norbert Nadir** - AI Native Consultant, Zenika
[LinkedIn](https://www.linkedin.com/in/norbert-jeff-nadir/) | [![With love by Zenika](https://img.shields.io/badge/With%20%E2%9D%A4%EF%B8%8F%20by-Zenika-b51432.svg)](https://oss.zenika.com)

## Contributing

Feedback, forks, and pull requests are welcome. If you run this workshop with a group, I'd love to hear what worked and what didn't - open an issue with your feedback.

---

*"AI is not the threat. Failing to reinvent oneself, however, is."*
