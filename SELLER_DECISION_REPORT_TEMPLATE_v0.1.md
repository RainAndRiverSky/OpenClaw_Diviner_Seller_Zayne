# Seller Decision Report Template v0.1

**Identity:** Seller / Zayne  
**Layer:** Commerce  
**Document type:** Reusable governance report template  
**Template version:** 0.1  
**Status:** Foundational draft  
**Date:** 2026-06-13  

## Purpose

This template defines the standardized Seller Decision Report produced after
Seller/Zayne completes an opportunity candidate evaluation.

The completed report records the candidate reviewed, evidence considered,
freshness and uncertainty, relationships and impacts, mandatory gate results,
risk classification, scores, critical and persistent findings, final
disposition, human sign-off, and governance audit trail.

The report is a governance record. It does not authorize product creation,
listing, publication, external communication, billing, payment, fulfillment, or
other external action.

## Governing Documents

Complete this template in accordance with:

- `SELLER_IDENTITY_STABILIZATION_v0.1.md`
- `SELLER_ARCHIVE_RELEVANCE_REVIEW_v0.1.md`
- `SEEKER_TO_SELLER_OPPORTUNITY_CANDIDATE_GOVERNANCE_v0.1.md`
- `SELLER_EVALUATION_STANDARD_v0.1.md`
- `SELLER_REVIEW_WORKFLOW_v0.1.md`

This template records the application of those documents. It does not change
their authority boundaries, mandatory gates, scoring rules, risk treatment,
decision thresholds, or human-review requirements.

## Completion Rules

- Complete every required field.
- Use `None identified` when a reviewed category has no findings.
- Use `Unknown` when available evidence cannot support a conclusion.
- Use `Not applicable` only with a brief rationale.
- Distinguish verified facts, source claims, corroborated evidence, inference,
  assumptions, disputes, unknowns, stale evidence, and inadmissible evidence.
- Identify the source or governance record supporting each material finding.
- Preserve unfavorable evidence, counterevidence, uncertainty, and disagreement.
- Do not leave a material omission implicit; enter it in the Missing Evidence
  Register.
- Do not treat a score as objective truth or as the sole basis for disposition.
- Do not remove a prior rejection or blocking finding. Record its current status.
- Select exactly one top-level final disposition.

## Candidate Reference Requirements

Every completed report must:

- Use the stable candidate identifier established by the candidate dossier.
- Identify the exact candidate version or review state evaluated.
- Reference the Seeker/Xavier transfer declaration.
- Reference the Seller/Zayne intake disposition.
- Identify any prior Seller Decision Reports for the same candidate.
- Preserve lineage to any earlier, rejected, superseded, or materially related
  candidate.
- Identify the evidence set and decision version on which the report is based.

A revised or resubmitted candidate must not receive a new reference merely to
conceal continuity with an earlier candidate or persistent finding.

## Review Timestamp Requirements

Every material review event must include:

- Calendar date.
- Time.
- Time zone.
- Accountable identity or reviewer.
- Review event or decision recorded.

The completed report must identify, at minimum:

- Discovery timestamp, if supplied.
- Transfer timestamp.
- Seller intake timestamp.
- Evaluation start timestamp.
- Evidence freshness review timestamp.
- Evaluation completion timestamp.
- Decision issuance timestamp.
- Human-review request timestamp, when applicable.
- Human sign-off timestamp, when applicable.
- Expiration or next-review timestamp, when applicable.

If an original event time is unavailable, record `Unknown` and identify the
governance consequence.

---

# Seller Decision Report

## Report Control

| Field | Entry |
|---|---|
| Report identifier | `[Required: stable report reference]` |
| Report version | `[Required]` |
| Template version | `0.1` |
| Report status | `[Draft / Pending Human Review / Final / Superseded / Expired]` |
| Candidate identifier | `[Required]` |
| Candidate version or review state | `[Required]` |
| Prior report identifiers | `[None or references]` |
| Supersedes report | `[None or reference]` |
| Prepared by | `Seller / Zayne` |
| Decision authority | `[Seller/Zayne / Human reviewer / OpenClaw governance, as applicable]` |
| Confidentiality or visibility limits | `[Required: state limits or None]` |

## 1. Candidate Information

