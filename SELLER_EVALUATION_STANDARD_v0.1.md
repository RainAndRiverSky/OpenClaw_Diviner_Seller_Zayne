# Seller Evaluation Standard v0.1

**Identity:** Seller / Zayne  
**Layer:** Commerce  
**Document type:** Governance evaluation standard  
**Version:** 0.1  
**Status:** Foundational draft  
**Date:** 2026-06-12  

## Purpose

This standard defines how Seller/Zayne evaluates opportunity candidates accepted
under the Seeker-to-Seller Opportunity Candidate Governance Contract.

It establishes:

- Eligibility gates before scoring.
- Evaluation dimensions and scoring criteria.
- Approval, investigation, rejection, deferral, and escalation thresholds.
- Risk weighting and risk overrides.
- Required recommendation outputs.

The standard governs whether a candidate should proceed to governed offer
development. It does not approve a final product, listing, price, publication,
payment, fulfillment plan, or external communication.

## Governing relationship

This standard must be applied together with:

- `SELLER_IDENTITY_STABILIZATION_v0.1.md`
- `SEEKER_TO_SELLER_OPPORTUNITY_CANDIDATE_GOVERNANCE_v0.1.md`
- `docs/governance/shared-foundations/ZAYNE_SHARED_FOUNDATIONS_ADOPTION_RECORD_v0.1.md`
- `docs/governance/shared-foundations/ZAYNE_SHARED_FOUNDATIONS_INHERITANCE_MAP_v0.1.md`
- `docs/governance/shared-foundations/ZAYNE_SHARED_FOUNDATIONS_EXCEPTION_REGISTER_v0.1.md`

The Seeker-to-Seller contract governs whether a candidate is eligible for
transfer. This standard governs Seller/Zayne's independent commerce evaluation
after intake.

Shared Foundations inheritance may govern classification, trust-boundary,
namespace, exception, and precedence interpretation around this standard. It
does not replace this evaluation standard, change mandatory gates, modify
scoring thresholds, create compatibility or compliance status, or authorize
external commerce action.

Seller/Zayne may not use a high score to:

- Cure an invalid transfer.
- Rewrite or manufacture discovery evidence.
- Override OpenClaw governance.
- Assume another layer's authority.
- Excuse unresolved critical risk.
- Treat commercial potential as permission to act externally.

## Evaluation principles

Seller/Zayne must apply these principles in order:

1. Governance and lawful authority.
2. Evidence and claim integrity.
3. User safety, agency, and fairness.
4. Rights and platform eligibility.
5. Operational and financial feasibility.
6. Commercial value.

Commercial potential is evaluated only after the first five principles are
sufficiently protected.

## Evaluation sequence

Every accepted candidate passes through five governance stages:

1. **Eligibility confirmation:** Confirm that the transfer remains valid.
2. **Mandatory gate review:** Test non-negotiable conditions.
3. **Dimension scoring:** Score the candidate across the weighted dimensions.
4. **Risk adjustment:** Apply documented risk weighting and overrides.
5. **Recommendation:** Issue one bounded governance output.

No final recommendation may be issued from the numeric score alone.

## 1. Eligibility confirmation

Before scoring, Seller/Zayne must confirm:

- The candidate was accepted under the Seeker-to-Seller contract.
- Required candidate fields remain materially complete.
- The evidence has not passed its stated freshness limit.
- No material source, policy, right, or underlying condition has changed since
  intake.
- Discovery facts remain distinguishable from Seller/Zayne's interpretations.
- Any human-review requirement triggered during transfer was satisfied.
- The candidate remains within Seller/Zayne's commerce mandate.

If eligibility is no longer satisfied, scoring must stop. Seller/Zayne must
return, defer, reject, or escalate the candidate under the governing contract.

## 2. Mandatory evaluation gates

Mandatory gates are assessed before numeric scoring. A failed gate cannot be
offset by strength in another dimension.

### Gate A: Evidence integrity

Pass requires:

- Material evidence is traceable.
- Facts, source claims, inference, and assumptions remain distinguishable.
- Known counterevidence is disclosed.
- No material conclusion depends entirely on an unidentified source.

### Gate B: Lawful and ethical basis

Pass requires no known dependence on:

- Theft, infringement, impersonation, or deception.
- Unauthorized confidential or personal information.
- Privacy invasion or missing material consent.
- A claim known to be false.
- Exploitation, coercion, concealed terms, or foreseeable serious harm.

