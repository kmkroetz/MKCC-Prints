MKCC Prints v1.4.4 — Startup/permissions resilience fix

Based on v1.4.2. Changes:
- Cloud startup no longer stops all data loaders if one optional seed/read operation is denied.
- Each collection loads independently and reports its own Firestore error.
- Fixed spool cache assignment so Print Jobs can populate from loaded spools.
- No changes to Firebase configuration, business logic, POS, Craft Shows, or Stock Print accounting model.

v1.4.4 — Firestore auth/startup stability fix
- Refreshes the Firebase Auth ID token before opening Firestore listeners.
- Removes all automatic Firestore seed/write operations from login startup.
- Loads each Firestore section independently so one failure cannot block the app.
- No data deletion or Firebase configuration changes.