| Field | Entry |
|---|---|
| Candidate identifier | `[Required]` |
| Candidate title | `[Required: neutral title]` |
| Candidate classification | `[Required]` |
| Secondary classifications | `[None or classifications]` |
| Submitting identity | `[Required]` |
| Discovery date and time | `[Required or Unknown]` |
| Transfer date and time | `[Required]` |
| Seeker/Xavier confidence | `[Exploratory / Supported / Strong]` |
| Observed opportunity | `[Required summary]` |
| Intended beneficiary or audience | `[Required]` |
| Use context | `[Required]` |
| Candidate form or forms evaluated | `[Required or Unclassified]` |
| Requested Seller decision | `[Required]` |
| Related candidate references | `[None or references]` |

### Candidate Reference Statement

`[State how this report links to the candidate dossier, transfer declaration,
intake record, prior reports, and any materially related candidate.]`

### Candidate Lineage

| Related record | Relationship | Current relevance |
|---|---|---|
| `[Reference or None]` | `[Prior version / Resubmission / Superseded candidate / Related candidate]` | `[Required]` |

## 2. Evaluation Metadata

| Field | Entry |
|---|---|
| Seller intake disposition | `[Accepted / Returned / Rejected / Deferred / Escalated]` |
| Intake record reference | `[Required]` |
| Intake timestamp | `[Date, time, time zone]` |
| Evaluation start timestamp | `[Date, time, time zone]` |
| Evaluation completion timestamp | `[Date, time, time zone]` |
| Decision issuance timestamp | `[Date, time, time zone]` |
| Evaluation scope | `[Required]` |
| Matters expressly outside scope | `[Required or None]` |
| Governing document versions | `[Required]` |
| Evidence-set reference or version | `[Required]` |
| Evaluation owner | `Seller / Zayne` |
| Dependency owners consulted | `[Required or None]` |
| Human review status | `[Not required / Required / Requested / Completed]` |
| Report expiration or next review | `[Date, condition, or None]` |

### Evaluation Question

`[State the bounded commerce-governance question evaluated.]`

### Evaluation Limitations

`[State material scope, evidence, authority, dependency, or timing limitations.]`

## 3. Evidence Summary

### Overall Evidence Assessment

`[Summarize the quality, relevance, provenance, independence, completeness, and
limitations of the evidence considered.]`

### Material Evidence Register

| Evidence reference | Source and provenance | Proposition supported | Evidence status | Freshness status | Material limitations |
|---|---|---|---|---|---|
| `[Required]` | `[Required]` | `[Required]` | `[Verified / Source claim / Corroborated / Inferred / Assumed / Disputed / Unknown / Stale / Inadmissible]` | `[Current / Expiring / Stale / Unknown]` | `[Required or None]` |

### Counterevidence

| Evidence reference | Proposition challenged | Evidence status | Material effect on evaluation |
|---|---|---|---|
| `[Reference or None]` | `[Required]` | `[Required]` | `[Required]` |

### Excluded Evidence

| Evidence reference | Exclusion reason | Status | Effect on evaluation |
|---|---|---|---|
| `[Reference or None]` | `[Stale / Inadmissible / Duplicative origin / Irrelevant / Untraceable / Other]` | `[Required]` | `[Required]` |

## 4. Evidence Freshness Status

### Overall Freshness Determination

| Field | Entry |
|---|---|
| Overall status | `[Current / Partially current / Expiring / Stale / Unknown]` |
| Freshness review timestamp | `[Date, time, time zone]` |
| Earliest material expiration | `[Date, condition, or Unknown]` |
| Revalidation required before progression | `[Yes / No]` |
| Freshness reviewer | `[Required]` |

### Time-Sensitive Evidence

| Evidence reference | Relevant proposition | Freshness measured from | Expiration or invalidating event | Current status | Required action |
|---|---|---|---|---|---|
| `[Reference or None]` | `[Required]` | `[Date or event]` | `[Date or condition]` | `[Current / Expiring / Stale / Unknown]` | `[None / Revalidate / Exclude / Return / Defer / Escalate]` |

### Freshness Rationale

`[Explain why the evidence is current enough, or not current enough, for this
decision stage.]`

## 5. Verified Facts

Record only facts confirmed by sufficiently authoritative, traceable, and current
evidence for this decision stage.

| Fact identifier | Verified fact | Supporting evidence | Verifying authority | Verification timestamp | Scope or limitation |
|---|---|---|---|---|---|
| `[Required or None identified]` | `[Required]` | `[Reference]` | `[Required]` | `[Date, time, time zone]` | `[Required or None]` |

