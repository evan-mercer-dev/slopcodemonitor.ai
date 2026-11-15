<h1 align="center">AI Slop Code Risk Monitor</h1>

<p align="center">
  <strong>Empirical code maintainability, supply-chain, and PR review-friction signals across 7,100+ GitHub repositories</strong><br>
  <a href="https://slopcodemonitor.ai"><strong>Live Dashboard: slopcodemonitor.ai</strong></a>
</p>

---

## Overview

AI-assisted code generation is not inherently a software defect. The engineering challenge for CTOs, CISOs, and Staff Reviewers is maintaining **cognitive ownership**, verifying **unfamiliar dependencies**, controlling **unnecessary abstraction**, and sustaining **pull-request review velocity** at scale.

**SlopCodeMonitor** scans open-source repositories across deterministic static heuristics and maps findings across four governance vectors:

1. **Cognitive Ownership Risk** — deeply nested control flow, silent broad exception handling, and opaque state transitions.
2. **Hallucinated Dependency & Supply-Chain Risk** — unverified package imports and supply-chain surface expansion.
3. **Agent Over-Engineering Ratio** — redundant wrapper layers and boilerplate inflation.
4. **PR Review Velocity Impact** — structural complexity metrics estimating human review effort.

> *Scores are heuristic signals intended to guide human engineering review, not proof of code authorship or security vulnerabilities.*

## Suggest a Repository

Want to see an open-source repository included in the next scan cycle?
👉 [**Open a Repository Suggestion Issue**](https://github.com/evan-mercer-dev/slopcodemonitor.ai/issues/new?title=%5BRepo+Suggestion%5D+&labels=repo-suggestion&body=%23%23+Repository+Suggestion%0A%0A**Repository+URL**%3A+%0A%3E+Paste+the+full+GitHub+URL+here+%28e.g.+https%3A%2F%2Fgithub.com%2Fowner%2Frepo%29%0A%0A**Why+should+we+scan+this+repo%3F**%0A%0A-+%5B+%5D+Popular+%2F+widely+used+project%0A-+%5B+%5D+Suspected+AI-generated+code%0A-+%5B+%5D+Educational+%2F+research+interest%0A-+%5B+%5D+Other%0A%0A**Additional+context+%28optional%29**%3A%0A%0A%3E+Any+extra+details+about+why+this+repo+is+interesting+to+analyse.%0A)
