<h1 align="center">Tushar Verma</h1>

<p align="center">
  <em>Professionally suspicious of what AI agents claim to remember.</em>
</p>

<p align="center">
  LLM agent-memory &amp; reliability evals &nbsp;·&nbsp; I break memory systems and file the receipts.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/LLM%20Evals-333333?style=flat" alt="LLM Evals" />
  <img src="https://img.shields.io/badge/Agent%20Memory-333333?style=flat" alt="Agent Memory" />
</p>

---

### What I work on

I evaluate the memory layer of AI agents — the part that decides which facts to keep, replace, or protect over time. Most eval work checks whether a model *retrieves* the right thing. I check whether it *changes its mind for the wrong reasons*: overwriting a confirmed fact on weak evidence, softening a safety-critical one, or confabulating a merge of two conflicting memories.

My approach is deliberately unglamorous — small, adjudicated, honest samples with error bars, and claims that get killed when the intervals overlap.

### Selected work

- **[conflict-resolution-evals](https://github.com/Tusharv23/conflict-resolution-evals)** — a cross-model evaluation of a production agent-memory policy. 120 manually adjudicated runs across 10 models; a follow-up context-load experiment (216 runs) with Wilson confidence intervals. Found action-type memory edits robust but restraint-type edits (don't-overwrite-on-weak-evidence) failing ~50% of the time — including a confirmed severe allergy silently downgraded. Findings were reported upstream to the open-source framework.

### How I think about this

- Negative results are results. Several findings in the study above did not survive uncertainty quantification, so I retired them.
- A green check is only as good as its assertion.
- If I can't show the arithmetic, I don't trust the number — including my own.

### Elsewhere

- **LinkedIn:** [tushar-verma](https://www.linkedin.com/in/tushar-verma-746465154/) &nbsp;·&nbsp; writing about evals & agent memory
- Background: platform engineering (API gateways, multi-team infra at scale), now focused on AI reliability.
