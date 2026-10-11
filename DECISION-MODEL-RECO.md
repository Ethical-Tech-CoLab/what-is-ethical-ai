# Decision-model recommendation: citation assistance, not moral scoring

Date: 2026-10-11. Public-source proposal; no runtime integration.
Reviewed [README](https://github.com/Ethical-Tech-CoLab/what-is-ethical-ai/blob/cc20aaaf5de53fdef500f7f880560a66aa43a803/README.md).
Assessment depth: the paper's documented thesis and workflow.

## Recommendation

The paper locates ethical AI in institutions, human rights and participation,
not in a product feature. A decision model may assist source/claim checking and
research taxonomy routing. It must not label a system, person or institution
"ethical" by a scalar score or replace affected communities' deliberation.

For an individual citation, validate the exact quote then assess supports /
contradicts / not established / insufficient evidence. Preserve source date,
scope, qualifications and dissenting interpretations.

## Evaluation and alternatives

Compare human review and deterministic source checks with a licensed local
classifier, Jev's [citation-checking recipe](https://docs.typesafe.ai/cookbooks/citation_check.md),
Microsoft-Decision-1 and Sage on approved public text.
Exact proprietary weights are not available for local inference; local
alternatives require separate evaluation.

Split by source/argument family. Include contested ethical interpretations,
descriptive claims mistaken for normative endorsements, quotation out of
context, missing sources and provider self-assessments. Record disagreement
rather than forcing a single gold moral judgment.

Measure support-check false acceptance, evidence recall, calibration and human
review burden only for suitably adjudicated factual tasks. Do not report
"ethical accuracy" as an objective universal metric.

## Release boundary

Annotations are advisory, source-linked and reversible; the canonical paper
remains under author review. No automated governance action is proposed.
Measure total review cost before adding a service; this research workflow has
no established LLM baseline spend to replace.