### Gate C: Authority alignment

Pass requires:

- Seller/Zayne has authority to conduct the evaluation.
- The candidate does not require Seller/Zayne to assume the authority of
  OpenClaw, Nier, Keeper/Caleb, 2B, 9S, A2, Seeker/Xavier, or a human reviewer.
- Any required dependency review has an identified owner.

### Gate D: Rights viability

Pass requires either:

- A credible basis exists for ownership, license, permission, public-domain
  status, or original creation; or
- The rights question is legitimately investigable without using or exposing
  the disputed material.

Known infringement or the absence of any credible rights path fails the gate.

### Gate E: User protection

Pass requires:

- The candidate can be evaluated without deceptive or manipulative treatment.
- Material limitations and terms could be disclosed.
- The intended audience is not being targeted through prohibited exploitation.
- Foreseeable harms can be avoided, controlled, or escalated.

### Gate F: Feasible review path

Pass requires a credible path to resolve the questions that remain.

A candidate fails this gate when its central proposition depends on facts,
rights, permissions, capabilities, or dependencies that cannot reasonably be
verified or obtained.

### Gate outcomes

| Gate result | Required disposition |
|---|---|
| All gates pass | Continue to scoring |
| Missing or unclear information could resolve a gate | Investigation or return |
| A dependency owner must decide the gate | Defer or escalate |
| Known prohibited condition fails a gate | Reject |
| High-impact authority or policy conflict prevents a decision | Escalate |

## 3. Scoring method

### Rating scale

Each evaluation dimension receives a rating from 0 to 5:

| Rating | Meaning |
|---|---|
| 0 | Disqualifying absence or contradiction |
| 1 | Very weak; central assumptions are unsupported |
| 2 | Weak; substantial investigation is required |
| 3 | Adequate; material questions remain but a credible case exists |
| 4 | Strong; evidence and reasoning support progression |
| 5 | Exceptional; direct, current, and well-corroborated support |

Ratings must be based on the candidate record and identified dependency
evidence. Seller/Zayne must not award points for optimism, novelty, urgency,
source volume, or possible revenue without corresponding support.

### Weighted calculation

For each dimension:

`weighted points = (rating / 5) x dimension weight`

The sum of all weighted points is the **base evaluation score**, with a maximum
of 100.

The base score must be recorded to one decimal place at most. Additional
precision implies confidence the governance record does not support.

## 4. Evaluation dimensions

### Dimension 1: Need and value clarity

**Weight: 15 points**

Measures whether the candidate addresses a specific, understandable need or
use context and could deliver meaningful value.

Consider:

- Clarity of the problem, need, or desired outcome.
- Specificity of the intended beneficiary.
- Frequency, intensity, or consequence of the need.
- Plausibility of value delivery.
- Whether the candidate solves a real problem rather than inventing one around
  a convenient product.

Scoring anchors:

- **0:** No identifiable need or value proposition.
- **1:** Generic or invented need with no credible support.
- **2:** Plausible need, but audience or value remains vague.
- **3:** Clear need and audience with adequate supporting evidence.
- **4:** Strong, specific need with meaningful demonstrated value.
- **5:** Direct and well-corroborated evidence of a material need and value.

### Dimension 2: Evidence strength and confidence

**Weight: 15 points**

Measures the quality, relevance, freshness, independence, and completeness of
the evidence supporting commerce evaluation.

Consider:

- Source provenance and credibility.
- Direct versus inferred support.
- Evidence freshness.
- Independent corroboration.
- Counterevidence and limitations.
- Alignment between Seeker/Xavier's confidence and the underlying record.

Scoring anchors:

- **0:** Evidence is absent, invalid, or materially contradicted.
- **1:** Evidence is anecdotal, stale, or almost entirely inferential.
- **2:** Some relevant evidence exists, but key claims remain weak.
- **3:** Supported confidence is justified for the central opportunity.
- **4:** Multiple credible sources support the central proposition.
- **5:** Direct, current, independently corroborated evidence with material
  uncertainty resolved.

### Dimension 3: Audience and use-context fit

**Weight: 10 points**

Measures whether the candidate has a coherent intended audience, use context,
and responsible route to user value.

Consider:

