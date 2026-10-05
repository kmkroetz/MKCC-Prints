MKCC Prints v1.5.0 — Stability Fix

Built from v1.5.0.

Fixes:
- Restores missing Business Defaults functions so the main script can finish registering all event handlers and Firebase auth-state handling.
- Business Defaults stored at settings/businessDefaults.
- Logout now reports errors instead of silently doing nothing.
- Printer and Stock Print status messages explicitly confirm successful data loads, preventing stale permission text from remaining after a successful snapshot.
- No changes to existing POS, Craft Show, inventory, or financial workflows.


## v1.5.0 — POS Deals
- Quantity-based deal groups
- Mix-and-match deals across multiple stock products
- Multiple quantity tiers per deal (example: 1/$3, 2/$5, 3/$7)
- POS automatically selects the best valid tier combination
- Sale records save the discounted revenue for accurate reporting
