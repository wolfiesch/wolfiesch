<!--
  GitHub profile README — lives at github.com/wolfiesch/wolfiesch, file README.md at root.
  Star and merged-PR counts are live shields.io badges, so they do not need manual refreshes.
-->

<div align="center">

# Hi, I'm Wolfie

### Ex-PwC Deals, now building developer tools in Rust, Python & TypeScript.

Making spreadsheets fast and AI agents useful.

<br>

[![Website](https://img.shields.io/badge/wolfie.gg-000000?style=for-the-badge&logo=safari&logoColor=white)](https://wolfie.gg)
&nbsp;
[![X](https://img.shields.io/badge/@wolfie__-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/wolfie_)
&nbsp;
[![Resume](https://img.shields.io/badge/resume-000000?style=for-the-badge&logo=readdotcv&logoColor=white)](https://resume.wolfie.gg)

<sub>San Francisco &nbsp;·&nbsp; Open to new opportunities</sub>

</div>

---

## Office files, edited in place

**[WolfXL](https://github.com/SynthGL/wolfxl-oss)** · Rust 🦀 + Python 🐍 · [wolfxl.com](https://wolfxl.com)
An openpyxl alternative with a Rust backend. Edit existing `.xlsx` and `.xlsm` files without losing formatting, charts, or macros, and recalculate common formulas without Excel. **6.7–12× faster than openpyxl** on the [committed read/write benchmark](https://github.com/SynthGL/wolfxl-oss/blob/main/benchmarks/results/2026-10-27-ecosystem-full-linux-epyc.md). One import change:

```diff
- from openpyxl import load_workbook, Workbook
+ from wolfxl   import load_workbook, Workbook
```

**[WolfPPT](https://github.com/wolfiesch/wolfppt-oss)** · Rust 🦀 + Python 🐍 · [wolfppt.com](https://wolfppt.com)
A python-pptx alternative for editing existing PowerPoint decks. Change text, tables, and chart data while themes, layouts, masters, and every part you did not touch stay byte-for-byte identical.

**[WolfDocx](https://github.com/wolfiesch/wolfdocx-oss)** · Python 🐍 · [wolfdocx.com](https://wolfdocx.com)
A python-docx alternative for editing existing Word documents in place. Find and replace across runs, edit tables, sections, and styles, and keep every untouched part byte-for-byte identical. Pure Python, MIT licensed.

**ExcelWorlds** · Rust 🦀 + Python 🐍 · [public receipts](https://share.wolfie.gg/excelworlds)
An RL environment for formula repair in real workbook programs, built on WolfXL: forkable hidden state, per-step reward ledgers, and a Gymnasium-compatible vector API. Source is private.

## Tools for coding agents

**[omp-best-of](https://github.com/wolfiesch/omp-best-of)** ![stars](https://img.shields.io/github/stars/wolfiesch/omp-best-of?style=flat&label=stars&color=yellow) · `TypeScript`
Best-of-N coding agents for Oh My Pi. Candidates run in isolated workspaces, a verifier ranks their full trajectories, and only the winning patch is applied.

**[agenttab](https://github.com/wolfiesch/agenttab)** · `TypeScript`
Drive a real, logged-in Chrome profile from local scripts through a Native Messaging bridge, with no remote-debugging prompt. Navigation, tabs, waits, screenshots, extraction, and forms.

**[omp-episodic-memory](https://github.com/wolfiesch/omp-episodic-memory)** · `TypeScript`
Hybrid semantic + keyword search over Oh My Pi session transcripts, so your agent remembers across sessions.

**[spreadsheet-peek](https://github.com/wolfiesch/spreadsheet-peek)** · `TypeScript`
Agent-agnostic skill that lets AI coding agents preview spreadsheets with token-efficient fallbacks, powered by WolfXL peek.

## Maps

**[sf-parking-heatmap](https://github.com/wolfiesch/sf-parking-heatmap)** ![stars](https://img.shields.io/github/stars/wolfiesch/sf-parking-heatmap?style=flat&label=stars&color=yellow) · `TypeScript` · [live map](https://sfparking.wolfie.gg)
Temporal heatmap of SF metered parking: typical-week occupancy from 206M+ meter transactions, with bike-share and isochrone overlays.

---

## Open source I contribute to

**[Orca](https://github.com/stablyai/orca)** ![stars](https://img.shields.io/github/stars/stablyai/orca?style=flat&label=stars&color=yellow) [![merged PRs](https://img.shields.io/github/issues-search?query=repo%3Astablyai%2Forca%20author%3Awolfiesch%20is%3Apr%20is%3Amerged&label=my%20merged%20PRs&color=8250df)](https://github.com/stablyai/orca/pulls?q=is%3Apr+is%3Amerged+author%3Awolfiesch)
Run a fleet of coding agents with your own subscription, on desktop, mobile, and remote runtimes. I profiled a 7.3-second file-explorer freeze and cut its refresh path from O(N²) to O(N), fixed rich-text browser automation, and hardened local and remote runtime ownership.

**[Oh My Pi](https://github.com/can1357/oh-my-pi)** ![stars](https://img.shields.io/github/stars/can1357/oh-my-pi?style=flat&label=stars&color=yellow) [![merged PRs](https://img.shields.io/github/issues-search?query=repo%3Acan1357%2Foh-my-pi%20author%3Awolfiesch%20is%3Apr%20is%3Amerged&label=my%20merged%20PRs&color=8250df)](https://github.com/can1357/oh-my-pi/pulls?q=is%3Apr+is%3Amerged+author%3Awolfiesch)
Highly regarded CLI agent harness. My work centers on agent-loop reliability (bounded RPC output, lossless paged transport, oversized tool results spilled to artifacts), native performance (memory-recall vector kernels and diffs in native code), and subagent orchestration.

<sub>Also merged upstream: [CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI/pulls?q=is%3Apr+is%3Amerged+author%3Awolfiesch) (model registry) and [umya-spreadsheet](https://github.com/MathNya/umya-spreadsheet/pulls?q=is%3Apr+is%3Amerged+author%3Awolfiesch) (hyperlink unescaping).</sub>
