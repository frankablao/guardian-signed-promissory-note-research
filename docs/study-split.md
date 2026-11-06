# Two-study research brief

## Decision and status

The research is separated into two linked studies at **Mabini Colleges, Inc.** following the researcher's direction on 6 November 2026. This is a scope decision, not institutional approval or evidence of completed research. Both protocols are drafts. No approved sample, dates, recruitment, measurements, or results are established here.

| Boundary | Study A | Study B |
| --- | --- | --- |
| Title | Requirements and Design of a Guardian-Signed Electronic Promissory Note Workflow at Mabini Colleges, Inc. | Evaluation of a Guardian-Signed Electronic Promissory Note Workflow at Mabini Colleges, Inc. |
| Repository | [Design research](https://github.com/frankkivenablao-mabini/guardian-signed-promissory-note-research) | [Evaluation research](https://github.com/frankkivenablao-mabini/guardian-signed-promissory-note-evaluation) |
| Main question | What local needs, requirements, and validated design should guide implementation? | How does the verified implementation perform in the participating local setting? |
| Evidence | Literature, local process investigation, requirements, and formative design walkthroughs | Versioned technical tests, baseline/post-rollout observations, task observations, and feedback |
| Contribution | Evidence-supported requirements and a validated design with an implementation handoff | Observed operational and stakeholder outcomes, technical behavior, and limitations |
| Claim limit | Anticipated benefits and design concerns; no demonstrated operational improvement | Effects and experiences supported by collected evidence; no automatic causal claim |

## Sequence and timing

1. Study A investigates the current process and validates a proposed design, using synthetic cases for mockups.
2. A versioned Study A handoff supplies the research basis for [mc-portal #740](https://github.com/frankkivenablao-mabini/mc-portal/issues/740). Changes to its established constraints require an explicit decision; the research does not silently broaden implementation scope.
3. Study B prepares its protocol and instruments in parallel. Its approved baseline must be collected **before rollout changes the existing workflow**. Baseline collection need not wait for implementation completion.
4. Implementation and technical verification occur in mc-portal. Study B records the tested commit/release and readiness evidence before participant pilots and field evaluation.
5. Each study reports its own questions, methods, evidence, and limitations. Neither paper depends on a positive benefit finding.

## Evidence ownership and reuse

Study A owns local requirements evidence, process maps, design decisions, walkthrough findings, and the implementation specification. Study B owns comparative baseline/post-rollout measurement and implementation evaluation. Study A process observations are not automatically a valid Study B baseline.

Cross-study reuse requires a recorded source version, permitted research use, compatible definitions, and disclosure in both reports. Reusing participants requires applicable consent/approval coverage. Reference the other study's evidence; do not present the same analysis as two independent contributions. Preserve the original combined proposal in Study A's source archive as historical planning.

## Shared limits

The intended flow is student request → guardian signing on the student's device within the student session → Dean approval → President's Office approval. The session records a student account; it does not independently authenticate a guardian, establish cryptographic signing, or establish legal enforceability.

Existing eligibility and financial rules and all legacy requests' original workflows remain in scope for preservation. Guardian accounts, external links, OTP, external signature providers, and retroactive conversion remain excluded under #740. Findings concern only confirmed participating units and observation periods at Mabini Colleges, Inc. Approval speed does not establish repayment, retention, or academic benefits.

Identifiable financial records, account identifiers, linkage keys, and actual signatures belong in approved restricted storage outside Git. Public examples use synthetic records or permitted disclosure-reviewed aggregates.
