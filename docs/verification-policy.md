# SNote Verification Policy

Version 1.0 — 3 November 2026
Owner: SOLIDMOVE TECHNOLOGY LIMITED
Applies to: all products, services, platforms, systems and infrastructure claimed on behalf of the Company.

## 1. Purpose

This policy defines how SNote decides whether an item may be described as an official SOLIDMOVE TECHNOLOGY LIMITED product. It exists to stop unverified claims from entering public company materials.

## 2. Core principle

> No sufficient evidence + no required SNote verification + no authorized human approval = no official SolidMove product status.

Technical work is not approval. A repository, deployment, API, design, or AI-generated recommendation does not by itself make something a company product.

## 3. What must be established

Every record is judged against four groups of criteria:

**3.1 Ownership**
- The legal owner of the work is identified.
- The Company's claim to it is supported by evidence (registration, assignment, contract, or founder attestation).
- Attribution to SOLIDMOVE TECHNOLOGY LIMITED is explicit.

**3.2 Technical evidence**
- The item exists and is reachable or reproducible.
- The repository or deployment location is recorded.
- The described function matches what actually runs.
- No unverifiable capability claims are made.

**3.3 Company policy**
- The item is consistent with the Company's published structure and division boundaries.
- Naming is consistent with official brand assets.
- Security and access controls are described, not assumed.

**3.4 Country and regulatory review**
- Jurisdiction is identified (Nigeria unless stated otherwise).
- Applicable requirements (CAMA 2020, NDPR/NDPA, KYC/AML where relevant) are reviewed in `country-policy.md`.

## 4. Status values

| Status | Meaning | Who may set it |
| --- | --- | --- |
| Unverified | Recorded, no evidence reviewed | SNote maintainer |
| Pending Verification | Under review, evidence incomplete | SNote maintainer |
| SNote Verified | Evidence reviewed and accepted | SNote maintainer |
| Official SolidMove Product | All criteria met plus founder approval | Founder only, per `approval-policy.md` |
| Rejected | Reviewed, not accepted | SNote maintainer with reason |
| Historical | Superseded or retired, retained for traceability | SNote maintainer |
| Not Owned by SolidMove | Found not to belong to the Company | Founder or SNote maintainer |

## 5. Rules of evidence

1. **Absence of evidence is not evidence.** Missing items are recorded as `Pending Verification`, never inferred.
2. **No forward-dating.** A record states the status at the time of writing, with a date.
3. **No borrowed credibility.** A plan, draft, or roadmap may be recorded as a plan; it may not be recorded as a delivered product.
4. **Negatives are preserved.** Rejections and corrections stay in the record for traceability.
5. **Confidential material stays out.** This repository is public; see `records/README.md`.

## 6. Review and change

- A record is re-reviewed when the item changes materially or when its next review date passes.
- Status changes are made by editing the record file, with the change described in the commit message.
- Disagreements are escalated to the Founder rather than resolved between maintainers.

## 7. What verification does not do

SNote records status. It does not create ownership, grant rights, or substitute for corporate authority. Only the Company, through its authorized officer, can confer official product status.
