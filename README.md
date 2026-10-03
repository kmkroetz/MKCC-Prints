# MKCC Prints v1.2.3.12

Adds safe Delete buttons to Stock Prints and Craft Shows.

- Stock Prints: Delete is blocked while inventory is assigned/held for a craft show.
- Craft Shows: Delete is available only after the show is closed and all remaining inventory has been returned.
- Shows with sales can still be deleted after closing, with a confirmation warning that the event/sales history will be permanently removed.
- No changes to Firebase Auth, Storage, QR/barcode labels, POS, or inventory assignment logic.