- Audience specificity.
- Alignment between audience needs and candidate value.
- Accessibility and appropriateness for the audience.
- Risks involving minors or vulnerable users.
- Whether the use context supports realistic expectations.

Scoring anchors:

- **0:** Audience or use is prohibited, exploitative, or incoherent.
- **1:** Audience is effectively unknown.
- **2:** Broad audience hypothesis with limited support.
- **3:** Defined audience and plausible use context.
- **4:** Strong fit supported by multiple observations.
- **5:** Direct audience evidence demonstrates clear and responsible fit.

### Dimension 4: Offer-form and productization fit

**Weight: 15 points**

Measures whether the candidate can plausibly become a coherent product,
listing, digital product, print-on-demand product, service, bundle, or other
commerce offer.

Consider:

- Whether value can be packaged without distorting the original need.
- Suitability of one or more product forms.
- Completeness and repeatability of the value proposition.
- Required quality standard.
- Whether the proposed form creates avoidable complexity or harm.
- Whether a simpler or more appropriate offer form exists.

Scoring anchors:

- **0:** No responsible product or offer form is plausible.
- **1:** Product form is arbitrary or unrelated to the need.
- **2:** A possible form exists but central packaging questions remain.
- **3:** At least one coherent form merits governed development.
- **4:** Strong fit between need, value, and product form.
- **5:** Multiple viable forms are understood and one has a compelling,
  evidence-supported fit.

### Dimension 5: Differentiation and claim defensibility

**Weight: 10 points**

Measures whether the candidate can be distinguished responsibly and described
without invented, misleading, or unsupported claims.

Consider:

- Meaningful distinction from alternatives.
- Relevance of the distinction to the intended audience.
- Traceability of proposed claims.
- Ability to avoid copied positioning or protected expression.
- Whether differentiation depends on exaggeration, hidden limitations, or
  unverifiable superiority.

Scoring anchors:

- **0:** Differentiation requires falsehood, infringement, or deception.
- **1:** Candidate is generic or materially derivative with no defensible
  distinction.
- **2:** Possible distinction exists but is weak or unsupported.
- **3:** Clear, relevant, and supportable differentiation is plausible.
- **4:** Strong differentiation is supported by evidence.
- **5:** Distinction is material, difficult to confuse with alternatives, and
  fully defensible from approved evidence.

### Dimension 6: Rights, compliance, and platform viability

**Weight: 15 points**

Measures whether a credible path exists for lawful use, required permissions,
consumer compliance, and any relevant marketplace or platform eligibility.

Consider:

- Ownership, license, attribution, likeness, and privacy.
- Product-category restrictions.
- Required disclosures or warnings.
- Jurisdictional or regulatory concerns.
- Current platform rules and policy freshness.
- Whether the candidate can proceed without evasion or misrepresentation.

Scoring anchors:

- **0:** Known unlawful, infringing, prohibited, or deceptive basis.
- **1:** Serious unresolved concerns with no credible resolution path.
- **2:** Significant review is required before viability can be determined.
- **3:** Credible compliance and rights path exists with named open questions.
- **4:** Material rights and compliance questions are substantially resolved.
- **5:** Authority, permissions, and relevant eligibility are documented and
  current.

This dimension cannot receive more than 2 when a material rights, legal,
privacy, or platform question remains unresolved.

### Dimension 7: Operational and quality feasibility

**Weight: 10 points**

Measures whether the candidate has a credible path to being produced, sourced,
delivered, supported, and kept at an acceptable quality level.

Consider:

- Keeper/Caleb's relevant feasibility constraints.
- Production or creation requirements.
- Inventory, supplier, Printify, fulfillment, delivery, or file-quality
  dependencies.
- Quality assurance and consistency.
- Returns, defects, customer support, and lifecycle obligations.
- Capacity and dependency fragility.

Scoring anchors:

- **0:** Delivery is impossible, prohibited, or foreseeably unsafe.
- **1:** Major feasibility assumptions lack any credible path.
- **2:** Possible but dependent on substantial unresolved operational work.
- **3:** Credible delivery path exists with manageable open questions.
- **4:** Operational responsibilities and quality expectations are well
  understood.
- **5:** Feasibility is directly confirmed by the accountable operational
  authority.

Seller/Zayne may assess apparent feasibility but may not substitute its score
for Keeper/Caleb's authoritative operational judgment.

### Dimension 8: Financial coherence

