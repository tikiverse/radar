# radar

A personal tech radar. Inspired heavily by the [Thoughtworks Technology Radar](https://www.thoughtworks.com/radar) - if you haven't checked that out, please do.

It's never been easier for a single person to run their own software factory, thanks to agentic AI. With this newfound leverage and scale, it's important for individual software engineers to inherit the behaviors of larger software factories (and treat the software factory itself [like a product](https://x.com/rauchg/status/2081123293340520642)).

Thoughtworks is one of the best at this game and I've been following them for more than 10 years. I love what they do with their Technology Radar, and felt the need to recreate this format for myself to share with others.

I highly encourage you to consider it too.

---

Published at [radar.tiki.pub](https://radar.tiki.pub).

## Rings

| Ring | Meaning |
|---|---|
| **Adopt** | Earned a core spot in my stack |
| **Trial** | Using actively, no strong opinion yet |
| **Assess** | Worth spending time to research |
| **Hold** | No further incentive to take action here |

## Rules

1. Nothing goes on the radar that I haven't personally touched.
2. Every entry is dated. Entries move between rings; the dates stay.
3. Assess is cheap on purpose — it's where a shiny new idea goes instead of becoming a weekend project.
4. v0 is a markdown table. It stays a markdown table until the table is genuinely the bottleneck.

## Radar

| Item | Ring | Since | Notes |
|---|---|---|---|
| Claude Code | Adopt | 2026-04 | Primary interface for coding and for the agentOS vault. |
| Obsidian | Adopt | — | Daily notes, weekly/monthly/quarterly reviews. Private by design. |
| Cloudflare Workers | Trial | — | Running a SQLite-backed service on it. |
| restic + Backblaze | Assess | — | Backup snapshots. Caveat: I have never tested a restore. Untested backups are not backups. |
| Healthchecks.io | Adopt | 2026-06 | For cron/job observability — wanting assurance that scheduled intents actually ran. |
| [Hatchet](https://hatchet.run/) | Assess | 2026-07 | Task orchestration. Idea on file: distributed video encoding across a fleet of MacBooks. Parked here deliberately rather than started. |

## Changelog

- **2026-07-30** — Radar created. Seeded with six entries.
