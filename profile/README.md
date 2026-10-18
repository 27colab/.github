# 27 Colab

Small, tested TypeScript building blocks for AI agents, extracted from real client work. Each package is MIT licensed, runs its tests offline with fakes (no keys or accounts), and comes with a write-up of the problem it solves and where it still falls short.

| Package | What it is |
|---|---|
| [`voice-engine`](https://github.com/27colab/voice-engine) | A WebSocket-based AI phone agent that sounds human: turn-taking, barge-in, and knowing what the caller actually heard. |
| [`sms-consent`](https://github.com/27colab/sms-consent) | An SMS agent that only texts people who said yes: consent state machine, STOP in any language, one send guard. Not legal advice. |
| [`instagram-dm`](https://github.com/27colab/instagram-dm) | An Instagram DM auto-reply agent on Meta's official API: webhook verification, echo filtering, the 24-hour window. |
| [`email-kit`](https://github.com/27colab/email-kit) | An email agent that sends once and tells the truth: retries, idempotency, suppression, spoken-address read-back. |
| [`quickbooks-online-kit`](https://github.com/27colab/quickbooks-online-kit) | A QuickBooks Online sync engine that keeps its connection alive: safe token rotation and a duplicate-invoice guard. |
| [`fl-parcel-lookup`](https://github.com/27colab/fl-parcel-lookup) | A Florida property-records lookup (Miami-Dade, Broward, Palm Beach): address in, folio and legal description out. |

**Read the engineering write-ups:** [theuxui.dev/open-source](https://theuxui.dev/open-source/) · **Docs:** [docs.27colab.com](https://docs.27colab.com)

These are version 0.x reference implementations, built with Claude Code and directed and reviewed by [Jesus Vasquez](https://www.linkedin.com/in/vasquezjesus). They are not on npm yet, so clone the repository to use one. They make no compliance, performance or production-readiness claims, and they are not affiliated with Twilio, Meta, Intuit or any county.
