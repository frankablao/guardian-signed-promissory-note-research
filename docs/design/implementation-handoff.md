# Implementation handoff to mc-portal #740

**Status:** Draft specification structure. No stakeholder validation, working implementation, or readiness acceptance is claimed. [#740](https://github.com/frankkivenablao-mabini/mc-portal/issues/740) remains the authoritative complete implementation scope; this document supplies the research traceability and handoff criteria.

## Required package

- Validated current and proposed process maps, with institutional variation and evidence locators.
- Role/action permissions, state transitions, errors, correction/replacement paths, and terminal-state behavior.
- Synthetic screen mockups showing terms review, explicit acceptance, signing, staff review, and printing.
- Record fields and preservation rules, with source-to-requirement-to-acceptance-criterion traceability.
- Walkthrough findings, revisions, dissent, limitations, and unresolved concerns.
- A version identifier, review record, decision owners, and a disposition for each material concern.
- Study B event/measurement requirements agreed before rollout; no research measurements may be silently inferred from unsupported application events.

## Current requirements and decision register

These are requirements from #740, not observed behavior or institutional research findings. Local rationale and walkthrough evidence remain to be collected. Research may identify conflicts; changes require a documented decision in #740 before implementation scope changes.

| ID | Requirement or constraint | Category | Evidence/validation status | Implementation criterion |
| --- | --- | --- | --- | --- |
| A-D01 | Guardian signs on the student's device inside the authenticated student session | Established issue constraint | #740; local burden and comprehension unvalidated | Own-session signing; explicit acceptance; no separate guardian identity claim |
| A-D02 | Review student, guardian/relationship, period, payable, immediate payment, deferred balance, and deadline | Established issue requirement | #740; presentation requires walkthroughs | Exact accepted terms displayed before signing |
| A-D03 | Preserve accepted terms, guardian details, signature, signing time, and student account | Established issue requirement | #740; storage design pending implementation | Later profile/configuration/recalculation changes cannot rewrite the signed record |
| A-D04 | Guardian signing precedes Dean approval, which precedes President approval | Established issue constraint | #740; process comprehension unvalidated | Server-enforced order and same signed record for both offices |
| A-D05 | Unsigned edits allowed; signed corrections require cancellation and a fresh eligible request/signature | Established issue requirement | #740; interaction design pending | No signature reuse, terminal-state revival, or final-approval cancellation bypass |
| A-D06 | Restrict ownership/staff actions and handle invalid, duplicate, stale, and concurrent submissions | Established issue requirement | #740; technical behavior untested | Server access checks, preserved signed terms, and one valid state transition |
| A-D07 | Preserve optional printing, Temporary Copy until Dean approval, and actual status | Established issue requirement | #740; readability unvalidated | Review/print includes signature, date, terms, and current status |
| A-D08 | Preserve legacy workflows and existing eligibility, financial, payment, and period-switch rules | Established issue constraint | #740; implementation unverified | Reliable new/legacy boundary; no fabricated signatures or reset approvals |
| A-D09 | Mockup layout, wording, accessibility, and error recovery | Proposed design choices | Not designed or validated yet | Versioned mockups and walkthrough dispositions |
| A-D10 | Reduced visits/printing/time and clearer terms | Anticipated benefits, not requirements proved effective | No local outcome evidence | Study B measures benefits and possible added guardian/device burden |

## Proposed process and state model

The existing process is described by #740 as request → Dean verification → print/guardian paper signature → President's Office approval. Local verification is pending.

For new requests: **Awaiting Guardian Signature → Pending Dean Approval → Pending President Approval → Approved**. Rejection and cancellation follow #740 and existing rules. Signing alone does not remove Temporary Copy. Unsigned requests remain editable; signed terms stay fixed. Both offices inspect the same preserved signed note. Existing notes keep their original workflow.

This is a proposed model for validation, not a complete tested state machine. Storage, concurrency mechanisms, and legacy identification are implementation decisions in mc-portal.

## Expected benefits and countervailing burdens

| Proposed mechanism | Anticipated benefit | Possible added burden | Future evidence |
| --- | --- | --- | --- |
| Remove mandatory paper-signature handoff for new requests | Fewer pages and physical visits | Arranging guardian access to the student's device | Study B visit/print counts and interviews |
| Show terms and status before signing/review | Better comprehension | Small screens, unfamiliar terms, and accessibility barriers | Study A walkthroughs; Study B comprehension/tasks |
| Preserve one signed record for sequential review | Consistent review material | New correction/cancellation steps | Study B technical tests and resubmission evidence |
| Move signing ahead of Dean approval | Potentially different total processing time | Waiting for guardian signing can delay the Dean queue | Study B total and stage times including guardian waiting |

## Handoff record — not yet populated

Record the Study A commit/tag, evidence locators, mockup version, review date/roles, unresolved concerns and dispositions, and the implementation issue/revision receiving the package. Study B must then record the actual tested implementation commit separately. A completed document is not evidence of acceptance or field readiness.
