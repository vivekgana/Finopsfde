# Bond Trading Analysis

## Objective

Provide research and decision support for bond-market analysis, including instrument comparisons, market movements, portfolio exposures, and scenario effects. This use case focuses on analysis and insight generation rather than automated order execution.

## Discovery questions

- Which instruments, markets, strategies, desks, and time horizons are in scope?
- Which prices, curves, ratings, reference data, and internal positions are authoritative?
- How are liquidity, transaction costs, and stale or indicative quotes handled?
- Who reviews recommendations, and what restrictions govern investment advice or trading decisions?

## Inputs and outputs

- **Inputs:** Approved market data, instrument terms, reference data, research, portfolio positions, and strategy assumptions.
- **Outputs:** Comparable instrument views, market and portfolio summaries, scenario analysis, and source-linked research notes.
- **Integrations:** Market-data providers, portfolio systems, research repositories, and approved analytics platforms.

## Candidate workflow

1. Identify instruments and normalize identifiers, currencies, timestamps, and conventions.
2. Check quote freshness, source coverage, and discrepancies before calculating comparisons.
3. Analyze price, yield, spread, duration, and relevant scenario sensitivities with stated assumptions.
4. Present source-linked findings, uncertainty, and limitations to an authorized analyst.
5. Capture review, corrections, and any downstream decision separately from the analysis output.

## Measures and validation

- Track data freshness, instrument-match accuracy, analyst review time, correction rate, and reproducibility.
- Reconcile calculations against approved pricing or analytics systems and independently check representative instruments.
- Test corporate actions, missing or crossed quotes, unusual day-count conventions, and market closures.

## Controls and FDE deliverables

Use licensed data only within permitted terms. Apply entitlements, maintain source and timestamp lineage, separate analysis from order handling, and require authorized human review. Clearly label indicative data and avoid implying guaranteed performance.

Document the instrument universe, data dependencies, calculation definitions, workflow boundaries, test results, and analyst acceptance criteria.
