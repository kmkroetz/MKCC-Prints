MKCC Prints v1.4.5 — Stability Fix

Built from v1.4.5.

Fixes:
- Restores missing Business Defaults functions so the main script can finish registering all event handlers and Firebase auth-state handling.
- Business Defaults stored at settings/businessDefaults.
- Logout now reports errors instead of silently doing nothing.
- Printer and Stock Print status messages explicitly confirm successful data loads, preventing stale permission text from remaining after a successful snapshot.
- No changes to existing POS, Craft Show, inventory, or financial workflows.
