# STATUS — UniCORE.XCP

**Repository state as of 2026-06-04 14:50 UTC.**

---

## Scaffold-anchor only

This repository exists as a **scaffold anchor**. Its purpose at this moment is to:

1. Reserve the canonical name on `bryanunitek/`.
2. Lock the licence position (GPL-2.0/AGPL-3.0 for code additions matching upstream; CC BY 4.0 for documentation additions).
3. Document the family pattern and upstream relationship in [`README.md`](https://git.unitek-systems.com/UniCORE/UniCORE.XCP/src/branch/main/README.md) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE.XCP/blob/main/README.md)).
4. Document the merge discipline in [`UPSTREAM-MERGE-DISCIPLINE.md`](https://git.unitek-systems.com/UniCORE/UniCORE.XCP/src/branch/main/UPSTREAM-MERGE-DISCIPLINE.md) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE.XCP/blob/main/UPSTREAM-MERGE-DISCIPLINE.md)).
5. Enrol the repository in the **UniCORE Sanity Check fleet** so it cannot be forgotten.

Nothing else is in this initial scaffold commit. Specifically:

- **Upstream codebase IS present** on `main` branch (full history, 493 commits forked at fleet-creation time).
- **No UniCORE additions yet.** No source code modifications, no custom modules.
- **No CI configuration.**

---

## What is queued

1. Author UniCORE-specific additions on the `unicore` branch.
2. Apply the canonical upstream-merge discipline (weekly or per-release cadence).
3. Test fence before every push to `unicore`.

---

## What this initial scaffold DOES guarantee

- The repository is picked up by the next **UniCORE Sanity Check** automatically.
- The licence boundary is documented before any UniCORE code lands.
- The merge discipline is canonical and reusable.
- The four-repo family pattern is locked.

---

*Status owned by: main Claw. Reviewed by: Bryan Fred.*
