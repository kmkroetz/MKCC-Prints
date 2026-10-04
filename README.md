MKCC Prints v1.4.0 — Business Defaults & Cost Model

Built from v1.3.1 Product Profitability.

Theme changes only:
- Scarlet primary accent (#BA0C2F)
- Gray secondary controls and borders
- Dark charcoal surfaces with white text
- Existing QR/barcode labels remain black/white
- No feature or Firebase logic changes


## v1.4.0 changes
- Added Business Defaults for labor rate, default filament cost per gram, and default production/consumable cost.
- Stock Prints now track filament grams per item and print hours per item. Print hours are informational only.
- Stock Print production cost is material + production/consumable cost; printer-time labor is not included.
- Print Jobs use separate extra labor hours for design/setup/finishing/assembly, using the Business Defaults labor rate.
- Selling price remains manually controlled.
