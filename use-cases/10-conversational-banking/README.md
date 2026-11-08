# Conversational Banking

## Objective

Help customers complete supported banking service tasks through conversational channels, with clear identity verification, accurate information, and seamless transfer to staff. Keep payment execution, account changes, and other high-impact actions behind approved authorization controls.

## Discovery questions

- Which channels, customer segments, languages, and service intents are in scope?
- Which systems provide authoritative balances, transaction status, fees, and product terms?
- What authentication and step-up verification is required for each task?
- Which intents must transfer to a person, and how is context handed over securely?

## Inputs and outputs

- **Inputs:** Customer messages, approved knowledge content, authenticated session context, and authorized account data.
- **Outputs:** Source-grounded answers, guided service actions, secure handoffs, and conversation audit records.
- **Integrations:** Digital banking channels, identity and access management, core banking, knowledge management, and contact center systems.

## Candidate workflow

1. Identify intent and determine whether the user is authenticated for the requested information or action.
2. Retrieve answers only from approved knowledge or authorized account services.
3. Confirm required details and authorization before any account-impacting action.
4. Complete supported tasks through governed APIs and provide a clear confirmation or failure state.
5. Transfer uncertain, sensitive, disputed, or unsupported requests to staff with appropriate context.

## Measures and validation

- Track containment alongside task completion, answer accuracy, authentication failures, transfer success, complaints, and repeat contacts.
- Test adversarial phrasing, ambiguous intent, outdated knowledge, account-specific questions, and failed transactions.
- Evaluate accessibility, language quality, privacy leakage, and safe refusal or escalation behavior.

## Controls and FDE deliverables

Enforce authentication, authorization, consent, data minimization, secure session handling, and auditable action logs. Do not expose credentials or sensitive account data in logs, and do not claim an action succeeded without system confirmation.

Document supported intents, authentication matrix, knowledge sources, action permissions, handoff behavior, evaluation plan, and incident response path.