### Verification Boundary

`[State what the verified facts establish and what they do not establish.]`

## 6. Inferred Relationships

Record relationships reasonably derived from evidence but not directly
established as verified facts.

| Relationship identifier | Inferred relationship | Evidence basis | Reasoning | Confidence | Decision effect |
|---|---|---|---|---|---|
| `[Required or None identified]` | `[Required]` | `[Reference]` | `[Required]` | `[Low / Moderate / High]` | `[Required]` |

### Inference Limitations

`[Identify assumptions, alternative interpretations, or evidence that would
confirm or disprove the inferences.]`

## 7. Uncertain Evidence

Include disputed, assumed, unknown, weakly supported, contradictory, stale, or
otherwise uncertain evidence that materially affects the review.

| Uncertainty identifier | Proposition or evidence | Uncertainty type | Basis of uncertainty | Affected review matter | Current treatment |
|---|---|---|---|---|---|
| `[Required or None identified]` | `[Required]` | `[Disputed / Assumed / Unknown / Contradictory / Stale / Authenticity concern / Other]` | `[Required]` | `[Gate / Score / Risk / Impact / Disposition]` | `[Required]` |

### Material Disagreements

| Parties or records | Matter disputed | Each position | Governance effect | Resolution owner |
|---|---|---|---|---|
| `[None or required entry]` | `[Required]` | `[Required]` | `[Required]` | `[Required]` |

## 8. Relationship Mapping Summary

### Relationship Overview

`[Summarize how the opportunity, evidence, audience, product forms, claims,
rights, dependencies, risks, and affected parties relate.]`

### Material Relationship Register

| Relationship identifier | Origin | Related matter | Relationship type | Relationship status | Evidence | Dependency owner | Governance effect |
|---|---|---|---|---|---|---|---|
| `[Required]` | `[Opportunity / Evidence / Claim / Product form / Risk / Decision]` | `[Required]` | `[Supports / Depends on / Constrains / Contradicts / Affects / Requires authority from]` | `[Verified / Supported / Inferred / Assumed / Disputed / Unknown]` | `[Reference]` | `[Identity, layer, or None]` | `[Required]` |

### Dependency Summary

| Dependency | Accountable owner | Required stage | Current status | Consequence if unresolved or denied |
|---|---|---|---|---|
| `[Required or None identified]` | `[2B / Keeper/Caleb / Nier / 9S / A2 / Thomas / OpenClaw / Other authorized owner]` | `[Before scoring / Before disposition / Before later progression]` | `[Satisfied / Pending / Disputed / Denied / Unknown]` | `[Required]` |

## 9. Direct Impact Assessment

Direct impacts immediately affect a claim, user, offer term, right, obligation,
dependency owner, or next-stage decision.

| Impact identifier | Originating matter | Directly affected party or decision | Impact description | Evidence and status | Likelihood | Severity | Reversibility | Governance effect |
|---|---|---|---|---|---|---|---|---|
| `[Required or None identified]` | `[Required]` | `[Required]` | `[Required]` | `[Reference and status]` | `[Unknown / Low / Moderate / High]` | `[Low / Moderate / High / Critical]` | `[Reversible / Partly reversible / Difficult to reverse / Irreversible / Unknown]` | `[Required]` |

### Direct Impact Conclusion

`[Summarize material direct effects and their influence on gates, scores, risks,
conditions, or disposition.]`

## 10. Indirect Impact Assessment

Indirect impacts affect another matter through one material dependency,
interpretation, or downstream use.

| Impact identifier | Originating matter | Intervening relationship | Affected party or decision | Impact description | Evidence and status | Likelihood | Severity | Governance effect |
|---|---|---|---|---|---|---|---|---|
| `[Required or None identified]` | `[Required]` | `[Required]` | `[Required]` | `[Required]` | `[Reference and status]` | `[Unknown / Low / Moderate / High]` | `[Low / Moderate / High / Critical]` | `[Required]` |

### Indirect Impact Conclusion

`[Summarize material indirect effects and their influence on the evaluation.]`

## 11. Transitive Impact Assessment

Transitive impacts may propagate across multiple dependencies, layers, parties,
or later decisions.

