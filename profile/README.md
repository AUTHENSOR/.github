---

## We audit the instruments the AI industry measures itself with, and file every fix upstream.

**AUTHENSOR** is an evaluation-integrity research practice. We read
evaluation harnesses, benchmarks, judges, leaderboards, and scoring
pipelines line by line. Findings go to maintainers privately first. Fixes
land in public.

**100+ defect reports** across **40+ organizations** · **20+ fixes landed
upstream** (UK AISI, Microsoft, SWE-bench, and others) · **76 of the first
99 are a single class**: *the evaluator trusts an artifact the evaluated
system controls.*

When an instrument survives the audit, we attest it. **Authenticated
evaluation**: one verified number per category per cycle. Founding cohort
forming now → [authensor.com](https://authensor.com)

---

### Live research artifacts

- **[The 24-of-25 census](https://www.authensor.com/census).** The 25
  most-starred evaluation repositories, read line by line. 24 have an
  evaluator trust boundary defect. The one clean repo validates judge
  output structurally instead of parsing free text, which is exactly what
  the taxonomy prescribes.
- **[The benchmark drift ledger](https://github.com/AUTHENSOR/etb-scan/blob/main/drift/LEDGER.md).**
  54 public benchmark datasets tracked byte by byte. 48 changed under the
  same dataset name. Per-dataset table, raw data, and the repro script.
- **[The taxonomy paper](https://zenodo.org/records/21633620).** The
  Evaluator Trust Boundary: the class, the patterns, the PoCs.

### The tools of the practice

| Repo | What it is |
|---|---|
| [**etb-scan**](https://github.com/AUTHENSOR/etb-scan) | Open scanner for evaluator trust boundaries. Free, MIT, forever. |
| [**etb-taxonomy**](https://github.com/AUTHENSOR/etb-taxonomy) | The rule catalog: one file per rule, stable IDs (ETB-n). |
| [**eval-cert**](https://github.com/AUTHENSOR/eval-cert) | The standard an evaluation must pass to be attested. Mapped to ISO 42001, NIST AI RMF, EU AI Act, OWASP. |
| [**findings**](https://github.com/AUTHENSOR/findings) | Named findings with PoCs, mechanisms, and fixes. |
| [**trust-boundary-demo**](https://github.com/AUTHENSOR/trust-boundary-demo) | Runnable demo of the core mechanism. |

### The audited surface

The ~60 forks on this account are the map: evaluation harnesses, agent
benchmarks, judges, adversarial tooling, and frameworks we've read line by
line. Fork presence means **studied**. Not "endorsed," not "vulnerable."

### The stack

The open, MIT-licensed safety tooling we built to do our job: SafeClaw,
policy engine, scanners, monitors. Free forever, on GitHub and npm. Proof
we ship, and no longer the headline.

---

Research: [zenodo.org/records/21633620](https://zenodo.org/records/21633620) ·
Contact: john@authensor.com
