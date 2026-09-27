# Security Notes

Escrow logic must protect three things: custody, authorization, and state transitions.

## Core questions
- Who can fund the escrow?
- Who can release funds?
- Who can refund funds?
- Can a state transition happen twice?
- Can the recorded amount diverge from the controlled coin?
- What happens if an expected counterparty never acts?

## Deployment policy
Do not deploy or advertise the prototype as production-ready until it has been compiled against the selected Sui framework version, tested on a controlled network, and reviewed for authorization and accounting correctness.
