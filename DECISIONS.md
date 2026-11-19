
# Data Processing Decisions

## Company A
- ERP values are treated as net spend.
- Invoice tool gross amounts must be converted to net amounts using VAT.
- Missing VAT rates are assumed to be 15%.
- ERP records take priority when matching duplicate purchases.
- Duplicate invoice records are excluded.

## Company B
- Reporting currency is USD.
- Currency conversion uses the supplied exchange rates.
- Missing exchange rates require monthly FX lookup.
- Supplier IDs are used for supplier identification.

## Common Rules
- Only approved or paid invoices are included.
- Cancelled invoices are excluded with CANCELLED reason code.
- Unapproved invoices are excluded with NOT_APPROVED reason code.
- Non-procurement transactions are excluded.
- Duplicate records are excluded.
- Taxonomy categories are loaded dynamically from the supplied files.

## Limitations
Matching and classification decisions must be validated against the supplied datasets and labels.
