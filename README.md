MKCC Prints v1.4.1 — Login Diagnostic Fix

Based on v1.4.0.

Changes:
- Added a 15-second Firebase sign-in timeout with a useful error message.
- Login errors now show the Firebase error code.
- Firebase initialization errors are surfaced instead of silently failing.
- No business, Firestore, Stock Prints, POS, Craft Show, or Defaults logic changed.