| Impact identifier | Originating matter | Impact path | Ultimately affected party or decision | Impact description | Evidence and status | Likelihood | Severity | Critical path | Governance effect |
|---|---|---|---|---|---|---|---|---|---|
| `[Required or None identified]` | `[Required]` | `[Required sequence of relationships]` | `[Required]` | `[Required]` | `[Reference and status]` | `[Unknown / Low / Moderate / High]` | `[Low / Moderate / High / Critical]` | `[Yes / No]` | `[Required]` |

### Transitive Impact Conclusion

`[Summarize material propagated effects, affected OpenClaw identities, and any
heightened scrutiny or sign-off required.]`

## 12. Missing Evidence Register

| Missing evidence identifier | Missing proposition, fact, or decision | Why it matters | Current status | Affected gate, score, risk, or decision | Resolution owner | Evidence or decision required | Review consequence | Failure outcome | Review or expiration condition |
|---|---|---|---|---|---|---|---|---|---|
| `[Required or None identified]` | `[Required]` | `[Required]` | `[Unknown / Assumed / Disputed / Stale / Not obtained]` | `[Required]` | `[Required]` | `[Required]` | `[Blocks / Limits score / Conditions approval / Requires return / Requires deferral / Requires escalation]` | `[Required]` | `[Required]` |

### Missing Evidence Conclusion

`[State whether the missing evidence prevents scoring, approval, sign-off, or
later progression. Missing knowledge must not be treated as evidence of low
risk.]`

## 13. Mandatory Gate Results

| Gate | Result | Evidence considered | Missing or disputed matter | Impact considered | Required governance effect |
|---|---|---|---|---|---|
| A. Evidence integrity | `[Pass / Unresolved / Dependency decision required / Fail]` | `[References]` | `[None or required]` | `[Required]` | `[Continue / Investigate / Return / Defer / Reject / Escalate]` |
| B. Lawful and ethical basis | `[Pass / Unresolved / Dependency decision required / Fail]` | `[References]` | `[None or required]` | `[Required]` | `[Continue / Investigate / Return / Defer / Reject / Escalate]` |
| C. Authority alignment | `[Pass / Unresolved / Dependency decision required / Fail]` | `[References]` | `[None or required]` | `[Required]` | `[Continue / Investigate / Return / Defer / Reject / Escalate]` |
| D. Rights viability | `[Pass / Unresolved / Dependency decision required / Fail]` | `[References]` | `[None or required]` | `[Required]` | `[Continue / Investigate / Return / Defer / Reject / Escalate]` |
| E. User protection | `[Pass / Unresolved / Dependency decision required / Fail]` | `[References]` | `[None or required]` | `[Required]` | `[Continue / Investigate / Return / Defer / Reject / Escalate]` |
| F. Feasible review path | `[Pass / Unresolved / Dependency decision required / Fail]` | `[References]` | `[None or required]` | `[Required]` | `[Continue / Investigate / Return / Defer / Reject / Escalate]` |

### Gate Conclusion

| Field | Entry |
|---|---|
| All gates permit scoring | `[Yes / No]` |
| Failed mandatory gates | `[None or list]` |
| Unresolved gates | `[None or list]` |
| Gate-based override | `[None / Reject / Escalate / Other governed effect]` |
| Gate reviewer rationale | `[Required]` |

## 14. Risk Classification

### Risk Register

| Risk identifier | Risk description | Evidence or condition | Affected parties or decisions | Likelihood | Likelihood value | Impact | Impact value | Exposure | Risk band | Owner | Current treatment |
|---|---|---|---|---|---:|---|---:|---:|---|---|---|
| `[Required or None identified]` | `[Required]` | `[Reference]` | `[Required]` | `[Unknown / Low / Moderate / High]` | `[3 / 1 / 2 / 3]` | `[Low / Moderate / High / Critical]` | `[1 / 2 / 3 / 4]` | `[Likelihood x impact]` | `[Low / Moderate / High / Critical]` | `[Required]` | `[Required]` |

### Risk Summary

| Field | Entry |
|---|---|
| Highest unresolved risk band | `[None / Low / Moderate / High / Critical]` |
| Applicable risk penalty | `[0 / 5 / 15 / No numeric result may approve]` |
| Risk overrides triggered | `[None or list]` |
| Unresolved high risks | `[None or list]` |
| Unresolved critical risks | `[None or list]` |
| Critical paths affected | `[None or list]` |
| Human review required by risk | `[Yes / No]` |

### Risk Classification Rationale

`[Explain the risk classification, including how uncertainty and unknown
likelihood were treated.]`

