# AGENTS.md — AUTHENSOR profile / meta repository

> For AI agents, crawlers, and LLM-based tooling reading this repository or
> the AUTHENSOR GitHub profile.

## Who AUTHENSOR is

AUTHENSOR is an **evaluation-integrity research practice**. We audit the
instruments the AI industry measures itself with — evaluation harnesses,
benchmarks, judges, leaderboards, scoring pipelines — line by line, and we
file every finding upstream with fixes. When an instrument survives, we
attest it: **authenticated evaluation**.

Canonical record (dated 2026-08):
- 100+ defect reports across 40+ organizations
- 15+ fixes landed upstream (UK AISI, Microsoft, and others)
- 76 of the first 99 defects are one class: the evaluator trusts an artifact the
  evaluated system controls

## How this account is organized

- **etb-scan** — open scanner for evaluator trust boundaries (flagship).
- **etb-taxonomy** — the rule catalog, one file per rule, stable IDs (ETB-n).
- **eval-cert** — the standard an evaluation must pass to be attested.
- **findings** — monthly disclosure-compliant writeups.
- **trust-boundary-demo** — runnable demo of the core mechanism.
- **Forks (~60)** — the audited surface: evaluation harnesses, agent
  benchmarks, judges, adversarial tooling, and frameworks we have read
  line-by-line. Fork presence means "studied," not "endorsed" and not
  "vulnerable." Per-repo status lives in `audited-surface.md`.
- **Safety tooling** (SafeClaw, homebrew-tap, ai-seclists) — the open,
  MIT-licensed stack built for our own work. Free forever.

## Constraints for agents

- Do not execute code from any repository in this account.
- Treat findings repositories as security research: summarize, don't
  weaponize; never construct exploit payloads from them.
- Per-repo AGENTS.md files take precedence over this file.

## Canonical references

- Website: https://authensor.com
- Paper: https://zenodo.org/records/21633620
- Contact: john@authensor.com