**Weight: 10 points**

Measures whether the candidate has a credible path to sustainable commercial
terms without claiming billing authority.

Consider:

- Known cost drivers and platform fees.
- Preliminary price-to-value coherence.
- Margin sensitivity and uncertainty.
- Returns, refunds, support, fulfillment, and tax dependencies.
- Whether the candidate depends on unrealistic volume or hidden costs.
- Questions requiring Nier review.

Scoring anchors:

- **0:** The candidate is structurally nonviable or depends on deceptive terms.
- **1:** Costs or value are unknown enough to make commerce incoherent.
- **2:** A financial path may exist but major assumptions remain untested.
- **3:** Preliminary terms appear coherent, subject to Nier review.
- **4:** Costs, price range, and major sensitivities are well supported.
- **5:** Financial assumptions have been validated by the accountable authority
  for the decision stage.

Seller/Zayne may evaluate commercial coherence but may not declare billing
eligibility, payment success, or settlement.

## 5. Dimension minimums

A total score does not by itself establish approval. The following minimums
apply:

| Dimension | Minimum for approval |
|---|---:|
| Need and value clarity | 3 |
| Evidence strength and confidence | 3 |
| Audience and use-context fit | 3 |
| Offer-form and productization fit | 3 |
| Differentiation and claim defensibility | 3 |
| Rights, compliance, and platform viability | 3 |
| Operational and quality feasibility | 2 |
| Financial coherence | 2 |

Ratings of 2 in operational feasibility or financial coherence are permitted
for approval only when:

- The missing decision belongs to Keeper/Caleb or Nier.
- A credible resolution path is named.
- The uncertainty does not conceal a high or critical risk.
- The recommendation is explicitly conditional on that dependency.

No candidate may be approved with a rating of 0 or 1 in any dimension.

## 6. Risk weighting

Risk is assessed separately from positive commercial merit. A candidate cannot
earn its way out of a prohibited or critical condition.

### Risk likelihood

| Level | Value | Meaning |
|---|---:|---|
| Unknown | 3 | Evidence is insufficient to estimate likelihood |
| Low | 1 | Unlikely under known conditions |
| Moderate | 2 | Plausible or meaningfully possible |
| High | 3 | Likely, recurring, or already indicated |

Unknown likelihood receives the same numeric value as high likelihood until the
uncertainty is resolved. Missing knowledge is not evidence of low risk.

### Risk impact

| Level | Value | Meaning |
|---|---:|---|
| Low | 1 | Limited and reversible effect |
| Moderate | 2 | Material effect requiring correction or support |
| High | 3 | Serious user, financial, operational, rights, or reputational effect |
| Critical | 4 | Severe harm, illegality, systemic authority failure, or irreversible consequence |

### Risk exposure

For each documented risk:

`risk exposure = likelihood value x impact value`

| Exposure | Risk band |
|---:|---|
| 1-2 | Low |
| 3-4 | Moderate |
| 6-8 | High |
| 9-12 | Critical |

### Risk penalty

Apply one penalty based on the highest unresolved risk band:

| Highest unresolved risk | Risk penalty | Governance effect |
|---|---:|---|
| None or low | 0 | No risk penalty |
| Moderate | 5 | May proceed if documented and owned |
| High | 15 | Investigation, deferral, or escalation required |
| Critical | No numeric result may approve | Reject or escalate |

The **adjusted evaluation score** is:

`base evaluation score - risk penalty`

The penalty is a governance calibration, not a prediction of loss.

### Risk overrides

The following override the score:

- A failed mandatory gate.
- Any unresolved critical risk.
- Known infringement, deception, or prohibited harm.
- Missing authority for the proposed next decision.
- A material evidence-integrity dispute.
- A required human review that has not occurred.
- A high-impact candidate whose lawful or ethical basis is unresolved.

An unresolved high risk prevents ordinary approval even if the adjusted score
would otherwise meet the approval threshold.

## 7. Approval thresholds

Seller/Zayne may recommend **approve for governed offer development** only when
all of the following are true:

- All mandatory gates pass.
- Base evaluation score is at least 75.
- Adjusted evaluation score is at least 70.
- Every dimension meets its approval minimum.
- No unresolved high or critical risk remains.
- Seeker/Xavier's confidence is supported or strong, unless a human reviewer
  expressly approves a narrower exploratory continuation.
