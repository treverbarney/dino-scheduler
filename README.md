# Dino Scheduler

**Modern multi-provider scheduling platform with AI conversational booking and MCP. Built from free open-source forks. More abilities than Dino Booking.**

## Base Forks Used

- **Primary base**: [ribato22/nexcal](https://github.com/ribato22/nexcal) (MIT, Next.js 16 + PostgreSQL + Prisma + Docker) — multi-provider booking, payments, WhatsApp, BI dashboard, Google Calendar sync.
- **AI / MCP layer**: Patterns from [Calnode/calnode](https://github.com/Calnode/calnode) (Apache 2.0) — conversational booking + native MCP server.

Single Docker container. Self-hostable. Zero commission.

## Why It's Better Than Dino Booking

| Feature | Dino Booking | Dino Scheduler |
|---------|--------------|----------------|
| Multi-provider booking | Partial | Full provider-aware wizard |
| AI conversational booking | Limited | Plain-English booking on the page + MCP |
| Payments | Partial | Gateway-agnostic + WhatsApp notifications |
| BI / Analytics | Limited | Revenue trends, staff performance dashboard |
| Calendar sync | Basic | Google Calendar + buffer times |
| Roles & cancellation | Basic | OWNER/STAFF roles + 24h reschedule rules |
| Docker / modern stack | Varies | Next.js 16 + Postgres + single container |
| Agent-ready | Limited | Native MCP endpoint for AI agents |

**Extra abilities**: AI-native booking page, MCP for agents, multi-provider focus, built-in analytics, WhatsApp, modern Next.js stack.

## Quick Start

```bash
git clone https://github.com/treverbarney/dino-scheduler.git
cd dino-scheduler
cp .env.production.example .env   # fill Postgres + keys
docker compose up -d
```

## Tech Stack

- Next.js 16 (App Router) + TypeScript
- PostgreSQL + Prisma
- Docker (multi-stage)
- Auth.js
- Tailwind CSS v4
- WhatsApp + Google Meet integration

## Roadmap / Enhancements

- [x] NexCal multi-provider base
- [ ] Calnode-style AI conversational booking + MCP
- [ ] Dino branding
- [ ] Stronger CRM layer
- [ ] Tattoo / service-specific templates
- [ ] Document center integration

## License

MIT — free for personal and commercial use.

---

Part of the Dino Booking family. Modern, multi-provider, and AI-ready.
