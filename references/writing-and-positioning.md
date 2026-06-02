# TPAMI Writing and Positioning

Use this reference for literature research, manuscript planning, journal-extension framing, and prose revision.

## TPAMI-Level Contribution Framing

Make the manuscript's central argument explicit:

- Problem: a durable pattern-analysis, vision, recognition, or machine-intelligence problem.
- Gap: a concrete limitation in existing methods, benchmarks, theory, evaluation, or deployment assumptions.
- Method: what technical mechanism changes the state of the art.
- Evidence: experiments, ablations, analysis, datasets, or theory that directly support the claims.
- Generality: why the result matters beyond one dataset, domain, or implementation.

Strong contribution bullets are specific, testable, and tied to evidence. Weak bullets use broad adjectives without proof: "robust", "effective", "general", "comprehensive", "novel framework".

## Journal Extension Positioning

For work derived from a conference or preprint version, require visible, substantive additions:

- New technical component, theory, analysis, or formulation.
- Expanded experiments across more datasets, metrics, protocols, or settings.
- Stronger ablations isolating the proposed ideas.
- Additional baselines, including recent and competitive methods.
- Reproducibility details: code, data, splits, hyperparameters, training/inference cost, and implementation notes.
- Explicit explanation of how the TPAMI version differs from and advances beyond the prior version.

Do not present incremental polishing as a journal-level extension. If additions are mostly wording, extra figures, or marginal tables, flag this as a major positioning risk.

## Section Guidance

### Abstract

- State the problem and gap in the first sentences.
- Identify the method without excessive architecture detail.
- Give the evidence and scope of improvement precisely.
- Avoid citations, equations, long enumerations, and unsupported generality.

### Introduction

- Use a tight arc: context, unsolved gap, key insight, method summary, evidence, contributions.
- Avoid long literature surveys in the introduction; move taxonomy and dense comparisons to related work.
- Make the "why TPAMI" case through maturity, depth, and evidence rather than prestige language.

### Related Work

- Organize by technical fault lines, not chronology.
- Explain how each cluster relates to the paper's gap.
- Include recent top-conference and journal baselines when relevant.
- Avoid dismissive or vague contrast. State exact differences in assumptions, supervision, data, objective, architecture, or evaluation.

### Method

- Define notation early and use it consistently.
- Separate problem formulation, model or algorithm, training/inference procedure, and complexity when applicable.
- Make assumptions explicit.
- Ensure figures match the text and expose the actual technical mechanism.

### Experiments

- Tie each experiment to a claim.
- Include enough details for reproduction: datasets, splits, metrics, baselines, hyperparameters, implementation, hardware or cost when relevant.
- Use ablations to isolate contributions, not just list variants.
- Report failure cases and limitations when they affect deployment or generality.
- Avoid comparing against weak or outdated baselines without justification.

### Conclusion and Limitations

- Summarize what was established, not what was hoped.
- Keep future work concrete and bounded.
- State limitations honestly when they are important for scope, ethics, robustness, or generalization.

## Prose Style

- Prefer direct technical claims over promotional language.
- Put evidence near the claim it supports.
- Use active voice when it improves clarity.
- Remove redundant signposting and repeated results.
- Keep terminology stable: one concept, one name.
- Avoid overclaiming SOTA unless the benchmark protocol and baselines justify it.
- Make captions self-contained enough to be useful during review.

## Literature Research Output

For a TPAMI-oriented literature review, return:

- Scope definition and inclusion/exclusion criteria.
- Taxonomy of method families or problem settings.
- Representative papers with real citations and why they matter.
- Benchmark and dataset landscape.
- Open gaps and how the user's manuscript can occupy one gap.
- Risks: saturated topic, missing baselines, weak novelty, or unsupported claims.
