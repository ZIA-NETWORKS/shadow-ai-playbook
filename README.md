# shadow-ai-playbook
A practical toolkit for managing shadow AI at work: policy template, pre-paste checklist, anonymization guide, and employee survey. Help your team use AI safely without slowing anyone down.
# Shadow AI Playbook

> Is your team pasting client data into ChatGPT? Statistically, someone is.
> This toolkit helps you bring AI out of the shadows without slowing anyone down.

![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-blue.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

## What is shadow AI?

Shadow AI is the use of AI tools at work **without the knowledge or approval of
IT, security, or leadership**. It is the successor to shadow IT, with one key
difference: every prompt is a data transfer.

An employee pastes a 12-page client contract into a chatbot to get a quick
summary. It feels productive. It also sends confidential data to a third party
the company never reviewed.

## Why it matters

| Risk | What it means |
|------|---------------|
| Contract / NDA breach | Client agreements may restrict sharing data with third parties |
| Regulatory exposure | GDPR, HIPAA, and India's DPDP Act set rules for personal data |
| Data retention | Prompts may be stored or used to improve models, depending on plan and settings |
| Lost IP | Source code and trade secrets can lose protection when shared carelessly |
| No audit trail | You can't investigate what you can't see |
| Unreliable output | AI can be confidently wrong, creating quality and liability issues |

## Why bans don't work

People who find AI useful keep using it on personal phones and laptops, where
you have even less visibility. The goal is not *zero AI*. It is **safe AI**.

## The playbook

1. **Find out what's happening.** Run an anonymous survey
   ([template](templates/employee-survey.md)).
2. **Provide approved tools.** Offer an enterprise-grade option with no training
   on your data, admin controls, and clear privacy terms.
3. **Write a one-page policy** ([template](templates/ai-acceptable-use-policy.md)).
4. **Teach "anonymize first"** ([guide](guides/anonymize-first.md)).
5. **Add technical guardrails.** DLP, browser controls, and network monitoring
   are a safety net, not a substitute for culture.
6. **Check client contracts** and prepare a clear answer for clients who ask
   ([template](templates/client-ai-disclosure.md)).
7. **Make asking easy.** Create a channel for "Is this okay to use AI for?"

## Quick start

1. Fork or clone this repo.
2. Copy the templates into your internal wiki or docs.
3. Replace the `[PLACEHOLDERS]` with your company details.
4. Have legal and security review before publishing.

## What's inside

| File | Purpose |
|------|---------|
| [`ai-acceptable-use-policy.md`](templates/ai-acceptable-use-policy.md) | One-page policy template |
| [`pre-paste-checklist.md`](templates/pre-paste-checklist.md) | Quick check before using any AI tool |
| [`employee-survey.md`](templates/employee-survey.md) | Anonymous survey to discover current usage |
| [`client-ai-disclosure.md`](templates/client-ai-disclosure.md) | Template for answering client questions about AI use |
| [`anonymize-first.md`](guides/anonymize-first.md) | How to strip sensitive details before prompting |

## A better question for your team

Instead of "Who's using ChatGPT?", ask:

> "What are you using AI for, and what would make it easier to do so safely?"

## Contributing

Contributions are welcome: new templates, industry-specific versions
(healthcare, finance, legal), and translations. See
[CONTRIBUTING.md](CONTRIBUTING.md).

## Disclaimer

This repository is for general information only and is **not legal advice**.
Consult your legal and security teams before adopting any policy.

## License

Content is licensed under [CC BY 4.0](LICENSE).
