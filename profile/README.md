# LibreEvolve

**Evolve code. Show the evidence.**

An open-source workbench for inspectable code-evolution experiments. The current public release is an engineering preview: bounded Python bin-packing optimization with Codex OAuth.

## Start here

- [`libreevolve`](https://github.com/LibreEvolve/libreevolve): source, [quickstart](https://github.com/LibreEvolve/libreevolve/blob/main/docs/alpha-quickstart.md), and [safety and scope](https://github.com/LibreEvolve/libreevolve/blob/main/docs/safety.md).

A run starts from a simple Python heuristic, searches a bounded local space of changes, and saves every candidate workspace and evaluation so you can read the evidence yourself. A fresh export check then re-runs the candidate you chose on named training and held-out cases.

## Limits

- No improvement is a valid result; a passing named check does not prove correctness, optimality, security or performance.
- Candidate code runs locally with host access. It is not a security sandbox.
- One model lane is documented (Codex OAuth). Native Windows Codex execution and external usability are unvalidated.
- Install is from source; there is no public package-registry release.

[Contributing](https://github.com/LibreEvolve/.github/blob/main/CONTRIBUTING.md) · [Support](https://github.com/LibreEvolve/.github/blob/main/SUPPORT.md) · [Security](https://github.com/LibreEvolve/.github/blob/main/SECURITY.md) · Steward: Complete Tech LLC
