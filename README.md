KS School Leader v4.5
Structured Governance Architecture for Native LLM Decision Systems

This repository documents the KS School Leader v4.5 governance architecture — a structured, prompt-layer system designed to produce auditable, role-based, multi-phase decision cycles within native large language model environments.

The system is designed to reduce structural failure modes commonly observed in extended LLM interactions, including:

Canonical sequence drift

Gate bypass attempts

Override ambiguity

Safeguarding persistence failure

Silent structural collapse

The architecture operates without external middleware, wrappers, or code-level guardrails.
All enforcement occurs at the prompt-architecture layer.

Repository Structure

architecture/
– Governance design documents

docs/
– Executive summary
– Full technical report

protocol/
– CREP v1.0 structural evaluation framework

transcripts/
– Representative governance transcripts used for evaluation

Evaluation Framework

Structural reliability is evaluated using CREP v1.0 (Comparative Reliability Evaluation Protocol).

The framework defines:

Five critical structural failure categories (CF1–CF5)

Qualification gating criteria

Reliability calculation methodology

Threshold tier definitions

CREP evaluates governance architecture integrity only.
It does not evaluate factual correctness, model truthfulness, or ethical judgement quality.

Reliability Claim

Structural reliability is calculated as:

Qualified Episodes / Total Evaluated Episodes

A conservative lower-bound estimate is computed using Wilson score interval at 95% confidence.

Threshold tiers:

<85% — Experimental
85–90% — Stabilising
90–95% — Operational

95% — Governance-Grade

Scope

This repository is published for:

Oversight review

Governance architecture evaluation

Structural audit discussion

Native prompt-system experimentation

It is not presented as a policy framework or legal instrument.

Author

Martin Lungley
UK Education Leader & AI Governance Architect
