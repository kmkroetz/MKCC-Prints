# MKCC Prints v1.3 — Craft Shows + QR Codes

This version builds on the v1.2 app and keeps Firebase Storage/Blaze disabled.

## Added
- Craft show workflow: create event, load stock, sell at event, close event, view results.
- Event inventory tracked separately from available stock.
- Craft-show event fee and other expenses.
- Craft-show sales record revenue and production cost.
- Closing a show returns remaining event inventory to available stock.
- POS event selector for active craft shows.
- POS accepts the existing barcodes/SKUs and QR-code values.
- Phone camera scanner supports common barcodes and QR codes through `BarcodeDetector` when supported by the browser.
- Printable product labels with product name, price, Code 128 barcode, and QR code.
- QR code value uses SKU when available; otherwise the stock item ID.
- Product photo upload is intentionally paused until Firebase Storage/Blaze is enabled.

## Firebase
- Firestore and Firebase Authentication continue to be used.
- Firebase Storage is not required for this version.

## Use
1. Open Stock Prints and create a product with a SKU and/or barcode.
2. Use **🏷️ Labels** to generate printable barcode + QR labels.
3. Create a Craft Show and enter its fee/other expenses.
4. Use **Load Stock** to assign inventory to the event.
5. Open POS, select the event, and scan the barcode or QR code.
6. Complete sales using Cash, Card, or Other.
7. Close the show to return unsold event inventory and review the event results.
