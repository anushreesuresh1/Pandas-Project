# iPhone Price Analysis using Pandas

## Table of Contents
- [Project Overview](#project-overview)
- [Repository Structure](#repository-structure)
- [Setup Instructions](#setup-instructions)
- [Running the Script](#running-the-script)
- [Output Files Generated](#output-files-generated)
- [Report Details](#report-details)
- [Requirements](#requirements)
- [Author](#author)

---

## Project Overview
This project performs a complete data analysis of Apple products using **Python** and **Pandas**.
It explores the dataset, analyzes prices, extracts model names, sorts by star rating, and generates detailed reports in both **CSV** and **Excel** formats.

---

## Repository Structure
```
├── data/
│ ├── apple_products.csv # Input dataset
│ ├── apple_products_with_model.csv # Dataset with new 'Model Name' column
│ ├── iphone_analysis_report.csv # Final report (CSV)
│ └── iphone_analysis_report.xlsx # Final report (Excel)
│
├── scripts/
│ └── iphone_analysis.py # Final analysis script
│
├── README.md # Documentation
└── requirements.txt # Required dependencies
```

---

## Setup Instructions

### 1. Clone the Repository
```bash
git clone [https://github.com/](https://github.com/)<your-username>/iphone-price-analysis.git
cd iphone-price-analysis
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
```

### 3. Activate the Virtual Environment
**Windows:**
```bash
venv\Scripts\activate
```

**macOS/Linux:**
```bash
source venv/bin/activate
```

### 4. Install Dependencies
```bash
pip install -r requirements.txt
```

---

## Running the Script
Once everything is set up, run the script:

```bash
python scripts/iphone_analysis.py
```

This will generate the final output files in the `data/` directory.

---

## Output Files Generated

| File Name | Description |
| :--- | :--- |
| `apple_products_with_model.csv` | Dataset with the new Model Name column |
| `iphone_analysis_report.csv` | Combined report (summary + filtered + sorted data) |
| `iphone_analysis_report.xlsx` | Same report in Excel format |

---

## Report Details

### Summary Table
Displays the **maximum price**, **minimum price**, and **total row count**.

### Products ≥ ₹1,00,000
Lists all **iPhone models** priced at or above **₹1,00,000**.

### Sorted Dataset
Contains all Apple products sorted by **Star Rating** in descending order.

---

## Key Learnings
- Data loading and exploration using **Pandas**
- **String manipulation** using methods like `upper()`, `lower()`, `strip()`, and **slicing**
- **Feature engineering** by extracting model names from text
- Sorting and filtering datasets based on conditions
- Exporting data to **CSV** and **Excel** formats

---

## Requirements
All dependencies are listed in the `requirements.txt` file.

### Example `requirements.txt`:
```text
pandas
openpyxl
```
