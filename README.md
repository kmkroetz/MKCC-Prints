# MKCC Prints v1.2.3.4 — QR + Barcodes, No Photos

Built from the working v1.2.2 Craft Shows version.

- Craft Shows retained
- Firebase Auth/Firestore retained
- Firebase Storage/photos completely removed from the stock interface and code
- Stock labels support Code 128 barcodes and QR codes
- Label libraries load only when the user clicks Label, so they cannot interfere with login
- No Blaze billing required

- Labels are generated in the current page so barcode/QR rendering does not depend on a popup tab.
