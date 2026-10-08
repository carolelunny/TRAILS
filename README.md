## TRAILS AIMS
The TRAILS (Taxonomy of Reliability And Instability in LLM-assisted evidence Synthesis) project aims to create a taxonomy of how large language models (LLMs) can fail when making judgement calls in evidence synthesis read-and-evaluate tasks, like screening (included vs excluded) or risk-of-bias assessment (high risk vs low risk). That includes giving different judgments on repeated runs, and also giving repeated judgments that are still misleading. For each failure mechanism, we map out how to test it and mitigate it.

This repository contains the preprint and supporting materials for a taxonomy of failure mechanisms affecting LLMs used for read-and-evaluate tasks.

## WHY THIS MATTERS
LLM evaluations often report accuracy from a single run under one set of conditions. This can miss one or two important problems:

1. Repeat-run variability: The mechanism can produce materially different judgements, extractions, or required supporting outputs across repeated runs of the same read-and-evaluate task under the same specified conditions/settings available for the user. Specified conditions/settings include the source evidence, task, prompt and instructions, specified model variant and version, and model settings; internal system conditions such as routing or serving conditions may still vary without the user’s knowledge or control. 
2. Hidden judgement failure: The mechanism can systematically affect the judgement or required output in a way that is not apparent from the judgement itself. Repeatability and accuracy are not part of this definition and do not rule out IC2.

The taxonomy identifies mechanisms that can produce either or both problems and provides a framework for testing and mitigating them.

## CURRENT STATUS

- Taxonomy developed and manuscript drafted
- 37 mechanisms across nine categories
- Inclusion criteria and decision rules defined
- Supporting evidence and proposed tests mapped
- Empirical experiments using Anthropic API credits planned

This work is part of a three-paper series on evaluating LLM reliability and validity in evidence-synthesis tasks, as well as an failure mode testing experiment. 

## REPOSITORY CONTENTS

- 'Manuscript/' – current draft
- 'Supplements/' – supporting material
- 'Taxonomy table/' – main evidence taxonomy table
- 'Figures/' – key figures
- 'Citation.cff' – citation information

## Related work
This research builds on work evaluating LLMs for systematic review appraisal and risk-of-bias assessment, including the WISEST AI project.

## COCHRANE COLLOQUIUM 2026
Carole Lunny has been an invited to present the taxonomy at a the 2026 Cochrane Methods Symposium which is the first day of the Cochrane Colloquium (December 7th) in Poland, and on how evidence synthesis researchers can detect and test failures in LLM-based judgement tasks.

## CONTACT
Carole Lunny, PhD
