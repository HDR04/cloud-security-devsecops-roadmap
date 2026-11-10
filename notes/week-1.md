# Week 1 — Git, GitHub and project setup

## What I built
- Created the public repo `cloud-security-devsecops-roadmap` with `notes/`, `labs/`, `projects/`, a README in English and a `.gitignore` (`.env`, `*.tfstate`, `.terraform/`, `.venv/`, keys).
- Practised Git before this repo on `HDR04/demo-` ("git learning", 21 Oct 2026) and `HDR04/demo-0` (26 Oct 2026): init, add, commit, push.
- This note was merged via Pull Request from the branch `notes/week-1`.

## What I broke / fixed
- Merge conflicts: practised resolving 3 conflicts, plus `revert` and `cherry-pick`.
- Rule learned: if a key is published by mistake, revoke it immediately — `.gitignore` alone does not fix it.

## What I can explain without notes
- `init / add / commit / push`, branches, Pull Requests, merge conflicts.
- Why a repo needs a `.gitignore` before the first real commit, and what must never be committed (secrets, `.tfstate`, keys).

## Blocked / next step
- Nothing blocked.
- Next: Semaine 2 — Docker and container security (hardened image, non-root user, Trivy scan).
