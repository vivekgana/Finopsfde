# Financial Services Use Cases

This repository is a discovery and analysis workspace for forward-deployed engineering (FDE) teams working with financial services and insurance clients. Each use case has a dedicated brief covering scope, discovery questions, candidate workflow, measures, validation, and controls.

## Use cases

| # | Use case | Focus |
|---|---|---|
| 01 | [Insurance processing](use-cases/01-insurance-processing/README.md) | Policy application, underwriting support, issuance, and servicing |
| 02 | [Financial stress testing](use-cases/02-financial-stress-testing/README.md) | Scenario-based portfolio and balance-sheet resilience analysis |
| 03 | [Bond trading analysis](use-cases/03-bond-trading-analysis/README.md) | Research and decision support for bond market activity |
| 04 | [Fed rate video analyzer](use-cases/04-fed-rate-video-analyzer/README.md) | Extracting and verifying rate-related information from public video briefings |
| 05 | [Claim processing](use-cases/05-claim-processing/README.md) | General insurance claim intake, triage, and adjudication support |
| 06 | [Sovereign and corporate bond trading](use-cases/06-sovereign-corporate-bond-trading/README.md) | Trading workflows across government and corporate debt markets |
| 07 | [Cross-border regulation](use-cases/07-cross-border-regulation/README.md) | Regulatory obligations across jurisdictions and legal entities |
| 08 | [Bank fraud and AML](use-cases/08-bank-fraud-aml/README.md) | Fraud detection, alert investigation, and anti-money-laundering operations |
| 09 | [Auto assistance claim processing](use-cases/09-auto-assistance-claim-processing/README.md) | Motor claims and roadside assistance coordination |
| 10 | [Conversational banking](use-cases/10-conversational-banking/README.md) | Customer service and self-service banking conversations |

## Workspace structure

```text
use-cases/
	01-insurance-processing/
		README.md
	02-financial-stress-testing/
		README.md
	...
	10-conversational-banking/
		README.md
```

Keep each use case's context and analysis in its own folder. As work grows, add only the artifact folders needed for that engagement:

```text
<use-case>/
	README.md       # scope, current state, proposed workflow, risks, measures
	discovery/      # interview notes and requirements; remove personal data
	data/           # schemas and approved synthetic or de-identified samples
	diagrams/       # process, system, and data-flow diagrams
	validation/     # test plans, evaluation results, and acceptance criteria
	reports/        # decision records and client-ready findings
```

Do not put credentials, production customer data, or confidential client material in this repository. Follow the client's approved environment, retention policy, and data-handling requirements.

## FDE analysis workflow

1. Establish the business outcome, users, process boundary, jurisdictions, and system of record.
2. Map the current workflow, decision points, handoffs, exceptions, and baseline performance.
3. Inventory source data and integrations; confirm access, quality, lineage, and permitted use.
4. Propose a bounded workflow and identify decisions that require an authorized human.
5. Define measurable acceptance criteria, representative test cases, and a rollback or escalation path.
6. Review security, privacy, auditability, model risk, and regulatory obligations with client owners before piloting.

Treat the use-case briefs as discovery starting points, not statements of client policy or regulatory advice. Validate assumptions with business, risk, compliance, security, and technology stakeholders.