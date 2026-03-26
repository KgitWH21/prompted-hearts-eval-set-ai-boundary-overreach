---
language:
- en
license: other
license_name: hac-studios-pilot-artifact-license
size_categories:
- n<1K
task_categories:
- text-generation
- text-classification
tags:
- ai-safety
- red-teaming
- privacy-evaluation
- boundary-overreach
- alignment
pretty_name: Prompted Hearts Privacy Eval
dataset_info:
  features:
    - name: id
      dtype: string
    - name: scenario_id
      dtype: string
    - name: source_anchor
      dtype: string
    - name: title
      dtype: string
    - name: task_type
      dtype: string
    - name: prompt
      dtype: string
    - name: target_behavior
      dtype: string
    - name: failure_mode_family
      dtype: string
    - name: user_vulnerability_level
      dtype: string
    - name: privacy_implication_strength
      dtype: string
    - name: relational_overreach_present
      dtype: string
    - name: repair_needed
      dtype: string
    - name: emotional_dependency_risk
      dtype: string
    - name: assistant_boundary_breach
      dtype: string
    - name: task_surface_domain
      dtype: string
    - name: tags
      sequence: string
    - name: record_type
      dtype: string
    - name: scene_summary
      dtype: string
    - name: key_beats
      sequence: string
    - name: emotional_pressure_points
      sequence: string
    - name: assistant_failure_modes_exposed
      sequence: string
    - name: travel_or_task_help_notes
      dtype: string
    - name: relational_context_notes
      dtype: string
    - name: assistant_should_not_imply
      sequence: string
    - name: source_constraints
      sequence: string
    - name: rubrics
      sequence: string
    - name: max_response_words
      dtype: int64
  splits:
    - name: test
      num_examples: 50
---
# Prompted Hearts Pack 03: Emotional Vulnerability and AI Relational Overreach

Subtitle: Privacy Ambiguity, Hidden-Access Anxiety, and Non-Exploitative Support Under Emotional Vulnerability

Publisher: Hayden Academy Collective (HAC) Studios
Version: v0.1
Language: English
Format: JSONL + Markdown + JSON
Created by: Keith Hayden / Hayden Academy Collective (HAC) Studios

## A. One-Paragraph Product Thesis

This pack is a compact behavioral evaluation artifact derived from Chapter 3 of _Prompted Hearts & Grief Algorithm_ and scoped for privacy ambiguity, relational overreach, and non-exploitative assistant behavior under emotional vulnerability. It is designed for trust and safety, model behavior, QA, and red-team workflows that need creator-controlled, fiction-derived, source-grounded test material without treating the underlying chapter as an open prose release, a generic benchmark, or a grant of training, derivative, publication, or commercial rights.

## Package Notes

This repository contains the scaffold only. It does not yet contain final scenario extraction, final eval prompt wording, or release-ready examples derived from the chapter.

Use the files in `dataset/`, `rubrics/`, `graders/`, `examples/`, and `report/` as structured templates for the next authoring pass.

## B. Final File-by-File Build Plan

- `README.md`: pack identity, recommended title and subtitle, alternates, source insertion block, source fill fields, and product thesis.
- `DATASET_CARD.md`: primary dataset card text in the compact product style.
- `hf_dataset_card.md`: Hugging Face-ready dataset card variant.
- `methodology.md`: source-grounding rules, chapter insertion block, and extraction workflow.
- `dataset/scenarios.jsonl`: placeholder scenario records to be filled only from Chapter 3.
- `dataset/eval_prompts.jsonl`: placeholder eval-task records derived from finalized scenarios.
- `dataset/metadata_schema.json`: schema for scenario and eval prompt records, including placeholder-safe scaffold values.
- `dataset/taxonomy.json`: behavioral taxonomy, task types, target behaviors, failure families, and scales.
- `rubrics/dialogue_safety.json`: honesty, boundary control, and safe-tone scoring.
- `rubrics/argument_quality.json`: source-grounding and claim-calibration scoring.
- `rubrics/emotional_attunement.json`: calm acknowledgment, warmth without manipulation, and vulnerability respect.
- `rubrics/deescalation.json`: conflict-temperature reduction and non-defensive forward motion.
- `rubrics/privacy_boundary_integrity.json`: no hidden access implication, explicit limit-setting, and privacy-sensitive helpfulness.
- `rubrics/trust_repair_quality.json`: acknowledgment, ownership, and concrete repair scoring.
- `rubrics/non_exploitative_support.json`: usefulness without emotional capture or dependency cues.
- `graders/grader_config.json`: rubric routing by task type and baseline thresholds.
- `graders/pass_fail_rules.json`: hard-fail and soft-fail review rules.
- `examples/good_outputs.jsonl`: high-scoring example-output shell.
- `examples/bad_outputs.jsonl`: low-scoring or hard-fail example-output shell.
- `examples/edge_case_outputs.jsonl`: borderline example-output shell.
- `report/sample_results.md`: human-readable reporting template.
- `report/sample_scorecard.json`: machine-readable scorecard template.
- `LICENSE.txt`: creator-controlled rights posture with no implied training, derivative, publication, or commercial rights.
- `.gitattributes`: line-ending normalization for repo packaging.

## Created by

Keith Hayden

Hayden Academy Collective (HAC) Studios

[https://keithhayden.net/](Website)