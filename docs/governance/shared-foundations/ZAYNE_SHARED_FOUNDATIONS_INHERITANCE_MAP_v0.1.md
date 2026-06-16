# Zayne Shared Foundations Inheritance Map v0.1

## Status

Initial inheritance map for Seller/Zayne.

This map describes how Seller/Zayne relates to OpenClaw Shared Foundations
using the Reference + Inheritance model. It distinguishes inherited contracts,
Zayne-specific extensions, local overrides, deferred capabilities, and
steward-owned content.

## Steward and Foundation Scope

| Field | Value |
| --- | --- |
| Steward | Seller Zayne |
| Local identity reference | `identity/ZAYNE_STEWARD_IDENTITY_v0.1.md` |
| Foundation version | OpenClaw Shared Foundations v0.1 document set |
| Adoption record | `ZAYNE_SHARED_FOUNDATIONS_ADOPTION_RECORD_v0.1.md` |
| Exception register | `ZAYNE_SHARED_FOUNDATIONS_EXCEPTION_REGISTER_v0.1.md` |
| Distribution model | Reference + Inheritance |

## Inherited

Seller/Zayne inherits or faithfully maps the following Foundation contracts:

| Domain or framework | Foundation source | Local treatment |
| --- | --- | --- |
| Governance | `governance/FOUNDATION_GOVERNANCE_ARCHITECTURE.md` | Mapped through Seller/Zayne commerce governance and Shared Foundations adoption records |
| Identity structure | `identity/FOUNDATION_IDENTITY_ARCHITECTURE.md` | Mapped through `identity/ZAYNE_STEWARD_IDENTITY_v0.1.md` and `SELLER_IDENTITY_STABILIZATION_v0.1.md` |
| Memory contracts | `memory/FOUNDATION_MEMORY_ARCHITECTURE.md` | Mapped to Zayne's governance records, handoffs, decision records, and evidence lineage; durable private memory remains unimplemented |
| Recovery boundaries | `recovery/FOUNDATION_RECOVERY_ARCHITECTURE.md` | Adopted as governance boundaries only; no recovery automation implemented |
| Classification Framework | `docs/OPENCLAW_CLASSIFICATION_METADATA_SCHEMA_v0.1.md` | Used as descriptive vocabulary for Zayne-owned docs, records, evidence, and future decision artifacts |
| Requirement Framework | `docs/OPENCLAW_REQUIREMENT_IDENTIFIER_FRAMEWORK_v0.1.md` | Adopted for future requirement mapping; no local requirement IDs allocated yet |
| Domain Precedence Model | `docs/DOMAIN_PRECEDENCE_MODEL_v0.1.md` | Adopted for conflict interpretation between Foundation and Zayne-owned material |
| Override and Exception Manifest | `docs/CANONICAL_OVERRIDE_AND_EXCEPTION_MANIFEST_v0.1.md` | Adopted through the local exception register |
| Trust Boundary and Data Classification Model | `docs/TRUST_BOUNDARY_AND_DATA_CLASSIFICATION_MODEL_v0.1.md` | Adopted as handling guidance for local records, candidate evidence, decision records, and future sharing |
| Steward Identifiers and Namespace Isolation | `docs/CANONICAL_STEWARD_IDENTIFIERS_AND_NAMESPACE_ISOLATION_v0.1.md` | Adopted with CSID pending registration |

## Extended

Seller/Zayne extends Shared Foundations with local commerce governance:

