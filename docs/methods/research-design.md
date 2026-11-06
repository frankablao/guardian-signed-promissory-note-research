# Proposed Research Design at Mabini Colleges, Inc.

The study proposes design science research linking local problem investigation, artifact development, technical verification, participant evaluation, and evidence-supported design lessons. Gregor and Hevner discuss positioning artifact-based contributions [1]; FEDS supports planning artifact evaluation [2]. These references provide methodological context, not findings about Mabini Colleges, Inc.; see the [references](../references.md).

The proposed phases are local workflow validation, design/development, synthetic technical verification, approved pilot evaluation, approved field evaluation, and analysis/reporting. The [four research questions](../introduction/research-questions.md) cover operational outcomes, participant experience, technical integrity, and signing-context limitations. No phase is claimed complete here.

## Proposed comparison

Prefer a prospective evaluation with clearly defined baseline and post-rollout observation periods. Use comparable periods where possible and record workload, staffing, request characteristics, and policy changes that may influence outcomes.

Existing legacy requests may provide additional context, but they are not automatically an equivalent control group: their age and approval stage may differ from new electronic requests. Describe a nonrandomized comparison as such and avoid attributing every observed change to the software.

Measure the whole process from initial request submission, including time awaiting guardian signing. Report stage-level times separately. Comparing only time after signing would omit a potentially substantial part of the new process.

## Proposed artifact boundary

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

The [scope and pending protocol decisions](participants-and-data.md) limit this design to institutionally confirmed units and observation periods. Artifact implementation and verification remain separate work in mc-portal #740 and research issue #6.
