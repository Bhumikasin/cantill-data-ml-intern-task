# cantill-data-ml-intern-task
config-driven data engineering and ml spend classification pipeline

# Cantill.ai – Data & ML Intern Task

## Project Overview
This project focuses on building a data processing and machine learning pipeline for procurement spend analysis.

The system processes raw purchase and invoice data, cleans inconsistent records, identifies duplicate suppliers and items, handles exclusions, and classifies purchase descriptions into company-specific taxonomies.

## Objectives
- Data ingestion from multiple sources.
- Data cleaning and preprocessing.
- Supplier and item deduplication.
- Invoice exclusion and validation.
- Currency and tax normalization.
- ML-based spend classification.
- Taxonomy-based category prediction.

## Companies
- Company A: Mining operations of a chemicals group.
- Company B: Metal packaging manufacturer.

## Technology Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Machine Learning
- Natural Language Processing

## Project Structure
```text
cantill-data-ml-intern-task/
├── configs/
├── src/
├── outputs/
├── README.md
├── APPROACH.md
├── DECISIONS.md
├── requirements.txt
└── .gitignore
```

## Installation
```bash
pip install -r requirements.txt
```

## Execution
The pipeline will be executed using company-specific configuration files.

## Data Privacy
Original company datasets are confidential and are not included in this public repository.

## Author
Data & ML Intern Candidate