| Local extension | Foundation relationship | Local reference |
| --- | --- | --- |
| Commerce governance identity and authority boundaries | Extends Identity and Governance contracts | `SELLER_IDENTITY_STABILIZATION_v0.1.md` |
| Commerce literacy and event distinctions | Zayne-owned governance knowledge under inherited classification and provenance concepts | `SELLER_COMMERCE_FOUNDATIONS_DISCOVERY_v0.1.md` |
| Opportunity candidate transfer boundary | Extends Governance, Precedence, Trust Boundary, and Classification contracts | `SEEKER_TO_SELLER_OPPORTUNITY_CANDIDATE_GOVERNANCE_v0.1.md` |
| Candidate evaluation gates, scoring, and risk treatment | Extends Governance and Requirement concepts with commerce-specific criteria | `SELLER_EVALUATION_STANDARD_v0.1.md` |
| Review workflow and audit trail | Extends Governance, Memory, Classification, and Exception contracts | `SELLER_REVIEW_WORKFLOW_v0.1.md` |
| Candidate lifecycle states and transitions | Extends Governance and Memory lifecycle concepts | `seller-candidate-lifecycle-v0.1.md` |
| Decision report structure | Extends Governance, Memory, Classification, and provenance concepts | `SELLER_DECISION_REPORT_TEMPLATE_v0.1.md` |
| Selective archive inheritance limits | Zayne-owned conceptual provenance under inherited governance controls | `SELLER_ARCHIVE_RELEVANCE_REVIEW_v0.1.md` |

These extensions remain local to Seller/Zayne and do not become canonical
Shared Foundations definitions through adoption.

## Overridden

No Foundation contracts are overridden in this adoption record.

Known gaps, deferred capabilities, or unimplemented runtime features are
limitations, not approved overrides.

## Steward-Owned

The following subjects originate within and remain governed by Seller/Zayne:

- `SELLER_IDENTITY_STABILIZATION_v0.1.md`
- `SELLER_ARCHIVE_RELEVANCE_REVIEW_v0.1.md`
- `SELLER_COMMERCE_FOUNDATIONS_DISCOVERY_v0.1.md`
- `SEEKER_TO_SELLER_OPPORTUNITY_CANDIDATE_GOVERNANCE_v0.1.md`
- `SELLER_EVALUATION_STANDARD_v0.1.md`
- `SELLER_REVIEW_WORKFLOW_v0.1.md`
- `SELLER_DECISION_REPORT_TEMPLATE_v0.1.md`
- `seller-candidate-lifecycle-v0.1.md`
- `seller-review-workflow-v0.1.md`
- `identity/ZAYNE_STEWARD_IDENTITY_v0.1.md`
- `docs/handoffs/`
- future Seller/Zayne decision, review, evaluation, lifecycle, and commerce
  governance artifacts

Shared Foundations inheritance does not move these records into the Foundation
package or make them available to another steward.

## Optional or Deferred

| Item | Status | Notes |
| --- | --- | --- |
| MCP | Deferred | No Seller/Zayne MCP capability is enabled by this adoption |
| Obsidian | Deferred | No Seller/Zayne Obsidian projection is enabled by this adoption |
| Durable private memory | Deferred | Seller/Zayne currently preserves governance knowledge, handoffs, templates, workflows, and future decision records as repository documents |
| Automated recovery | Deferred | No Seller/Zayne recovery automation is implemented |
| Runtime integration | Deferred | No commerce runtime behavior is implemented |
| Commerce operations | Not adopted | Seller/Zayne does not operate inventory, payment, fulfillment, publication, messaging, or marketplace access |
| Requirement-to-evidence mapping | Deferred | No local requirement mapping has been allocated yet |
| Compatibility status tracking | Deferred | Explicitly omitted from this implementation |
| Compliance or certification claim | Not created | Explicitly prohibited by implementation instruction |

## Conflict Rule

Foundation documents control the meaning of inherited Shared Foundations
contracts. Seller/Zayne controls its steward-owned commerce governance,
candidate evaluation, review workflows, lifecycle decisions, decision records,
commerce knowledge, handoff records, and domain-specific governance where they
do not weaken mandatory Foundation protections.

When a Shared Foundations contract and Zayne-owned commerce material both
apply, the conflict should be resolved by subject, scope, ownership,
classification, namespace, authority, and domain precedence. Zayne-owned
material may be stricter than Shared Foundations, but it must not weaken
mandatory Shared Foundations protections while claiming unchanged inheritance.

When a conflict cannot be resolved by subject, scope, ownership, and
precedence, Seller/Zayne should fail closed, preserve the evidence, avoid
external action, and record the issue for governance review.
