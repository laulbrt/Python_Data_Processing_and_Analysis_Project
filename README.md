# Python Data Processing and Analysis Project

This project focuses on processing, cleaning, and analyzing datasets provided as CSV files.  
It includes data consolidation, transformation, log inspection, and the implementation of Python scripts to automate the workflow.

The project was completed as part of an academic assignment.

---

## Project Overview

The objective of this project is to load, clean, and manipulate structured datasets in order to extract meaningful insights.  
The project uses Python scripts to parse raw data, consolidate information, detect anomalies, and organize outputs for further analysis.

The workflow includes:

- Reading and merging CSV files  
- Cleaning inconsistent or missing values  
- Transforming and organizing tabular data  
- Extracting useful indicators  
- Logging system activity  
- Exporting consolidated results  

The final script (`Projet_Python.py`) contains the core logic of the project.

---

## Main Features

### Data Loading
- Import multiple CSV files  
- Validate data structure and integrity  
- Handle missing or invalid entries  

### Data Consolidation
- Merge datasets into unified tables  
- Align columns and normalize formats  
- Detect duplicates or inconsistencies  

### Data Cleaning
- Remove invalid rows  
- Convert data types  
- Standardize values for further processing  

### Analysis and Processing
- Compute aggregated statistics  
- Extract key performance indicators  
- Generate structured outputs  

### Logging
- Write runtime information to a log file  
- Track errors and warnings  
- Keep an execution trace for debugging  

---

## Files Included

- `Projet_Python.py` – Main Python script  
- `consolidated_data.csv` – Consolidated dataset  
- `consolidated_bulletins.csv` – Bulletin dataset  
- `vulnerability_scanner_20250114.log` – Log file generated during execution  
- `Projet_Python_2024_A3_V2.pdf` – Assignment instructions  
- `untitled0.py`, `untitled1.py` – Test or draft scripts  

---

## How It Works

1. The script loads each CSV file.  
2. The data is checked, cleaned, and transformed.  
3. Consolidated datasets are generated.  
4. Logs are written to track anomalies or important events.  
5. Final results are exported as CSV files.

---

## Technologies Used

| Purpose | Technology |
|---------|------------|
| Data Processing | Python |
| Data Handling | pandas |
| Logging | Python logging module |
| File Management | CSV files |
| Documentation | PDF |

---

## Execution

### Run the main script

```bash
python Projet_Python.py