## 15. Evaluation Scores

### Dimension Scores

| Dimension | Weight | Rating (0-5) | Weighted points | Evidence and freshness | Counterevidence or limitation | Rationale | Minimum met |
|---|---:|---:|---:|---|---|---|---|
| Need and value clarity | 15 | `[Required]` | `[Required]` | `[References]` | `[Required or None]` | `[Required]` | `[Yes / No]` |
| Evidence strength and confidence | 15 | `[Required]` | `[Required]` | `[References]` | `[Required or None]` | `[Required]` | `[Yes / No]` |
| Audience and use-context fit | 10 | `[Required]` | `[Required]` | `[References]` | `[Required or None]` | `[Required]` | `[Yes / No]` |
| Offer-form and productization fit | 15 | `[Required]` | `[Required]` | `[References]` | `[Required or None]` | `[Required]` | `[Yes / No]` |
| Differentiation and claim defensibility | 10 | `[Required]` | `[Required]` | `[References]` | `[Required or None]` | `[Required]` | `[Yes / No]` |
| Rights, compliance, and platform viability | 15 | `[Required]` | `[Required]` | `[References]` | `[Required or None]` | `[Required]` | `[Yes / No]` |
| Operational and quality feasibility | 10 | `[Required]` | `[Required]` | `[References]` | `[Required or None]` | `[Required]` | `[Yes / No]` |
| Financial coherence | 10 | `[Required]` | `[Required]` | `[References]` | `[Required or None]` | `[Required]` | `[Yes / No]` |

### Score Summary

| Field | Entry |
|---|---|
| Base evaluation score | `[0-100, one decimal place at most]` |
| Highest unresolved risk band | `[Required]` |
| Risk penalty | `[Required]` |
| Adjusted evaluation score | `[Required or Not approvable due to override]` |
| All dimension minimums met | `[Yes / No]` |
| Approval threshold met | `[Yes / No]` |
| Strong-approval threshold met | `[Yes / No]` |
| Score overridden | `[No / Yes: reason]` |

### Scoring Limitation Statement

`[State the principal evidence, dependency, uncertainty, and judgment limitations
on the scores. Confirm that the score was not treated as the sole decision
basis.]`

## 16. Critical Findings

Record findings that materially control the disposition, require heightened
scrutiny, affect a critical path, or cannot be safely omitted from later review.

| Finding identifier | Critical finding | Evidence | Affected gate, risk, score, party, or decision | Severity | Required response | Owner | Status |
|---|---|---|---|---|---|---|---|
| `[Required or None identified]` | `[Required]` | `[Reference]` | `[Required]` | `[High / Critical]` | `[Required]` | `[Required]` | `[Open / Pending / Resolved / Escalated]` |

### Critical Findings Conclusion

`[Explain how the critical findings influence or control the final disposition.]`

## 17. Rejection Findings: Persistent Record

This section must preserve all prior and current rejection or decisive blocking
findings associated with the candidate. A later approval, resubmission, or revised
score does not erase them.

| Finding identifier | Original finding | Original report or decision reference | Original date | Supporting evidence | Permanent or potentially curable | Current status | Resolution or supersession evidence | Current governing effect |
|---|---|---|---|---|---|---|---|---|
| `[Required or None identified]` | `[Required]` | `[Required]` | `[Date]` | `[Reference]` | `[Permanent / Potentially curable]` | `[Open / Resolved / Superseded / Determined inapplicable]` | `[Required if status changed]` | `[Required]` |

### Evidence or Premises Prohibited from Reuse

| Evidence or premise | Reason reuse is prohibited without correction | Correction or new evidence required |
|---|---|---|
| `[None or required entry]` | `[Required]` | `[Required]` |

### Persistent Record Statement

`[Confirm that prior rejection findings were reviewed and state whether any
remain controlling. Explain the visible governance basis for every status
change.]`

## 18. Final Disposition

Select exactly one:

- [ ] **APPROVE**
- [ ] **INVESTIGATE FURTHER**
- [ ] **REJECT**
- [ ] **ESCALATE**

### Governance Subtype

Use the subtype needed to preserve the more specific outcome required by the
Seller Evaluation Standard and Seller Review Workflow.

