# TPAMI Review and Revision

Use this reference for reviewer-style critique, manuscript audits, response planning, and revision strategy.

## Review Rubric

Assess the manuscript on these dimensions:

- Fit: TPAMI scope and audience alignment.
- Significance: importance of the problem and likely community impact.
- Novelty: clear difference from prior art and prior versions by the same authors.
- Technical soundness: formulation, assumptions, algorithms, proofs, and implementation consistency.
- Experimental adequacy: datasets, baselines, metrics, ablations, statistical reliability, and protocol fairness.
- Generality: evidence across conditions, domains, scales, or assumptions.
- Reproducibility: code/data availability, hyperparameters, splits, compute, and enough implementation detail.
- Clarity: structure, notation, figures, tables, captions, and claim/evidence alignment.
- Ethics and compliance: permissions, human/animal subjects, bias/safety issues, duplicate submission, AI disclosure, and prior-version disclosure.

## Severity Labels

- `Critical`: likely desk rejection, policy violation, central result invalid, or manuscript outside TPAMI scope.
- `Major`: likely reviewer objection that needs new evidence, restructuring, new experiments, or claim reduction.
- `Minor`: local clarity, formatting, citation, caption, style, or consistency issue.

Lead with findings. Keep praise short unless the user explicitly asks for balanced reviewer text.

## Common Rejection Risks

- Contribution is conference-level rather than journal-level.
- Novelty is asserted but not isolated from prior methods.
- Experiments validate performance but not the paper's central mechanism.
- Baselines omit recent, strong, or directly comparable work.
- Ablations remove arbitrary components rather than testing hypotheses.
- Claims exceed evidence, especially for robustness, generality, efficiency, or real-world deployment.
- Dataset, split, metric, or implementation choices make comparison unfair.
- Related work is descriptive rather than argumentative.
- Figures are visually polished but do not clarify the method.
- Supplement carries essential evidence that should be in the main paper.
- Prior conference/preprint versions are not clearly disclosed and differentiated.

## Review Output Template

Use this compact structure unless the user requests another format:

1. Overall assessment: likely TPAMI readiness and the main reason.
2. Findings by severity: each finding includes evidence, risk, and concrete fix.
3. Missing experiments or analyses: prioritized list.
4. Writing and structure fixes: only the changes that affect review outcome.
5. Compliance or submission risks: separate from technical quality.

## Revision Strategy

For each reviewer concern:

- Restate the concern neutrally.
- Decide whether to add evidence, narrow a claim, correct an error, clarify text, or concede a limitation.
- Prefer manuscript changes over argumentative replies.
- Cite exact revised sections, figures, tables, or supplementary locations.
- Avoid claiming a concern is solved unless the manuscript visibly changed.

## Response Letter Style

- Start with a concise summary of major changes.
- Group repeated concerns across reviewers.
- Use respectful, specific language.
- Quote reviewer comments only as much as needed for orientation.
- For each response, include: concern, action taken, manuscript location, and residual limitation if any.
- Do not overpromise future experiments unless they are actually completed.

## Acceptance Criteria for a Revised TPAMI Draft

- The central contribution is understandable from abstract and introduction alone.
- Every major claim has direct supporting evidence.
- The prior-version difference is explicit and substantial.
- Baselines and ablations match the claim strength.
- Limitations and failure cases are not hidden.
- Formatting and policy issues are resolved or clearly queued for final official verification.
