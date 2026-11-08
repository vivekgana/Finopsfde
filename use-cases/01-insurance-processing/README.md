# Insurance Processing

## Objective

Analyze and improve the insurance policy lifecycle, from application intake and underwriting through policy issuance, servicing, and renewal. Keep claims-specific workflows in the claims use cases.

## Discovery questions

- Which products, channels, jurisdictions, and steps are in scope?
- Where do handoffs, missing information, or manual reviews slow processing?
- Which underwriting and approval decisions must remain with licensed staff?

## Inputs and outputs

- **Inputs:** Applications, policy records, underwriting guidelines, correspondence, and processing events.
- **Outputs:** Validated application summaries, missing-information flags, routed work items, and auditable processing reports.
- **Integrations:** Policy administration, document management, CRM, and underwriting systems.

## Candidate workflow

1. Ingest and classify application documents and events.
2. Extract fields with source references and validate them against policy rules.
3. Route exceptions and underwriting decisions to authorized reviewers.
4. Record the decision, rationale, and processing timestamps in the system of record.

## Measures and validation

- Measure cycle time, straight-through processing rate, exception rate, and reviewer corrections against a baseline.
- Test incomplete applications, conflicting documents, policy-rule changes, and reviewer overrides using approved synthetic or de-identified data.
- Verify extracted fields against source documents and audit records before expanding automation.

## Controls

Apply least-privilege access, protect personal information, document retention, and retain human approval for underwriting and policy decisions. Confirm applicable insurance requirements with compliance.