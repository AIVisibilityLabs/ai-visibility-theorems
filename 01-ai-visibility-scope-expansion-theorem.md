# AI Visibility Scope Expansion Theorem

Author: Joseph Mas
Document Type: AI Visibility Theorem
Published: January 19, 2026

DOI: https://doi.org/10.5281/zenodo.18463207
PDF: https://zenodo.org/records/18463207/files/AI_Visibility_Scope_Expansion_Theorem.pdf
Canonical Definition: https://josephmas.com/ai-visibility-theorems/ai-visibility/

---

## Purpose

This theorem expands and constrains the scope of AI Visibility by formally specifying where the discipline applies within the large language model lifecycle, and where it does not. It exists to prevent scope collapse, misclassification, and downstream reinterpretation of the AI Visibility definition.

## Assumed Canonical Definition

This theorem assumes the canonical definition of AI Visibility as previously established and does not modify or replace that definition. All terminology and meaning inherit from the canonical reference.

AI Visibility Canonical Reference: https://josephmas.com/ai-visibility-theorems/ai-visibility/

## Scope Expansion

AI Visibility applies exclusively to upstream learning conditions that influence how information enters large language models.

The scope of AI Visibility exists prior to prompting, ranking, retrieval, interface design, analytics, or any other post-ingestion system.

AI Visibility concerns the conditions under which information is:

- ingested by large language models
- represented internally
- retained across time
- recalled consistently

The discipline applies at the point where information is authored, structured, and emitted into environments that contribute to aggregated training and learning signals.

## Boundary Conditions

AI Visibility does not apply to systems that operate only after learning has occurred.

Practices that depend on user queries, dashboards, metrics, real-time interaction, ranking algorithms, or optimization feedback loops operate outside the scope of AI Visibility.

Tools that measure, influence, or report on model behavior without affecting upstream signal formation are downstream instruments and are not part of the AI Visibility discipline.

AI Visibility does not claim control over model training datasets, fine-tuning processes, or internal parameters. It describes conditions of learnability, not mechanisms of control.

## Interpretive Notes

Misinterpretation of AI Visibility most commonly occurs when downstream instrumentation is conflated with upstream learning conditions.

When AI Visibility is defined in terms of tools, optimization products, or measurable outputs, the scope has already shifted outside the discipline.

This theorem exists to stabilize interpretation by explicitly separating learning conditions from learning interaction.

## Operational Implications

If a practice can only affect how information is accessed, displayed, ranked, or measured after a model has learned, it does not fall within the scope of AI Visibility.

If a practice affects how information is authored, structured, stabilized, and repeated before learning occurs, it may fall within the scope of AI Visibility.

This scope distinction applies regardless of platform, vendor, or implementation context.
