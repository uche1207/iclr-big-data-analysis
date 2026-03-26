# Big Data Analytics of ICLR Submissions and OpenAlex Records

## Overview
This project analyses ICLR paper submissions using PySpark in Databricks. It combines submission data with OpenAlex citation metadata to study review outcomes, research trends, and research impact.

The goal is to provide actionable insights for understanding peer review variability, keyword trends, and citation impact across years.

---

## Key Features
- Distributed data processing with PySpark  
- Cleaning and transformation of nested datasets (scores and keywords)  
- Analysis of 50,000+ research paper submissions  
- Identification of emerging keyword trends over time  
- Integration with OpenAlex for citation-based research impact  

---

## Key Results
- 27,403 withdrawn papers, exceeding both accepted and rejected counts  
- 1,514 accepted papers contained at least one low reviewer score (<5)  
- Top papers achieved mean scores between 9.0 and 10.0, with low standard deviations  
- Emerging research topics detected: `llm`, `test-time scaling`, `spatial reasoning`  
- No low-score papers reached the top 5% citation impact  

---

## Tech Stack
- Python  
- PySpark  
- Apache Spark  
- Databricks  

---

## How to Run
1. Upload datasets to your Databricks workspace  
2. Open `ICLR_Code_250124837.ipynb`  
3. Run all cells in order  
4. The notebook outputs cleaned datasets, analysis results, and visualisations  

> Note: Ensure the OpenAlex dataset subset is available in the notebook environment for citation-based analysis.
