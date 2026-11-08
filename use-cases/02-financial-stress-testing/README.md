# Financial Stress Testing

## Objective

Assess how defined economic and market scenarios could affect a financial institution's portfolios, earnings, capital, liquidity, or other risk measures. The analysis supports approved risk processes; it does not replace formal model governance or regulatory submissions.

## Discovery questions

- Which portfolios, legal entities, risk types, horizons, and reporting obligations are in scope?
- Which scenarios and assumptions are required, and who approves changes to them?
- What are the authoritative data sources, calculation engines, and existing model limitations?
- How are results reviewed, challenged, escalated, and retained today?

## Inputs and outputs

- **Inputs:** Approved scenario variables, portfolio exposures, historical and forecast data, model parameters, and calculation rules.
- **Outputs:** Scenario impacts, key drivers, sensitivities, comparison to limits, exceptions, and traceable review records.
- **Integrations:** Risk data platforms, finance systems, approved calculation engines, and reporting tools.

## Candidate workflow

1. Load a versioned, approved scenario and a timestamped portfolio snapshot.
2. Validate coverage, reconciliations, freshness, and required fields before calculation.
3. Run governed calculations and retain scenario, data, model, and code versions with results.
4. Explain material drivers and sensitivities; route breaches and anomalies for risk-owner review.
5. Publish only approved results to the designated reporting process.

## Measures and validation

- Track run completion, data exceptions, reconciliation breaks, calculation duration, and review-cycle time.
- Compare results with approved benchmarks, prior runs, independent calculations, and expected directional sensitivities.
- Test missing exposures, scenario revisions, boundary conditions, and repeatability from a fixed input snapshot.

## Controls and FDE deliverables

Maintain model inventory and approval, independent validation, access controls, reproducibility, audit trails, and explicit limitations. Do not silently substitute assumptions or present generated explanations as model validation.

Document the process map, data lineage, scenario governance, calculation boundaries, validation plan, findings, and open decisions.
