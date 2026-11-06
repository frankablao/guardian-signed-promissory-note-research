# Research quality checks

Use the sections relevant to the deliverable. These checks supplement the issue and approved protocol; they do not establish new sample sizes, collection permissions, or statistical methods.

## Literature and citations

Verify retained claims against the actual source, preferably the original publication. Record search locations, terms, dates, selection criteria, and reasons for exclusions at an appropriate level. Check bibliographic details and stable URLs/DOIs. Search snippets and a citation in another paper do not establish that a source supports the claim.

Separate literature findings, local observations, and proposed design choices. Explain the local gap without unsupported novelty claims. Match in-text citations and reference entries. Flag inaccessible or unverifiable sources rather than supplying invented details.

## Protocol and instruments

Connect each outcome and instrument to a research question. Define population, eligibility, recruitment, sampling rationale, primary outcome, time origin, observation window, denominators, exclusions, missing data, and pending-case treatment before affected collection/analysis. Justify sample size from feasibility, variability, precision or the planned analysis rather than convention alone.

Measure the whole process from initial submission, including guardian waiting time, and report stage time separately. Document workload, staffing, calendar/request windows, policy changes, and nonrandomized-comparison limitations. Legacy cases are not automatically comparable controls.

Check institutional research/data-access requirements before participant recruitment or research use of identifiable administrative records. Record actual approval evidence or an applicable institutional determination. Separate voluntary research consent from payment-term acceptance and service eligibility. Resolve applicable minor-participant requirements when relevant.

Instruments should distinguish logs, observations, and self-reports; define units and missing-value codes. Cover students, guardians, and approving staff appropriately. Verify validated instruments' original scoring/use guidance and document adaptations. Comprehension covers deferred amount, deadline, status, and signing meaning. Use synthetic dry runs before approved participant pilots.

## Artifact and field evidence

Link artifact claims to the implementation commit/release, environment, test procedure, and actual result, including failures and untested cases. Check the full #740 requirements, not only the happy path. Sanitize screenshots and examples with synthetic records.

For pilot/baseline/field evidence, retain dates, cohort selection, recruitment/nonparticipation, instrument and artifact versions, deviations, and data-quality limitations. Document pilot defects and their disposition before claiming field readiness. If rollout prevents prospective baseline collection, document a justified protocol amendment instead of inventing baseline observations.

## Analysis and reporting

Follow the prespecified analysis; label and justify departures and exploratory work. Include missing/pending cases according to the protocol, correct denominators, effect estimates, and uncertainty. Distinguish requests from participants and account for repeated observations when relevant to the method. Avoid unsupported causal or statistical-significance language.

Record qualitative coding decisions and theme development. Keep quotations de-identified and within granted use. Integrate themes with operational results while preserving the difference between perceptions, test outcomes, and measured effects.

For executable analyses, record input versions, transformations, dependencies, and commands sufficient to reproduce permitted outputs. Test meaningful calculations against known synthetic examples. Clearly label synthetic demonstration outputs so they cannot be mistaken for observed findings.

Trace manuscript numbers, tables, figures, and conclusions to evidence. Use prospective language for unfinished work. Explain institutional and design limits, including student-session identity limits and guardian/device access burden. Recommendations must follow the local findings.

## Public artifacts and document checks

Keep raw identifiable records, actual signatures, account identifiers, and re-identification keys in approved restricted storage outside Git. Removing names alone does not demonstrate anonymization; review small groups, quotations, screenshots, dates and financial combinations for disclosure risk. Use synthetic fixtures or appropriately anonymized aggregates in public reproduction materials.

Run `mkdocs build --clean` when manuscript/navigation/configuration changes warrant it, and inspect affected rendered pages, tables, figures and links. If dependencies are unavailable, report the check as not run. Build success does not verify citations, privacy, or empirical claims; report those checks separately.
