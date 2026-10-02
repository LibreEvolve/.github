<p align="center">
  <img src="https://raw.githubusercontent.com/LibreEvolve/.github/main/profile/assets/banner.jpg" alt="Dark navy banner: a glowing emerald lineage tree branches from a single node on the left, most candidate branches fading out, one bright path continuing to the right past faint bin-packing layouts" width="100%">
</p>

<h1 align="center">LibreEvolve</h1>

<p align="center"><b>Evolve code. Show the evidence.</b></p>

An open-source workbench for inspectable code-evolution experiments. The current public release is an engineering preview: bounded Python bin-packing optimization with Codex OAuth.

## What we do

A run starts from a simple Python heuristic, searches a bounded local space of changes, and saves every candidate workspace and evaluation so you can read the evidence yourself. A fresh export check then re-runs the candidate you chose on named training and held-out cases.

## Repositories

| Repository | What it is |
| --- | --- |
| [`libreevolve`](https://github.com/LibreEvolve/libreevolve) | Open-source workbench for inspectable code-evolution experiments on bounded Python bin-packing. Start with the [quickstart](https://github.com/LibreEvolve/libreevolve/blob/main/docs/alpha-quickstart.md) and [safety and scope](https://github.com/LibreEvolve/libreevolve/blob/main/docs/safety.md). MIT license. |
| [`.github`](https://github.com/LibreEvolve/.github) | Organization profile and community health files. |

## Limits

- No improvement is a valid result; a passing named check does not prove correctness, optimality, security or performance.
- Candidate code runs locally with host access. It is not a security sandbox.
- One model lane is documented (Codex OAuth). Native Windows Codex execution and external usability are unvalidated.
- Install is from source; there is no public package-registry release.

<p align="center">
<a href="https://libreevolve.com">Website</a> · <a href="https://github.com/LibreEvolve/libreevolve">Source</a> · <a href="https://github.com/LibreEvolve/.github/blob/main/CONTRIBUTING.md">Contributing</a> · <a href="https://github.com/LibreEvolve/.github/blob/main/SUPPORT.md">Support</a> · <a href="https://github.com/LibreEvolve/.github/blob/main/SECURITY.md">Security</a> · Steward: Complete Tech LLC
</p>
