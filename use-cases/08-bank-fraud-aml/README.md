# Bank Fraud and AML

## Objective

Support bank fraud operations and anti-money-laundering (AML) teams with alert prioritization, case evidence organization, and investigation workflow improvements. Detection and investigative outputs must remain reviewable and governed by the institution's approved policies.

## Discovery questions

- Which fraud typologies, channels, products, and AML processes are in scope?
- What are the existing detection rules, alert thresholds, and case-management systems?
- Which actions require investigator, compliance, or law-enforcement approval?
- How are false positives, customer impact, suspicious activity reporting, and retention governed?

## Inputs and outputs

- **Inputs:** Authorized transaction and account data, alert features, customer and device signals, and approved case history.
- **Outputs:** Prioritized alerts, evidence summaries, linked activity timelines, investigator tasks, and case audit records.
- **Integrations:** Transaction monitoring, fraud systems, case management, identity services, and approved reporting systems.

## Candidate workflow

1. Ingest only data authorized for the stated monitoring purpose and validate its quality.
2. Apply institution-approved rules or models and preserve feature and rule provenance.
3. Group related alerts and prepare source-linked evidence for investigator review.
4. Record investigator decisions, rationale, escalation, and any required filing in approved systems.
5. Monitor outcomes, drift, disparate impact, and operational changes under model governance.

## Measures and validation

- Track alert precision, investigator workload, time to disposition, confirmed loss, and missed-event indicators.
- Validate using appropriately governed historical or synthetic data, with temporal separation and investigator adjudication.
- Test data gaps, changing typologies, benign lookalikes, channel shifts, and the impact of threshold changes.

## Controls and FDE deliverables

Apply strict data minimization, access controls, retention, auditability, and model-risk governance. Do not automatically freeze accounts, contact law enforcement, or file reports without approved authority and review. Restrict disclosure of monitoring logic where required.

Document data permissions, typology coverage, investigation workflow, model and rule governance, fairness and performance checks, and escalation controls.
