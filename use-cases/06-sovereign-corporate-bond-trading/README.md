# Sovereign and Corporate Bond Trading

## Objective

Map and improve the end-to-end operating workflow for trading sovereign and corporate debt, from idea and pre-trade checks through execution, allocation, confirmation, and post-trade reconciliation. Unlike bond trading analysis, this use case includes operational trading controls and execution interfaces.

## Discovery questions

- Which desks, markets, instruments, currencies, and execution venues are in scope?
- How do sovereign and corporate workflows differ in liquidity, credit review, and settlement?
- Which pre-trade limits, restricted lists, best-execution policies, and approvals apply?
- What systems handle orders, allocations, confirmations, settlement, and exception resolution?

## Inputs and outputs

- **Inputs:** Approved market data, instrument and issuer reference data, orders, mandates, limits, and venue information.
- **Outputs:** Validated order details, workflow status, exception queues, execution records, and reconciliation results.
- **Integrations:** Order and execution management, market data, risk and compliance controls, confirmation, and settlement systems.

## Candidate workflow

1. Validate instrument identity, account mandate, order details, and market status.
2. Run required pre-trade checks and route any breach or ambiguity for approval.
3. Submit or stage orders only through authorized trading systems and personnel.
4. Capture execution details, allocations, confirmations, and required surveillance records.
5. Reconcile trade and settlement data; route breaks to the responsible operations team.

## Measures and validation

- Track pre-trade exception rates, order-to-confirmation time, allocation breaks, settlement fails, and manual touchpoints.
- Validate instrument and order data against system-of-record results in a non-production environment.
- Test limit breaches, stale prices, venue outages, partial fills, cancellations, and corporate action or settlement exceptions.

## Controls and FDE deliverables

Maintain strict separation of duties, entitlements, audit trails, approved limits, and surveillance. No autonomous order placement or change to trading limits is in scope without explicit governance and authorization.

Document the current and target workflow, control points, system ownership, exception taxonomy, test scenarios, and operational acceptance criteria.