| Top-level disposition | Permitted governance subtype |
|---|---|
| APPROVE | `[Ordinary approval / Strong approval / Conditional approval]` |
| INVESTIGATE FURTHER | `[Seller-led commerce investigation / Return for discovery investigation / Defer pending dependency review]` |
| REJECT | `[Intake rejection / Evaluation rejection]` |
| ESCALATE | `[Human review / OpenClaw governance / Dependency authority dispute / Other authorized escalation]` |

**Selected governance subtype:** `[Required]`

### Disposition Rationale

`[State the accountable decision rationale using the complete governance record,
not the score alone.]`

### Decision Basis

| Decision factor | Conclusion |
|---|---|
| Intake eligibility | `[Required]` |
| Evidence sufficiency and freshness | `[Required]` |
| Relationship and impact findings | `[Required]` |
| Mandatory gates | `[Required]` |
| Scores and minimums | `[Required]` |
| Risk and overrides | `[Required]` |
| Persistent findings | `[Required]` |
| Dependency decisions | `[Required]` |
| Human-review requirement | `[Required]` |

### Decision Boundaries

| Field | Entry |
|---|---|
| Governance progression permitted | `[Required]` |
| Candidate form, claim, scope, or condition covered | `[Required]` |
| Matters not approved or decided | `[Required]` |
| Prohibited claims or representations | `[Required or None]` |
| Outstanding dependencies | `[Required or None]` |
| Conditions for continuation | `[Required or None]` |
| Failure outcome if conditions are not met | `[Required or None]` |
| Evidence or decision that would change the disposition | `[Required or None]` |
| Expiration or revalidation trigger | `[Required]` |
| Human sign-off required before effect | `[Yes / No]` |

### Disposition-Specific Requirements

#### If APPROVE

- Approved only for governed offer development: `[Confirm]`
- Base and adjusted thresholds satisfied: `[Yes / No, with rationale]`
- Dimension minimums satisfied: `[Yes / No, with rationale]`
- Unresolved moderate risks and owners: `[None or list]`
- Candidate form or forms approved for further governance work: `[Required]`
- Claims currently supportable: `[Required]`
- Conditions attached to approval: `[None or required]`

#### If INVESTIGATE FURTHER

- Exact unanswered questions: `[Required]`
- Evidence or decision needed: `[Required]`
- Accountable identity or layer: `[Required]`
- Dimensions, gates, risks, or findings that may change: `[Required]`
- Investigation boundary: `[Required]`
- Expected decision after investigation: `[Required]`
- Review or expiration condition: `[Required]`

#### If REJECT

- Decisive defect: `[Required]`
- Supporting evidence: `[Required]`
- Governing rejection basis: `[Required]`
- Permanent or potentially curable: `[Required]`
- Conditions for any materially revised candidate: `[Required or None]`
- Evidence or premise prohibited from reuse without correction: `[Required or None]`

#### If ESCALATE

- Exact decision or exception required: `[Required]`
- Accountable authority: `[Required]`
- Evidence and risks involved: `[Required]`
- Affected parties and decisions: `[Required]`
- Consequence of approval, deferral, or rejection: `[Required]`
- Genuine deadline, if any: `[Required or None]`
- Scope of Seller/Zayne authority pending escalation: `[Required]`

### Seller/Zayne Accountability Statement

`[Seller/Zayne states that this disposition is bounded by the identified
evidence, conditions, authority, and review date; preserves uncertainty and
counterevidence; and grants no authority for external action.]`

## Human Sign-Off

### Human Review Requirement

| Field | Entry |
|---|---|
| Human review required | `[Yes / No]` |
| Triggering governance requirement | `[Required or None]` |
| Exact decision or exception requested | `[Required or None]` |
| Human reviewer | `[Required if applicable]` |
| Reviewer authority | `[Required if applicable]` |
| Review request timestamp | `[Date, time, time zone or None]` |
| Review completion timestamp | `[Date, time, time zone or Pending]` |

### Human Disposition

Select one when human review is required:

- [ ] **APPROVE WITHIN STATED LIMITS**
- [ ] **APPROVE A NARROWER CONTINUATION**
- [ ] **REQUIRE ADDITIONAL EVIDENCE OR NARROWER SCOPE**
- [ ] **DEFER PENDING A NAMED DEPENDENCY**
- [ ] **DECLINE**
- [ ] **ESCALATE TO OPENCLAW OR ANOTHER ACCOUNTABLE AUTHORITY**

### Sign-Off Record

