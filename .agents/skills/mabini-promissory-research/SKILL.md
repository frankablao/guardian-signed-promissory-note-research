---
name: mabini-promissory-research
description: Develop and verify research materials for the guardian-signed electronic promissory note study at Mabini Colleges, Inc. Use for its proposal, literature, protocol, instruments, analysis, and manuscript, including research issues delivered through GitHub Work.
---

# Mabini promissory note research

Produce reviewable research materials whose methods and claims match the evidence available for Mabini Colleges, Inc.

## Establish the task and evidence

Read the requested issue or deliverable and relevant source materials. Resolve repository paths from the repository root, not from this skill directory. Read [study scope](references/study-scope.md) for the domain constraints and source map. Inspect the current protocol and evidence relevant to the task; do not assume a closed issue establishes research completion.

Identify which research question and acceptance criteria the work addresses. Distinguish confirmed requirements, proposed methods, observed evidence, and unresolved decisions. If a material decision is missing, first check existing artifacts, then ask a focused question or document the concrete blocker. Do not reopen settled decisions for optional refinements.

## Produce and check the deliverable

Read only the relevant sections of [research quality checks](references/research-quality-checks.md). Use the existing manuscript organization and citation conventions. Choose reasonable drafting details without manufacturing institutional facts, dates, sample sizes, approvals, or findings.

- For literature synthesis, adapt the [literature matrix template](assets/literature-matrix-template.md) when it helps retain selection and source evidence.
- For substantive claims, tables, or results, adapt the [claim evidence template](assets/claim-evidence-template.md) or use an existing equivalent. Avoid a separate ledger for trivial wording edits.
- Record new study decisions in the protocol or relevant manuscript/evidence file, with amendments where needed. Keep these living decisions out of the skill itself.
- Treat missing observations or institutional approvals as missing evidence. Drafting forms or scripts cannot satisfy criteria requiring recruitment, collection, or measured results. Continue independent authorized work, but leave dependent criteria unmet.

Report the changed deliverable, relevant checks and outcomes, evidence limitations, and outstanding criteria. Report neutral or negative findings faithfully. A completed study need not show improvement.

## Complement GitHub Work

When `$github-workflows:github-work` is invoked, apply this skill inside that workflow:

| GitHub Work phase | Research contribution |
| --- | --- |
| Recon | Map criteria to research questions, source evidence, protocol decisions, and genuine prerequisites. |
| Plan and execute | Identify manuscript/instrument/analysis files and evidence needed for each criterion. |
| Verify | Check source authenticity, scope, methodology, reproducibility, and claim support alongside repository checks. |
| Deliver | Supply concise research evidence and unresolved gaps for the PR acceptance checklist. |

GitHub Work retains control of branch provenance, isolation, commits, review checks, pushes, and PR delivery. Do not duplicate or relax its rules, invoke sibling workflows, or modify the plugin. This skill can also guide an authorized local research edit without starting GitHub Work.

A successful build demonstrates rendering, not research validity. An implemented portal feature demonstrates an artifact, not empirical benefits. Do not claim an issue is complete or use a completion claim for a partial deliverable whose required fieldwork or evidence remains missing.
