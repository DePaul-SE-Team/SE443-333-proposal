# Final Project Proposal — 5%

## Purpose

The proposal will help your team establish a clear and feasible plan for the final project. You do not need to have a completed implementation or experimental results at this stage.

## Submission Requirements

- Submit one proposal per team.
- The proposal must be **two pages long, excluding references**.
- References may appear on an additional page.
- Submit the proposal in PDF. You should use overleaf.
- Short paragraphs, tables, and bullet points are acceptable.
- A separate title page is not required.

## Required Sections

### 1. Team Members

List each team member’s name and initial responsibility.

### 2. Introduction and Motivation

Briefly explain:

- What problem will your team investigate?
- Why is generating regression tests from software issue descriptions difficult?

Write approximately one short paragraph.

### 3. Related Work

Discuss at least **four relevant works**, such as:

- SWT-Bench
- SWE-mini
- A paper or tool related to automated test generation
- An agent-based software engineering approach

For each work, explain:

- What it does
- Its main idea or contribution
- How it relates to your proposed project

Include citations and list the complete references at the end of the proposal.

### 4. Baseline

Describe the unchanged baseline: **mini-SWE-agent using DeepSeek**.

Include:

- The DeepSeek model and version
- The mini-SWE-agent configuration
- The information available to the agent
- How the baseline generates a test patch
- The generation budget
- The stopping rule

The baseline may use issue descriptions, repository source code, existing tests, and development tools.

The baseline may not use:

- Reference fixes
- Reference test patches
- Evaluator-only information

### 5. Research Question and Proposed Workflow

State one clear research question:

> Does **[proposed workflow change]** improve **[measured outcome]** compared with the unchanged DeepSeek baseline under the same experimental conditions?

Then describe:

- What you will add or change
- Why you think the change may help
- How your workflow differs from the baseline

Choose one small and testable workflow change. A complicated system is not required.

### 6. Evaluation and Pilot Plan

Explain:

- Which SWT-Bench instances you plan to use for pilot-study? and why?
- How you will keep the baseline and proposed workflow comparable
- Which metrics you will collect
- Which instance you will use for the first pilot

### 7. Team Plan

List:

- Any current technical question or anticipated difficulty

## Grading — 5 Points

| Criterion | Points |
|---|---:|
| Introduction, motivation, and research question | 1 |
| Related work and appropriate citations | 1 |
| Clear and reproducible baseline | 1 |
| Proposed workflow and evaluation plan | 1 |
| Feasible pilot and team plan | 1 |
| **Total** | **5** |

## Important

Your proposed workflow does not need to outperform the DeepSeek baseline. The final project emphasizes experimental rigor, reproducibility, analysis, and clear reporting.
