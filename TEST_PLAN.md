# Escrow Test Plan

## Lifecycle
1. Create escrow.
2. Fund with the expected amount.
3. Release to the seller.
4. Refund to the buyer where the refund condition permits it.

## Negative cases
- Wrong buyer attempts a privileged action.
- Wrong seller attempts a seller-only action.
- Funding amount does not match the agreed amount.
- Release or refund is attempted after the escrow is already settled.
- Empty or invalid object references are supplied.

The final executable tests must be run against the exact Sui framework version used for implementation.
