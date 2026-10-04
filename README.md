MKCC Prints v1.4.2 — Login startup fix

Fixes the login screen remaining on “Login successful — loading app...” by opening the app immediately after successful authentication and moving Firestore startup/seed work to a non-blocking async task.
