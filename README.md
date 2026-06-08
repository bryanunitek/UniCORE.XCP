# UniCORE.XCP

**SCAFFOLD-ANCHOR repository — initial scaffold 2026-06-04.**

Full scaffolding, upstream-fork integration, and source-code work all pending a fresh dedicated kickoff arc. This initial commit exists to lock the repository's identity, licence position, and place in the UniCORE Sanity Check fleet so the work cannot be forgotten.

Author: **Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom.**
First commit: **2026-06-04 14:50 UTC.**

---

## What this repository is

`bryanunitek/UniCORE.XCP` is the **XCP** family member: On-prem-deployment-shape public gift surface. Documentation today; source code at certification.

**Family purpose:** Open-source virtualisation platform. Multi-upstream: XCP-ng (Xen-based hypervisor) + Xen Orchestra (management UI).

**Role in UniCORE:** Virtualisation substrate — UniCORE.GVB substrate-services consume XCP-ng + Xen Orchestra to deliver virtualisation on customer-premise hardware and SaaS infrastructure tiers. Bryan's existing production infrastructure runs on XCP-ng across the LA / NJ / UK GVB node fleet.

---

## Upstream

- **Upstream projects:** [xcp-ng](https://github.com/xcp-ng/xcp) + [xen-orchestra](https://github.com/vatesfr/xen-orchestra)
- **Upstream licences:** GPL-2.0 (xcp-ng) + AGPL-3.0 (xen-orchestra)
- **Our relationship:** Fork-and-extend. Upstream codebases are consumed verbatim under their original licences; our code additions carry the same copyleft licences; our documentation additions sit under CC BY 4.0.

This repository tracks multiple upstreams via separate remotes (`upstream-xcp` + `upstream-xo`). The merge discipline that governs how this repository absorbs upstream changes is documented in [`UPSTREAM-MERGE-DISCIPLINE.md`](UPSTREAM-MERGE-DISCIPLINE.md).

---

## Platforms

Windows · Linux · macOS · iOS · Android

---

## Family — the four-repo pattern

UniCORE.XCP is published as a **four-repo family**:

- `bryanunitek/UniCORE.XCP` — public on-prem-deployment-shape gift surface
- `bryanunitek/UniSaaS.UniCORE.XCP` — public SaaS-deployment-shape gift surface
- `bryanunitek/UniCORE.XCP-Claw` (private) — on-prem-shape working repository
- `bryanunitek/UniSaaS.UniCORE.XCP-Claw` (private) — SaaS-shape working repository

**This repository is the `UniCORE.XCP` member of the family.**

Sister repos:

- [`UniSaaS.UniCORE.XCP`](https://github.com/bryanunitek/UniSaaS.UniCORE.XCP)
- `UniCORE.XCP-Claw (private)`
- `UniSaaS.UniCORE.XCP-Claw (private)`

---

## Status

**SCAFFOLD-ANCHOR** as of 2026-06-04 14:50 UTC. See [`STATUS.md`](STATUS.md) for the full status breakdown.

---

## Files in this scaffold commit

- [`README.md`](README.md) — this file
- [`LICENSE.md`](LICENSE.md) — UniCORE additions licence (GPL-2.0/AGPL-3.0 code + CC BY 4.0 docs)
- [`LICENSE.upstream.md`](LICENSE.upstream.md) — verbatim upstream licence (renamed from original `LICENSE`)
- [`README.upstream.md`](README.upstream.md) — verbatim upstream README (renamed)
- [`STATUS.md`](STATUS.md) — scaffold-anchor status
- [`UPSTREAM-MERGE-DISCIPLINE.md`](UPSTREAM-MERGE-DISCIPLINE.md) — canonical merge discipline
- [`AI-AUTHORSHIP.md`](AI-AUTHORSHIP.md) — AI authorship disclosure

---

## Related repositories — UniCORE programme

**Foundation triad (gift, public, CC BY 4.0):**
- [`UniVERSE`](https://github.com/bryanunitek/UniVERSE) — programme
- [`TrueAI`](https://github.com/bryanunitek/TrueAI) — Foundation (Nine Invariants)
- [`UniCORE-AI`](https://github.com/bryanunitek/UniCORE-AI) — reference architecture (12 Levels)

**Implementation reference (deployment-shape pair):**
- [`UniCORE`](https://github.com/bryanunitek/UniCORE) — on-prem-shape
- [`UniSaaS.UniCORE`](https://github.com/bryanunitek/UniSaaS.UniCORE) — SaaS-shape

**Substrate-services layer (deployment-shape pair):**
- [`UniCORE.GVB`](https://github.com/bryanunitek/UniCORE.GVB) — on-prem-shape
- [`UniSaaS.UniCORE.GVB`](https://github.com/bryanunitek/UniSaaS.UniCORE.GVB) — SaaS-shape

**Forked-upstream building blocks:**
- UniCORE.Avalonia family (4 repos) — cross-platform UI
- UniCORE.DNN family (4 repos) — CMS platform
- UniCORE.Asterisk family (4 repos) — telephony
- UniCORE.Jitsi family (4 repos) — video conferencing
- UniCORE.Signal family (4 repos) — secure messaging
- UniCORE.XCP family (4 repos) — virtualisation ← **this family**

---

## Contact

- **Public discussion:** [GitHub Discussions](https://github.com/bryanunitek/UniCORE.XCP/discussions) (public repos only)
- **Private contact / connection request:** [LinkedIn — Bryan Fred](https://www.linkedin.com/in/bryan-fred-02209753/)

---

*Author: Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom. Public. Given, not sold. Irrevocable.*
