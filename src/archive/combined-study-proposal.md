# Design and Evaluation of a Guardian-Signed Electronic Promissory Note Workflow at Mabini Colleges, Inc.

## Document status

Research proposal and manuscript planning document based on [mc-portal issue #740](https://github.com/frankkivenablao-mabini/mc-portal/issues/740). This document describes a proposed study; it does not report completed implementation, participant recruitment, experimental results, or demonstrated benefits.

## Repository and source status

This working proposal is versioned in `src/guardian-signed-promissory-note-research-proposal.md` in the [research repository](https://github.com/frankkivenablao-mabini/guardian-signed-promissory-note-research). The manuscript lives in `docs/`; implementation is tracked separately in [mc-portal #740](https://github.com/frankkivenablao-mabini/mc-portal/issues/740). No implementation, institutional approval, recruitment, data collection, or benefit is established by this proposal.

The locally supplied inventory/POS PDF is a structural/contextual reference only. Its outcomes, approvals, participants, and implementation status are not evidence for this study. The original PDF is preserved locally without alteration and is not required to substantiate this proposal; the source register explains its availability. Public research materials must exclude identifiable financial records, account identifiers, linkage keys, and actual signatures.

## Proposed abstract

This proposed study will design and evaluate a guardian-signed electronic promissory note workflow at Mabini Colleges, Inc. The portal requirements describe a process involving an electronic student request, Dean verification, printing and guardian signing, and President's Office approval; local practice and its burdens remain to be validated. The proposed workflow moves guardian signing onto the student's device within the authenticated student session before Dean and President's Office approval. It is intended to preserve accepted terms and present the same signed record to both offices. Design science research will combine artifact development, technical verification, a proposed baseline/post-rollout comparison, and participant evaluation. Eligible local students, participating guardians, Dean reviewers, and President's Office personnel are the intended participants; included departments, academic levels, observation periods, and sample size remain protocol decisions requiring institutional evidence. Evaluation will examine request-to-decision time, completion, visits, printing, resubmission, usability, payment-term clarity, perceived trustworthiness, and signed-record integrity. Student-session signing does not independently authenticate the guardian. The intended contribution is evidence about this local workflow and qualified design lessons, without claims of completed implementation, approvals, collection, or demonstrated benefits. Findings will be bounded to the participating units and observation periods at Mabini Colleges, Inc.

**Keywords:** Mabini Colleges, Inc.; electronic promissory note; guardian signing; administrative workflow; design science research; usability; record integrity.

## Research context and problem

For Mabini Colleges, Inc., the requirements in issue #740 describe a workflow that combines an electronic promissory note request with a paper-signature requirement. A student submits a request, the Dean verifies it, and the student prints the note for a parent or guardian to sign. The signed paper is then the basis for President's Office approval. This is a requirements-derived description, not an observed baseline; institutional workflow validation remains pending.

This arrangement introduces a physical handoff into an otherwise electronic process. Potential consequences include additional printing, visits, waiting, and document handling. These are hypotheses to investigate, rather than established problems with measured prevalence or severity.

The proposed workflow moves guardian signing before Dean approval:

**Student request → Guardian signing on the student's device → Dean approval → President's Office approval.**

The guardian reviews the student and guardian details, applicable period, payable amount, intended immediate payment, deferred balance, and payment deadline before explicitly accepting and signing. Both offices subsequently review the same signed note. Printing remains optional for new requests.

The research problem is how to redesign and evaluate this process so that reduced dependence on paper can be assessed alongside usability, clarity of acknowledgment, preservation of signed terms, and enforcement of approval order. A central constraint is that the guardian signs while the student is logged in. The proposed design would record the student session associated with signing, but it cannot independently establish that the guardian personally signed.

## Research opportunity and intended contribution

The study will investigate how an integrated workflow combines electronic acknowledgment, a preserved record of accepted terms, sequential approvals, and continued support for legacy paper requests. The intended scholarly contribution is evidence from Mabini Colleges, Inc.; any transferability to other institutions would require qualified discussion and independent contextual assessment.

Candidate contributions are:

1. A working artifact that preserves accepted terms and enforces the required signing and approval sequence.
2. Empirical evidence about workflow performance and stakeholder experience compared with the existing process.
3. Design principles for making signing context and identity-verification limitations clear to users and reviewers.
4. Lessons from introducing an electronic process while existing requests retain their original workflow.

These are intended contributions, not established novelty claims. A focused literature review must determine how they relate to prior research on electronic signatures, administrative process redesign, student financial services, and design science artifacts. Avoid claiming that this is the first system of its kind.

## Aim and objectives

**Aim:** Design and evaluate a guardian-signed electronic promissory note workflow at Mabini Colleges, Inc., examining efficiency, usability, and the integrity of the approval record.

Within the participating units and confirmed observation periods at Mabini Colleges, Inc., the objectives are to:

1. Document the existing process and establish baseline measures of time, effort, and completion.
2. Develop the proposed workflow according to issue #740, including preservation of signed terms and legacy compatibility.
3. Evaluate student, guardian, and staff usability and understanding of the signed commitment.
4. Compare relevant workflow outcomes between paper-based and electronic cases.
5. Verify access restrictions, signed-term immutability, approval order, and safe handling of duplicate or concurrent actions.
6. Identify the practical limits and transferable design lessons of signing within an authenticated student session.

## Research questions

- **RQ1:** Within the participating units at Mabini Colleges, Inc., how do the baseline and electronic workflows compare in total request-to-decision time, completion rates, physical visits, printing, and resubmission rates?
- **RQ2:** How do eligible participating students, guardians, Dean reviewers, and President's Office personnel at Mabini Colleges, Inc. assess usability, clarity of payment terms, and trustworthiness?
- **RQ3:** Under specified tests for the Mabini Colleges, Inc. artifact, how effectively does the system preserve signed terms and enforce authorized access and approval sequencing under specified test conditions?
- **RQ4:** What practical limitations and misunderstandings arise at Mabini Colleges, Inc. when guardian signing occurs within a student session without separate guardian authentication?

## Institutional scope and beneficiaries

This is a single-institution study at Mabini Colleges, Inc. It includes the proposed workflow for eligible local students in institutionally confirmed participating units, their participating guardians, Dean reviewers, and President's Office personnel. It does not assume participation by all departments, academic levels, students, or guardians.

Students and guardians are potential beneficiaries of clearer terms and fewer physical handoffs; Dean reviewers and President's Office personnel may benefit from reviewing the same preserved record. These are motivations to evaluate, not demonstrated benefits. Local administrators may use eventual evidence to assess workflow decisions. Broader literature supplies methodological context, not evidence of local outcomes.

Excluded are other institutions, unconfirmed units and academic levels, guardian accounts, external signing links, SMS/OTP verification, external signature providers, and retroactive conversion of legacy requests. Repayment, retention, and academic improvements are not outcomes established by this evaluation. Legacy requests retain their original workflow and are not automatically comparable controls.

### Protocol decisions pending institutional evidence

| Decision | Evidence needed before affected research proceeds |
| --- | --- |
| Included departments and academic levels | Institutional confirmation of participating units and service eligibility; no all-college assumption. |
| Observation periods and rollout boundary | Approved baseline/post-rollout dates, comparable request windows, and artifact version. |
| Sampling and recruitment | Eligible population, request volume, primary outcome, feasibility and sample-size rationale; voluntary recruitment arrangements. |
| Research and data access | Applicable institutional approval or determination, consent arrangements, minor-participant requirements if relevant, and restricted storage/retention plan. |
| Measurement and analysis | Outcome definitions, denominators, pending/repeated cases, exclusions, missing-data rules, and contextual confounders. |

These decisions belong to the protocol work tracked in [research issue #4](https://github.com/frankkivenablao-mabini/guardian-signed-promissory-note-research/issues/4). This proposal neither resolves them nor records institutional approval. No approved protocol is present in the repository at this foundation stage.

## Scope of the artifact

The following are proposed requirements, not verified implementation behavior.

| Area | Included behavior |
| --- | --- |
| Signing | Touch or mouse capture of a handwritten signature after review and explicit acceptance of the displayed terms. |
| Signing context | Record the authenticated student account and signing time without claiming independent guardian authentication. |
| Signed record | Preserve accepted guardian details and financial terms so later profile or configuration changes do not rewrite the signed record. |
| Approval order | Require guardian signing before Dean approval and Dean approval before President's Office approval. |
| Corrections | Allow editing before signing; after signing, corrections require cancellation and a fresh request and signature, subject to existing rules. |
| Access | Limit access to the owning student and appropriately authorized staff. |
| Printing | Include the signature, signing date, accepted terms, and actual status; retain the Temporary Copy label until Dean approval. |
| Legacy requests | Keep all requests created before rollout on their original workflow without fabricated signatures or reset approvals. |
| Existing policies | Preserve eligibility, amount limits, payment handling, request windows, duplicate prevention, and cancellation constraints. |

Guardian accounts, external signing links, SMS or OTP verification, external signature providers, and retroactive conversion of existing requests are outside the feature scope. The study does not establish legal enforceability, cryptographic digital signing, or the authenticity of a guardian's identity.

## Proposed methodology

### Research approach

Use design science research to connect the practical problem, artifact development, evaluation, and resulting design knowledge. Gregor and Hevner discuss how to position artifact-based contributions beyond an implementation description [1]. The FEDS framework provides guidance for planning artifact evaluation [2].

### Study phases

1. **Problem investigation:** Map the existing process, interview relevant stakeholders, and define event timestamps and outcomes before collecting comparative data.
2. **Design and development:** Implement and document the workflow, the preserved signed record, access controls, and rollout boundary.
3. **Technical verification:** Exercise normal, invalid, unauthorized, stale, and concurrent actions with synthetic records.
4. **Pilot evaluation:** Observe representative students, guardians, and staff completing tasks and use the findings to refine the artifact.
5. **Field evaluation:** Collect comparable workflow measures and stakeholder feedback under an approved study protocol.
6. **Analysis and reporting:** Assess outcomes, explain uncertainty and limitations, and derive design principles supported by evidence.

### Participants and sampling

The proposed participants are students eligible to request promissory notes at Mabini Colleges, Inc. in confirmed participating units, their participating guardians, Dean reviewers, and President's Office personnel. Included departments and academic levels require institutional confirmation. Determine sample size from the primary outcome, expected variability, available request volume, and the intended analysis. Do not select an arbitrary sample size solely because it is customary.

For interviews and usability observations, seek variation in device familiarity, accessibility needs, and experience with the existing process. Record recruitment and nonparticipation so selection bias can be discussed.

### Comparative design

Prefer a prospective evaluation with clearly defined baseline and post-rollout observation periods. Use comparable periods where possible and record workload, staffing, request characteristics, and policy changes that may influence outcomes.

Existing legacy requests may provide additional context, but they are not automatically an equivalent control group: their age and approval stage may differ from new electronic requests. Describe a nonrandomized comparison as such and avoid attributing every observed change to the software.

Measure the whole process from initial request submission, including time awaiting guardian signing. Report stage-level times separately. Comparing only time after signing would omit a potentially substantial part of the new process.

## Evaluation and analysis plan

| Dimension | Operational measures | Evidence and analysis |
| --- | --- | --- |
| Efficiency | Request-to-decision elapsed time and time spent at each stage. | Event records and consistent baseline records; report distributions and suitable effect estimates with uncertainty. |
| Completion | Proportion of eligible submitted requests reaching a final decision within a predefined observation window. | Track pending, rejected, and cancelled cases separately; do not silently omit unfinished cases. |
| Administrative burden | Physical visits, pages printed, staff handling time, and replacement or resubmission frequency. | Structured observations, logs where available, and clearly identified self-reports. |
| Usability | Task success, errors, assistance needed, and questionnaire responses. | Observed tasks plus a suitable validated usability instrument used according to its published guidance. |
| Understanding | Ability to identify the deferred amount, deadline, current approval status, and meaning of signing. | Brief comprehension questions and interviews. |
| Record integrity | Whether signed values remain unchanged after attempted edits and changes to source records. | Automated tests using synthetic data and documented expected outcomes. |
| Workflow control | Whether unauthorized, unsigned, out-of-order, duplicate, and stale actions are rejected appropriately. | Functional, access-control, and concurrency tests; record failures as well as passes. |
| Signing confidence | Perceptions of who signed and what the system can verify. | Student, guardian, and staff interviews with thematic analysis. |

Predefine the primary outcome, observation window, exclusions, and missing-data handling. For time outcomes, account for requests still pending at the end of observation rather than comparing completed cases alone. Select statistical methods based on the design and data distribution, and report practical effect sizes alongside uncertainty.

For qualitative data, document interview prompts, coding decisions, and how themes were developed. Integrate qualitative findings with the workflow measures to explain delays, usability difficulties, or unexpected results. User satisfaction and successful software tests should be treated as distinct forms of evidence.

## Ethics and data management

Obtain applicable institutional research approval before recruiting participants or using identifiable administrative records for research. Separate research participation from access to the promissory note service, and explain that declining participation will not affect administrative decisions.

Minimize collected personal and financial data. Use coded study identifiers, restrict access to identifiable materials, and define retention and deletion arrangements. Public reproducibility materials should use synthetic data or appropriately anonymized summaries, excluding signatures, account identifiers, and identifiable financial records.

Distinguish the guardian's acceptance of payment terms from consent to participate in research. If minors are included, determine the applicable institutional requirements before recruitment.

## Limitations to acknowledge

- A signature captured during a student session does not independently verify guardian identity or prove who physically drew it.
- Requiring the guardian to use the student's device may shift effort to arranging access or being physically together; measure this burden rather than assuming it disappears.
- This study at Mabini Colleges, Inc. will be limited to its participating units and observation periods and may not generalize to institutions with different financial policies or staffing arrangements.
- Before-and-after comparisons can be affected by seasonality, staff workload, and changes in the student population.
- Access to devices, digital familiarity, and accessibility requirements may influence participation and task success.
- Technical verification demonstrates behavior under tested conditions; it does not prove the absence of all vulnerabilities or establish legal validity.
- Approval speed does not establish improved repayment, retention, or academic outcomes; those require separate evidence.

## Suggested manuscript structure

1. Introduction and research problem.
2. Related literature and research gap.
3. Institutional context and requirements.
4. Research methodology.
5. Artifact design and implementation.
6. Evaluation results, populated only after data collection and analysis.
7. Discussion and evidence-supported design principles.
8. Limitations, implications, and conclusion.

## Publication readiness

Before preparing a submission, complete the focused literature review, select an appropriate publication venue, finalize the study protocol and instruments, implement and verify the artifact, and collect and analyze the evaluation evidence. Replace prospective language with completed-study descriptions only where the work has actually been performed. An implemented feature alone does not establish a publishable research contribution.

## References and source material

1. Gregor, S., & Hevner, A. R. (2013). Positioning and presenting design science research for maximum impact. *MIS Quarterly, 37*(2), 337–355. https://aisel.aisnet.org/misq/vol37/iss2/3/
2. Venable, J., Pries-Heje, J., & Baskerville, R. (2016). FEDS: A framework for evaluation in design science research. *European Journal of Information Systems, 25*, 77–89. https://doi.org/10.1057/ejis.2014.36
3. mc-portal issue #740. Require guardian signing in the student session before promissory note approvals. https://github.com/frankkivenablao-mabini/mc-portal/issues/740

These sources establish the project requirements and an initial methodological foundation. They do not constitute a complete literature review of electronic promissory notes or guardian signing.
