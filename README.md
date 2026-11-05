# Design and Evaluation of a Guardian-Signed Electronic Promissory Note Workflow at Mabini Colleges, Inc.

This repository contains the proposed single-institution design science study at **Mabini Colleges, Inc.** It does not report completed implementation, institutional approval, recruitment, data collection, or demonstrated benefits.

The [working proposal](src/guardian-signed-promissory-note-research-proposal.md) is versioned and available to collaborators. The [manuscript](docs/index.md) follows the existing IMRaD organization. The [source register](src/README.md) distinguishes the proposal from the optional local inventory/POS example.

The intended participants are eligible local students, participating guardians, Dean reviewers, and President's Office personnel. Included departments, academic levels, sample size, and baseline/post-rollout observation periods require institutional evidence and protocol confirmation; participation by all college units is not assumed.

The [aim, objectives and RQ1–RQ4](docs/introduction/research-questions.md) cover workflow time and burden, usability and comprehension, signed-record integrity and approval sequence, and limitations of guardian signing within a student session. The [scope and pending decisions](docs/methods/participants-and-data.md) define inclusions and exclusions. Findings will be bounded to participating units and observation periods at Mabini Colleges, Inc.

The proposed sequence is student request → guardian signing on the student's device within the authenticated student session → Dean approval → President's Office approval. Guardian identity is not independently authenticated. Guardian accounts, external signing links, OTP, external signature providers, and retroactive legacy conversion are excluded. Artifact implementation belongs to [mc-portal #740](https://github.com/frankkivenablao-mabini/mc-portal/issues/740).

## Study status and evidence

The [research roadmap](https://github.com/frankkivenablao-mabini/guardian-signed-promissory-note-research/issues/1) tracks literature, protocol, instruments, artifact verification, fieldwork, analysis, and final manuscript work. Those tasks remain separate from this foundation. Potential benefits for local students, guardians, and approving offices are questions for evaluation. Approval speed will not establish repayment, retention, or academic benefits.

Keep identifiable student financial records, account identifiers, linkage keys, and actual signatures outside Git and published pages. Public examples must be synthetic or appropriately anonymized within approved use.

## Build the manuscript

The repository workflow installs MkDocs and Material and builds the site with:

```sh
python -m pip install mkdocs mkdocs-material
mkdocs build --clean
```

For local preview, run `mkdocs serve`. Build output is generated in `site/`; it is not manuscript source. A successful build verifies rendering, not research validity. The existing deployment workflow runs only after a PR is merged into `main`.
