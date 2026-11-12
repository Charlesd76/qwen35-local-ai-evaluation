# Qwen 3.5 4B — Local AI Evaluation Log

**Status:** Exploratory baseline research · **Recorded through:** November 8, 2026  
**Evaluator:** Charles (Chuck) · **Model:** `qwen3.5:4b` via Ollama on a local Windows desktop

## Purpose

An ongoing, independently directed evaluation of a small local language model as a possible general-purpose AI collaborator across projects. The study examines repeated reconsideration of already-settled choices, instruction carryover between turns, relevance of generated reasoning traces, and uncertainty calibration.

## Evaluation so far

- **Baseline 1:** In an existing conversation, the model carried an earlier one-sentence instruction into subsequent reasoning.
- **Baseline 2:** A fresh conversation produced a more focused response, but also assumptions about unspecified governance details.
- **Round 3:** A replicated nickname-prompt sequence reproduced extensive repetitive deliberation.
- **Diagnostic follow-up:** A later self-report did not adequately account for the behavior visible in the recorded trace.

**Interpretation limit:** Ollama's displayed “thinking” is model-generated text; it is not direct access to the model's internal computation. These observations do not establish a general defect, motive, or causal mechanism. Comparable token counts, settings, and repeated trials were not all recorded.

## Evaluation principles

Record observed behavior separately from inference. Preserve original evidence. Document prompts, conditions, negative results, uncertainty and untested hypotheses. Do not claim a fix or model training without evidence. Apply independent testing before making stronger conclusions.

## Current status and next experiment

This is an **ongoing evaluation**, not a finished product or a claim of model improvement. Round 4 is **planned, not executed**: remove one prompt from the original sequence and repeat conditions to test possible context carryover.

## Evidence

The source study has a reviewed, path-redacted publication package with detailed comparisons, exact prompts, screenshots, raw traces, an observation sheet and evidence hashes. The full package has **not yet been uploaded to this repository**. This README is the initial public portfolio overview; evidence files will be added only after their publication and integrity checks are complete.

## Project ownership

The related commercial software projects remain separate and are not being published here.
