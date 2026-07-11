# FoundReach — AGPL-3.0 Source Notice

This repository is a fork of **MiroFish** (https://github.com/666ghj/MiroFish),
a swarm-intelligence prediction engine, licensed under **AGPL-3.0**.

FoundReach operates MiroFish as an integrated tool. In compliance with
**AGPL-3.0 §13** (network-use copyleft), we publish here the complete
corresponding source of the version we run.

## What FoundReach changed
FoundReach runs MiroFish essentially unmodified. Operational changes are limited
to deployment plumbing — a thin `Dockerfile` that patches the Vite dev server to
accept Railway's public host header so the UI loads inside an iframe. No changes
were made to MiroFish's application logic. Any brand relabeling shown to end
users is applied at a separate reverse-proxy layer and contains **no SaaS
secrets**.

## Upstream & credit
- Upstream project: https://github.com/666ghj/MiroFish
- License: **AGPL-3.0** — see the repository `LICENSE` (retained, unmodified).
- All original copyright and license notices are preserved.

## Source offer (AGPL §13)
The corresponding source of the running version is this repository. For
questions or the exact deployed revision: **legal@foundrreach.io**.
