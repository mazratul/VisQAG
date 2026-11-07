# Supplemental Materials and Research-Use Notes

**Associated work:** *VisQAG: An Experimental Study of Image-Based Question--Answer Generation with Multimodal LLMs*

## What is provided

The complete **consolidated prompt** is provided as `consolidated_prompt.md` (readable text) and `consolidated_prompt.docx` (source-formatted document). It includes the ground-truth instructions, four instruction-defined phases, visualization-specific adaptation matrix, five analytical categories, JSON structure, and self-check directives described in the manuscript.

These files document the prompt **used in the consolidated-prompt and exploratory evaluation phases**. They are intended to support scrutiny, reproduction attempts, and methodological comparison. The repository does not, by itself, provide the full set of original experimental images, model response logs, co-author ratings, or an independent output-validation implementation.

## Interpretation and use limitations

- This is an **empirically studied prompt**, not a clinically, educationally, or psychometrically validated assessment instrument. Its five analytical categories are study-defined; their cognitive hierarchy and question difficulty have not been independently validated.
- The prompt requests that the model internally check visual labels, numerical estimates, graph relationships, JSON structure, and rationale consistency. These are **model instructions, not guarantees** of correctness or evidence that a separate validator has been executed.
- The outputs may contain incorrect, ambiguous, unsupported, or unstable interpretations. Reviewers should independently check questions, answers, calculations, and rationales against the original visualization before use in consequential or formal assessments.
- The optional structured-data input described by the prompt **was not provided** in the reported image-based experiments; do not describe the published evaluations as data-table-grounded.
- No participant-based evidence in the paper establishes educational effectiveness, learner differentiation, or measurement reliability.

## Rights and permissions

This file is a **Supplemental Materials description and research-use statement**, not a legal ``Restricted Use Notice'' and not a license. Access or use beyond applicable law is governed by the license, if any, separately adopted by the rights holders. No license is silently implied by this package.