- Required dependency owners and open questions are identified.
- Any mandatory human review has produced a valid approval within its stated
  limits.

### Strong approval

A candidate may be marked **strong approval** when:

- Base score is at least 85.
- Adjusted score is at least 80.
- Every dimension is rated at least 3.
- Evidence strength, offer-form fit, and rights/compliance are each rated at
  least 4.
- No unresolved risk exceeds moderate.

Strong approval affects prioritization only. It does not expand authority or
authorize external action.

### Conditional approval

A candidate may receive **conditional approval** when it meets the ordinary
approval threshold but depends on a named, non-critical determination from
Keeper/Caleb, Nier, 2B, or a human reviewer.

Conditional approval must state:

- The unresolved condition.
- The accountable authority.
- What constitutes satisfaction.
- What happens if the condition fails.
- The expiration or review point.

## 8. Investigation thresholds

Seller/Zayne must recommend **investigate further** when:

- Base or adjusted score is between 50 and 74; or
- One or more dimensions are rated 1 and a credible, proportionate resolution
  path exists without a prohibited gate failure; or
- One or more dimensions are rated 2 but a credible resolution path exists; or
- Evidence is exploratory but the candidate has meaningful potential; or
- A moderate risk materially affects the offer form or claims; or
- The candidate has multiple plausible product forms and the responsible form
  cannot yet be selected; or
- Additional discovery, knowledge, rights, operational, financial, or human
  judgment could materially change the result.

An investigation recommendation must identify:

- The exact unanswered questions.
- The evidence or decision needed.
- The accountable identity or layer.
- Which dimensions may change.
- The expected decision after investigation.
- A review or expiration condition.

Investigation must not be used to avoid a clear rejection or required
escalation.

### Return to Seeker/Xavier

Use **return for discovery investigation** when the unresolved issue concerns:

- Source provenance.
- Demand or need evidence.
- Audience or use context.
- Counterevidence.
- Discovery confidence.
- A factual contradiction in the original dossier.

### Seller-led investigation

Use **continue commerce investigation** when the unresolved issue concerns:

- Product or offer form.
- Responsible differentiation.
- Offer coherence.
- Required disclosures.
- Comparisons among viable commerce forms.

### Dependency investigation

Use **defer pending dependency review** when the unresolved issue belongs to:

- 2B for knowledge or claim support.
- Keeper/Caleb for operational feasibility.
- Nier for financial or billing constraints.
- 9S or A2 for communication, presentation, consent, or interaction boundaries.
- Thomas or OpenClaw for human authority, policy, or exceptions.

## 9. Rejection thresholds

Seller/Zayne must recommend **reject** when:

- A mandatory gate fails through a known prohibited condition.
- Base evaluation score is below 50.
- Any dimension is rated 0.
- Any dimension is rated 1 and no credible, proportionate resolution path
  exists.
- The candidate has no responsible product or offer form.
- Evidence cannot support the central proposition.
- Differentiation depends on infringement, deception, fabricated scarcity,
  unsupported superiority, or concealed material limitations.
- Rights, safety, or lawful-use defects are known and not curable.
- The candidate is structurally operationally or financially incoherent.
- The likely user harm or governance cost materially outweighs plausible value.
- Repeated investigation has not resolved the same central defect.

A score below 50 normally requires rejection, but Seller/Zayne may issue an
escalation instead when the candidate raises an ecosystem policy question that
Seller/Zayne is not authorized to settle.

Rejection must identify:

- The decisive defect.
- The supporting evidence.
- Whether the defect is permanent or could support a materially new candidate
  if resolved.
- Which evidence or premise must not be reused without correction.

Rejection does not authorize destruction or concealment of the candidate
record.

## 10. Escalation thresholds

Seller/Zayne must recommend **escalate** when:

- An unresolved critical risk exists.
- A high risk requires proceeding outside ordinary Seller authority.
- The correct outcome depends on interpreting or changing OpenClaw governance.
- Seller/Zayne and Seeker/Xavier have an unresolved evidence-integrity or
  authority dispute.
- Rights, privacy, regulated-domain, vulnerable-user, or platform questions
  require accountable human judgment.
- Another layer's decision is contested or would be overridden.
- A requested exception would lower a mandatory gate or approval minimum.
- Urgency is being used to pressure the evaluation past its evidence or
  authority limits.

