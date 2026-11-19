
# Technical Approach

## 1. Data Ingestion
Load company purchase and invoice datasets using configurable file paths and column mappings.

## 2. Data Cleaning
Handle missing values, inconsistent date formats, invalid amounts and duplicate records.

## 3. Spend Validation
Identify cancelled, unapproved and non-procurement transactions using exclusion reason codes.

## 4. Supplier and Item Deduplication
Normalize supplier names and item descriptions to identify repeated entities.

## 5. Currency and Tax Processing
Convert monetary values into the required reporting currency and calculate net spend.

## 6. Machine Learning Classification
Use TF-IDF and cosine similarity to match purchase descriptions with taxonomy categories.

## 7. Output Generation
Generate company-specific CSV files with inclusion status, spend, supplier keys, item keys, category predictions and confidence scores.

## Validation
Accuracy, runtime and matching performance will be reported after testing on the supplied datasets.
