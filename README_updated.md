
# BRCA Clinical and Protein Data

BRCA Dataset - Data Description and Cleaning Process
Project Overview
This dataset contains information on BRCA patients and their medical details, including protein levels, tumor stages, and patient visit history. The data has been cleaned and processed to ensure consistency and accuracy for further analysis. This project focuses on preparing the dataset for research and machine learning tasks.
Dataset Description
The dataset includes the following columns:
Protein1, Protein2, Protein3, Protein4: These columns represent protein levels recorded for each patient. Initially, some columns had blank values and invalid entries which were replaced with NULL to allow for better data analysis.
Date_of_Surgery: The date of the patient's surgery.
Date_of_Last_Visit: The most recent date the patient visited the clinic. Invalid future dates (e.g., 2026) and placeholder dates (e.g., 01-01-1900) were removed to ensure only valid dates are included.
Age: The age of the patient, converted into an integer format for better use in analysis.
Tumour_Stage: The stage of the tumor. The values were grouped into numerical categories: I (1), II (2), and III (3).
Patient_Status: The status of the patient. Blank entries were replaced with 'Unknown'.
Year_of_Surgery: Extracted from the Date_of_Surgery column to simplify year-based analysis.
Data Cleaning Process
1. Handling Invalid Numeric Values
Before Modification: Some numeric columns, such as Protein1, Protein2, etc., contained blanks or invalid values that were non-numeric.
After Modification: These blanks were replaced with NULL, and the columns were converted to numeric types (Decimal).
2. Removing Invalid Date Entries
Before Modification: The Date_of_Last_Visit column contained invalid entries such as 01-01-1900 or dates in the future (e.g., 2026).
After Modification: Rows with invalid dates were removed, ensuring all dates fall within a logical range for patient visits.
3. Converting Tumor Stages
Before Modification: The Tumour_Stage column had categorical values (I, II, III).
After Modification: These were converted to numerical categories (1, 2, 3) for easier analysis, and blanks were replaced with NULL.
4. Adjusting Patient Status
Before Modification: The Patient_Status column had some missing values (blanks).
After Modification: Blanks were replaced with Unknown to provide a consistent dataset.
5. Extracting Year of Surgery
Before Modification: The year of surgery was embedded within the Date_of_Surgery column.
After Modification: A new column Year_of_Surgery was created by extracting the year from the Date_of_Surgery column.
Examples from the Dataset
Protein Levels:
Before: Protein1 = "", Protein2 = "", Protein3 = "abc" (non-numeric value)
After: Protein1 = NULL, Protein2 = NULL, Protein3 = NULL (non-numeric value removed)
Date Cleaning:
Before: Date_of_Last_Visit = 01-01-1900, Date_of_Surgery = 2026-04-15
After: Invalid date rows removed, only valid dates remain.
Usage Guide

