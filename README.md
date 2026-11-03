# SNote

**SNote — SolidMove verification and evidence registry**

SNote is the public verification register for products, services, platforms, systems and infrastructure associated with **SOLIDMOVE TECHNOLOGY LIMITED** (RC 9619709), the technology, software and systems architecture company behind the **Steph-Tech** ecosystem.

SNote records one thing and records it honestly: whether a given item has been evidenced, reviewed and approved as an official SolidMove product, and what the current verification status is.

## What SNote is not

- It is not proof of ownership on its own. Ownership comes from the Company's legal records (CAC registration, contracts, assignments).
- It is not a marketing page. An item listed here is not automatically an official product.
- It is not a place for confidential evidence. This repository is public and must never contain secrets.

## Verification principle

> No sufficient evidence + no required SNote verification + no authorized human approval = no official SolidMove product status.

AI assists. Humans decide.

## Repository structure

```
snote/
├── README.md                             <- this file
├── LICENSE
├── docs/
│   ├── verification-policy.md            <- how verification works
│   ├── verification-record-template.md   <- blank record template
│   ├── approval-policy.md                <- who may approve and how
│   └── country-policy.md                 <- Nigerian legal, NDPR, KYC/AML baseline
├── schemas/
│   └── verification-record.schema.json   <- machine-readable record schema
└── records/
    ├── README.md                         <- record index and status legend
    └── solidmove-app.md                  <- individual verification record
```

## Status vocabulary

| Status | Meaning |
| --- | --- |
| Unverified | Recorded, no evidence reviewed yet |
| Pending Verification | Under review; evidence incomplete |
| SNote Verified | Evidence reviewed and accepted |
| Official SolidMove Product | All requirements met, including founder approval |
| Rejected | Reviewed and not accepted |
| Historical | No longer active, kept for traceability |
| Not Owned by SolidMove | Reviewed and found not to belong to the Company |

## Governance path

Candidate → OnSpace → SNote evidence review → Company policy → Country/regulatory policy → Ownership + technical evidence → Pyramide → DPY Core → SNote verification → Founder approval → Official SolidMove Product

## Adding a record

1. Copy `docs/verification-record-template.md`.
2. File it under `records/` as `<asset-name>.md`.
3. Fill in only what you can evidence. Where evidence is missing, write `Pending Verification` — never a guess.
4. Reference the criteria in `docs/verification-policy.md`.
5. Approval is recorded only under `docs/approval-policy.md`, by an authorized person.

## Contact

SOLIDMOVE TECHNOLOGY LIMITED, Benin City, Edo State, Nigeria
Email: solidmovetechnologylimited@gmail.com
Web: https://solidmove-technology-limited.github.io/website/
