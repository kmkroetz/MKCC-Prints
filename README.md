MKCC Prints v1.4.3 — Startup/permissions resilience fix

Based on v1.4.2. Changes:
- Cloud startup no longer stops all data loaders if one optional seed/read operation is denied.
- Each collection loads independently and reports its own Firestore error.
- Fixed spool cache assignment so Print Jobs can populate from loaded spools.
- No changes to Firebase configuration, business logic, POS, Craft Shows, or Stock Print accounting model.
