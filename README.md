# Data Transformation 

# Project Overview

This project demonstrates advanced data transformation techniques on a sample employee dataset. The core objective is to clean, enhance, and enrich employee records by applying string manipulations, date-time handling, role deduplication, and categorization — resulting in a structured and insightful Excel report.


# Key Transformations

- **Name Construction:** Combined `first_name` and `last_name` into a new `full_name`.
- **Date-Time Handling:**
  - Converted `date` to datetime format.
  - Extracted day name (e.g., Monday) and formatted time (`HH:MM:SS`).
  - Calculated `working_days` from hire date to the current date.
- **String Processing on Job Titles:**
  - Extracted `job_prefix` (first 3 letters) and `job_suffix` (last 3 letters).
- **Duplicate Role Detection:**
  - Marked duplicate job titles and generated a `unique_role_key` for each.
- **Role Categorization:**
  - Mapped job titles to broader categories (e.g., Engineering, Management, Support).
- **Excel Reporting:**
  - Exported the final dataset to a professional Excel file using `pandas` and `openpyxl`.

---

# Files in the Repository

- | File                             | Description                                      |
- |----------------------------------|--------------------------------------------------|
- | `employee_transformations.py`    | Main Python script to perform all transformations. |
- | `Employee_records.csv`           | Sample input dataset.                           |
- | `Advanced_Employee_Report.xlsx`  | Final enriched Excel report.                    |


# How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/data-transformation-assignment.git
   cd data-transformation-assignment
2. Install dependencies:
   - pip install pandas openpyxl
     
3. Run the script:
   - python employee_transformations.py
  
# Demo Screenshots

1. Raw Dataset:

   ![Screenshot 2025-05-14 204911](https://github.com/user-attachments/assets/37f6bc5f-3b9b-4e81-9d5c-a21c36a0b82b)

2. After Data Transformation:

   ![Screenshot 2025-05-14 204832](https://github.com/user-attachments/assets/55d32765-472b-40b9-917a-14d4346fcf77)


# Value to Business

 - This automated solution provides HR and Analytics teams with:

   - Clean and readable employee data.
   - Role-based categorization for reporting.
   - Duplicate detection with unique role identifiers.
   - Easy-to-read Excel reports with professional formatting.
  
  
# Credits
 - Developed by Mallipeddi Chandrahas