| Field | Entry |
|---|---|
| Candidate identifier and version reviewed | `[Required]` |
| Seller Decision Report identifier and version reviewed | `[Required]` |
| Evidence and material findings considered | `[Required]` |
| Human disposition | `[Required]` |
| Exact scope of approval or decision | `[Required]` |
| Conditions and prohibitions | `[Required or None]` |
| Matters expressly not decided | `[Required]` |
| Expiration or revalidation condition | `[Required]` |
| Reviewer name or accountable identity | `[Required]` |
| Reviewer authority | `[Required]` |
| Sign-off timestamp | `[Date, time, time zone]` |

### Human Reviewer Rationale

`[Required when human review occurs.]`

### Sign-Off Boundary Statement

`[Confirm that sign-off does not validate false, stale, or inadmissible evidence;
erase known risks or rejection findings; transfer another layer's authority;
override law, platform policy, user agency, or OpenClaw governance; or authorize
actions outside the bounded decision reviewed.]`

## Governance Audit Trail

### Audit Trail Summary

| Field | Entry |
|---|---|
| Original candidate dossier reference | `[Required]` |
| Transfer declaration reference | `[Required]` |
| Intake record reference | `[Required]` |
| Evidence inventory reference | `[Required]` |
| Missing evidence register reference | `[This report or linked record]` |
| Risk register reference | `[This report or linked record]` |
| Dependency decisions | `[References or None]` |
| Prior Seller Decision Reports | `[References or None]` |
| Human-review records | `[References or None]` |
| OpenClaw governance records | `[References or None]` |

### Review Event Log

| Timestamp | Accountable identity or reviewer | Review event | Evidence or record affected | Decision or status change | Rationale | Prior state preserved |
|---|---|---|---|---|---|---|
| `[Date, time, time zone]` | `[Required]` | `[Intake / Evidence addition / Correction / Freshness review / Gate review / Score change / Decision / Sign-off / Revalidation / Closure]` | `[Reference]` | `[Required]` | `[Required]` | `[Yes / No with explanation]` |

### Evidence Change Log

| Timestamp | Evidence reference | Change type | Prior status | New status | Authority or source | Reason | Evaluation effect |
|---|---|---|---|---|---|---|---|
| `[Date, time, time zone or None]` | `[Required]` | `[Added / Corrected / Challenged / Withdrawn / Expired / Discredited / Revalidated]` | `[Required]` | `[Required]` | `[Required]` | `[Required]` | `[Required]` |

### Score and Decision Change Log

| Timestamp | Prior report or decision | Changed score, risk, finding, or disposition | New result | New evidence or authority basis | Accountable reviewer |
|---|---|---|---|---|---|
| `[Date, time, time zone or None]` | `[Reference]` | `[Required]` | `[Required]` | `[Required]` | `[Required]` |

### Audit Integrity Confirmation

- [ ] Original evidence and candidate records remain preserved.
- [ ] Corrections identify the prior statement, author, timestamp, and reason.
- [ ] Stale or inadmissible evidence remains visible but is not treated as current
      support.
- [ ] Missing evidence and disagreement remain visible.
- [ ] Prior rejection, return, deferral, and escalation findings remain preserved.
- [ ] Every changed score or disposition identifies its new governance basis.
- [ ] Candidate lineage remains visible.
- [ ] The report can be reconstructed from its referenced records.

### Revalidation and Closure

| Field | Entry |
|---|---|
| Revalidation required | `[Yes / No]` |
| Revalidation trigger | `[Required or None]` |
| Next review date or condition | `[Required or None]` |
| Candidate review state after report | `[Required]` |
| Closure authorized | `[Yes / No]` |
| Closure authority and rationale | `[Required if closed]` |
| Closure timestamp | `[Date, time, time zone or None]` |

## Final Record Certification

### Seller/Zayne Certification

**Accountable identity:** `Seller / Zayne`  
**Report identifier and version:** `[Required]`  
**Certification timestamp:** `[Date, time, time zone]`

`[Confirm that the report accurately reflects the evidence set, freshness
determinations, uncertainty, relationships, impacts, gates, risks, scores,
persistent findings, disposition, and authority known at the decision timestamp.]`

### Final Governance Boundary

Completion, approval, or human sign-off of this report authorizes only the
bounded governance progression expressly stated in the Final Disposition.

It does not by itself authorize implementation, product creation, listing,
publication, posting, messaging, billing, payment, purchasing, fulfillment,
refunds, or any other external action.

