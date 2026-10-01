# MKCC Prints v1.2

Adds Craft Shows and stock-product photos.

## Firebase Storage
Enable Storage in Firebase Console before using stock photo uploads.

Suggested Storage rules for this authenticated app:
```text
rules_version = '2';
service firebase.storage {
  match /b/{bucket}/o {
    match /stockPrints/{userId}/{allPaths=**} {
      allow read, write: if request.auth != null;
    }
  }
}
```
