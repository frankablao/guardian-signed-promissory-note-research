# Requirements and Design of a Guardian-Signed Electronic Promissory Note Workflow at Mabini Colleges, Inc.

**Study A — local needs, design basis, and anticipated benefits.** This repository develops evidence-supported requirements and a formatively validated design for Mabini Colleges, Inc. Its result will guide [mc-portal #740](https://github.com/frankkivenablao-mabini/mc-portal/issues/740). It does not report completed research, institutional approval, implementation, or demonstrated benefits.

[Study B: implementation evaluation](https://github.com/frankkivenablao-mabini/guardian-signed-promissory-note-evaluation) is maintained separately. The sequence is Study A → implementation → Study B field evaluation; Study B plans and collects its approved baseline before rollout. See the [two-study brief](docs/study-split.md) for timing, evidence ownership, and reuse rules.

Start with the [research questions](docs/introduction/research-questions.md), [draft protocol](docs/protocol.md), [implementation handoff](docs/design/implementation-handoff.md), and [roadmap](docs/roadmap.md). The [working proposal](src/guardian-signed-promissory-note-research-proposal.md) follows the new scope. The earlier combined proposal is preserved in the [source archive](src/archive/combined-study-proposal.md).

Study A investigates the current process, derives traceable requirements from local evidence and literature, and validates diagrams/mockups through stakeholder walkthroughs. It can identify needed changes to #740 through explicit decisions. It cannot establish operational improvement from a mockup or stakeholder agreement.

The proposed workflow retains student-session guardian signing, preserved signed terms, sequential Dean/President approvals, and legacy compatibility. Guardian identity is not independently authenticated. Keep identifiable financial records, account identifiers, linkage keys, and actual signatures outside Git. Included units, sample, observation dates, permissions, and collection arrangements remain unresolved in the draft protocol.

## Build and preview

```sh
python -m pip install -r requirements.txt
python -m mkdocs build --clean --strict
python -m mkdocs serve
```

Manuscript pages live in `docs/`; source planning lives in `src/`. A build checks rendering, not research validity. The existing site deployment workflow remains unchanged. Use a branch and pull request for further changes, and preserve ongoing literature work when integrating the split.
