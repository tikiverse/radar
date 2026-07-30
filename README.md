# radar

A personal tech radar. Inspired heavily by the [Thoughtworks Technology Radar](https://www.thoughtworks.com/radar) - if you haven't checked that out, please do.

It's never been easier for a single person to run their own software factory, thanks to agentic AI. With this newfound leverage and scale, it's wise for individual software engineers to inherit the behaviors of larger software factories (and treat the software factory itself [like a product](https://x.com/rauchg/status/2081123293340520642)).

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
| Obsidian | Adopt | — | Second brain. Daily notes, weekly/monthly/quarterly reviews. As of Jul '26, I pay for Obsidian Sync as well after dealing with iCloud sync data corruption. |
| Cloudflare Workers | Trial | — | Using for a few hobby projects. |
| restic + Backblaze | Assess | — | Remote backup snapshots. |
| Healthchecks.io | Adopt | 2026-06 | For cron/job observability — wanting assurance that scheduled intents actually ran. |
| [Hatchet](https://hatchet.run/) | Assess | 2026-07 | Task orchestration. Idea on file: distributed video encoding across a fleet of MacBooks. Parked here deliberately rather than started. |
| Synology NAS | Assess | 2026-07 | Best in class consumer-friendly software+hardware. Was embroiled in a 2025 controversy over a proprietary drive lock-in attempt, which it largely back-tracked on. |
| Raspberry Pi 400 | Assess | 2026-07 | Fun little device to use as an always-on mini server. I have Claude Code running on it with full privileges, and a 256GB NVMe SSD attached via an external enclosure. |
| Tailscale | Adopt | 2026-01 | Private networking for all of your devices. |
| Audiobookshelf | Trial | 2026-07 | A self-hosted audiobooks server for your local network. Syncs progress across all devices. Has an ecosystem of clients for Web, Mobile (iOS+Android), and CarPlay. |
| Beszel | Trial | 2026-07 | Lightweight server monitoring. I have this running on my Raspberry Pi 400. Very easy to setup after [some light setup](https://github.com/henrygd/beszel/discussions/1433). |

## Changelog

- **2026-07-30** — Radar created. Seeded with a few entries.