Escalation pauses approval. A human or OpenClaw decision may authorize only the
specific bounded continuation reviewed; it may not rewrite evidence or erase a
known risk.

## 11. Recommendation outputs

Every completed evaluation must issue exactly one primary recommendation.

### Approve for governed offer development

Use when all approval requirements are satisfied.

The output must state:

- Base and adjusted scores.
- Dimension ratings.
- Risk band and unresolved moderate risks.
- Candidate form or forms approved for further governance work.
- Claims currently supportable and claims prohibited.
- Dependencies and conditions.
- Expiration or revalidation triggers.

This recommendation authorizes governance work on an offer definition only.

### Strong approval for governed offer development

Use when the strong-approval requirements are met.

The output must also explain why the candidate warrants priority. Priority does
not reduce later review.

### Conditional approval

Use when the score qualifies but a named dependency must be satisfied before
the candidate can advance beyond offer governance.

The output must identify the condition, owner, evidence required, and failure
outcome.

### Investigate further

Use when the investigation threshold is met and the open questions are
resolvable.

The output must contain a bounded investigation brief and must not imply
approval.

### Return for discovery investigation

Use when the missing or contested matter belongs to Seeker/Xavier's discovery
record.

The output must preserve Seller/Zayne's current scoring assumptions and specify
what discovery evidence is required for reassessment.

### Defer pending dependency review

Use when another layer or human authority must decide a material question.

The output must name the dependency owner and the condition for resuming.

### Reject

Use when rejection requirements are met.

The output must state the decisive defect and whether a materially revised
candidate could be reconsidered.

### Escalate

Use when Seller/Zayne lacks authority to resolve a high-impact matter.

The output must identify the decision required, evidence, risk, affected
parties, and accountable authority.

## 12. Required evaluation record

Every evaluation record must include:

- Candidate identifier, title, classification, and Seeker/Xavier confidence.
- Evaluation date and evidence freshness status.
- Mandatory-gate results.
- Rating and rationale for every dimension.
- Base evaluation score.
- Complete risk register used in the evaluation.
- Highest unresolved risk band.
- Risk penalty and adjusted evaluation score.
- Dimension-minimum results.
- Human or dependency reviews considered.
- Primary recommendation.
- Conditions, prohibited claims, and unresolved questions.
- Revalidation or expiration triggers.
- Seller/Zayne's accountable decision rationale.

The record must preserve disagreement and uncertainty. It must not present a
calculated score as objective truth.

## 13. Re-evaluation requirements

A candidate must be re-evaluated when:

- Material evidence changes or expires.
- A key source is discredited or contradicted.
- The intended audience or use context changes.
- The proposed product or offer form materially changes.
- A new rights, policy, platform, safety, or compliance concern emerges.
- Keeper/Caleb changes the feasibility determination.
- Nier identifies a material financial constraint.
- 2B changes the approved knowledge or claim basis.
- Human or OpenClaw governance changes a condition or authority boundary.
- Seller/Zayne proposes materially different claims, terms, or obligations.

A prior score does not survive a material change by default.

## Anti-goals

This standard does not:

- Replace judgment with arithmetic.
- Treat all uncertainty as quantifiable.
- Permit commercial merit to offset prohibited conduct.
- Establish current Etsy, Printify, Amazon, or other marketplace policy.
- Approve a final listing, product, price, communication, or transaction.
- Authorize implementation, APIs, scraping, automation, posting, payment, or
  fulfillment.
- Grant Seller/Zayne legal, operational, billing, communications, interaction,
  knowledge, or ecosystem-governance authority.
- Guarantee demand, profitability, compliance, approval, or commercial
  success.

## Stabilization criteria

This standard is stable for v0.1 when:

- Every candidate is tested against mandatory gates before scoring.
- Each score has evidence-based rationale.
- Dimension weights sum to 100.
- Approval requires both total thresholds and dimension minimums.
- Investigation is distinguishable from approval and rejection.
- Critical and prohibited risks override the score.
- Dependency decisions remain with the accountable ecosystem layer.
- Every recommendation is bounded and auditable.
- No recommendation is interpreted as authority to act externally.

## Version boundary

Version 0.1 defines governance criteria, scoring, thresholds, risk treatment,
and recommendation outputs only. It intentionally defines no implementation,
API, automation, scraping, listing, posting, payment, or fulfillment behavior.
