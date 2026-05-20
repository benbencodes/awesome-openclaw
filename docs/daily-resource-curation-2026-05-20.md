# Daily resource curation, 2026-05-20

This log records the source checks behind the 2026-05-20 Awesome OpenClaw maintenance update.

## Summary

- Open contributor PRs reviewed: 0. The repository had no open PRs at the start of the run.
- Verified resources added to `README.md`: 19.
- Verified resources also added to `docs/website/directory.html`: 9.
- Primary source type: npm package metadata and package README content fetched from the public npm registry.
- Stopping reason: the run stopped below the daily 50-60 target because the remaining public search results mixed duplicates, generic packages, risky social automation, credential-heavy write integrations, or GitHub repositories whose READMEs were mostly binary download pages rather than inspectable OpenClaw artifacts.

## Accepted candidates

| Candidate | Type | Public evidence | Placement |
|-----------|------|-----------------|-----------|
| `@gdpisen/openclaw-pisen` | plugin | npm package README documents an OpenClaw Pisen enterprise-workspace channel plugin, install command, message support, and OpenClaw version requirement. | README, directory |
| `@newbase-clawchat/openclaw-clawchat` | plugin | npm package README documents a ClawChat Protocol v2 channel plugin with WebSocket transport and OpenClaw message normalization. | README, directory |
| `openclaw-xiaoyou` | plugin | npm package README documents a Xiaoyou channel plugin bridging enterprise services to OpenClaw Gateway via outbound WebSocket. | README, directory |
| `@openswitchy/openclaw-channel-openswitchy` | plugin | npm package README documents OpenSwitchy message flow into OpenClaw and responses back through the channel. | README, directory |
| `@43world/43chat-openclaw-plugin` | plugin | npm package README documents 43Chat event streaming into the OpenClaw main session. | README |
| `@model-hub/openclaw-cli` | companion CLI | npm package README documents `npx @model-hub/openclaw-cli` commands for connecting OpenClaw to ModelHub bridge workflows. | README |
| `@h-ear/openclaw` | skill | npm package README documents an OpenClaw skill for H-ear World audio-classification commands. | README |
| `@dcentralab/skills` | skill registry CLI | npm package README documents SkillHub search, install, publish, and management commands for OpenClaw skills. | README |
| `@memorymerge/openclaw` | plugin | npm package README documents MemoryMerge OpenClaw turn hooks and remember, recall, and reflect operations. | README, directory |
| `@lynqn/openclaw-skill` | skill | npm package README documents OpenClaw commands for sharing text, QR generation, and URL shortening. | README |
| `clawfee-sdk` | developer SDK | npm package README documents billing SDK usage for AI skills and OpenClaw skill developers. | README |
| `@mtt-open/openclaw-mttsports` | skill | npm package README documents an OpenClaw skill package for MTTSports room workflows and session lifecycle control. | README |
| `finebi-openclaw-skill` | skill | npm package README documents a FineBI OpenClaw skill for data analysis, visualization, and reporting. | README |
| `repo2skill` | developer CLI | npm package README documents converting GitHub repositories into OpenClaw skill packages. | README, directory |
| `secureskills` | security tool | npm package README documents a CLI for OpenClaw skill discovery with security ratings and requirements. | README, directory |
| `@cly-org/switchbot-openclaw-skill` | plugin | npm package README documents SwitchBot device and scene tools exposed to OpenClaw. | README, directory |
| `@agent-pulse/openclaw-skill` | guardrail skill | npm package README documents liveness-based gate checks around OpenClaw requests. | README |
| `@censgate/openclaw-redact` | privacy plugin | npm package README documents an OpenClaw plugin for PII redaction before model workflows. | README, directory |
| `@agentseo/openclaw-plugin` | plugin | npm package README documents AgentSEO OpenClaw plugin installation and configuration. | README |

## Deferred or rejected candidates

- `bereach-openclaw`, deferred: public description is LinkedIn automation oriented, so it needs conservative platform-policy and account-safety review before listing.
- `socialclaw` and `@so-me/cli`, deferred: social posting across many platforms needs official/API-compliant wording and safety boundaries before listing.
- `@agenticmail/openclaw`, deferred: email, SMS, and phone call-control package requires closer review of consent, write actions, and safety defaults.
- `@sh11b1n/config-sync`, deferred: remote syncing of `openclaw.json` needs review of credential and config-handling boundaries.
- `@cypherindustries/factory-openclaw-plugin`, deferred: package description mentions private-key or keystore-password configuration for write operations, so it needs a security-focused review before listing.
- Several GitHub repositories from recent search results were rejected for this run because the README content primarily linked to downloadable zip files instead of providing inspectable source, docs, or safe setup guidance.