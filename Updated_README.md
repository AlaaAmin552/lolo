
# Project Title: BRCA Clinical and Protein Data Analysis

## Description
This dataset provides clinical and protein expression data for patients with BRCA (Breast Cancer). The dataset includes a range of variables such as patient demographics, protein levels, tumor stage, and treatment information.

## Data Columns:
1. **Patient_ID**: A unique identifier for each patient.
2. **Age**: The age of the patient.
3. **Gender**: The gender of the patient (e.g., FEMALE).
4. **Protein1, Protein2, Protein3, Protein4**: Protein expression levels related to the disease.
5. **Tumour_Stage**: The stage of the tumor (e.g., I, II, III).
6. **Histology**: The histological subtype of the tumor (e.g., Infiltrating Ductal Carcinoma, Mucinous Carcinoma).
7. **ER status**: Estrogen receptor status (Positive/Negative).
8. **PR status**: Progesterone receptor status (Positive/Negative).
9. **HER2 status**: HER2 protein receptor status (Positive/Negative).
10. **Surgery_type**: The type of surgery performed (e.g., Modified Radical Mastectomy, Lumpectomy).
11. **Date_of_Surgery**: The date the surgery was performed.
12. **Date_of_Last_Visit**: The date of the patient's last follow-up visit.
13. **Patient_Status**: The patient's current status (Alive/Dead).
14. **Tumor_Stage_Numeric**: The numeric representation of the tumor stage (e.g., 1, 2, 3).
15. **Year_of_Surgery**: The year the surgery was performed.

## Usage
This dataset can be used for analyzing the relationships between clinical features and protein expression in BRCA patients, and for investigating potential prognostic factors.

## Notes
- The dataset includes sensitive patient data. Ensure that any usage complies with ethical standards and guidelines.

## EDA (Exploratory Data Analysis)

The following insights have been drawn from the analysis of the BRCA dataset:

1. **Patient Age Distribution**: The majority of patients diagnosed with cancer fall within the age range of 35 to 89 years. This wide range emphasizes the need for early screening across various age groups.
2. **Cancer Stage Awareness**: Most patients discover the disease at Stage II, highlighting the critical need for earlier detection and education.
3. **Surgery Trends**: The highest number of surgeries occurred in 2018. Interestingly, most patients who underwent surgery are currently alive, with 2017 seeing the lowest number of surgeries.
4. **Gender Disparity**: The majority of patients are women, though the data reveals that a smaller proportion of men are also affected by the disease.
5. **Survival Rates**: Approximately 77% of patients survived, while 20% succumbed to the disease. These figures underscore the severe risk posed by breast cancer.
6. **Age Distribution Validation**: The histogram confirms the age distribution insights observed earlier, reinforcing the significant age range of affected individuals.
7. **Histology-Specific Insights**:
    - **Mucinous Carcinoma**: Discovered primarily in Stages I and II. Unfortunately, patients reaching Stage II face higher mortality rates.
    - **Infiltrating Lobular Carcinoma**: Occurs across all ages but predominantly in Stage I.
    - **Infiltrating Ductal Carcinoma**: Also seen across all ages, with most cases detected in Stage I.
8. **HER2 Status and Survival**:
    - **HER2 Negative**: Approximately 79% of patients are alive, while 21% have passed away.
    - **HER2 Positive**: Around 87% of patients are alive, with 13% deceased.
9. **Surgical Success Rates**:
    - **Lumpectomy**: The most successful surgery, with 86% survival and 14% mortality.
    - **Modified Radical Mastectomy**: Has a slightly lower success rate, with 78% survival and 22% mortality.
10. **Surgery Distribution**: As highlighted earlier, 2018 saw the highest number of surgeries, while 2017 experienced the lowest.
11. **Histology and Surgery Correlation**:
    - **Infiltrating Ductal Carcinoma**: Managed through various surgeries, but Lumpectomy and Modified Radical Mastectomy are commonly employed.
    - **Infiltrating Lobular Carcinoma**: Also treated with different surgeries, though Lumpectomy and Modified Radical Mastectomy remain the most frequent choices.

### Protein Correlation Insights
1. **Protein Correlations**: Scatter plots with linear patterns between specific protein pairs suggest possible correlations between these proteins.
2. **Histology Patterns**: Certain histological types cluster around particular protein combinations, offering insights into how different cancer types may relate to protein expression.
3. **Protein Distributions**: The diagonal histograms illustrate the distribution of each protein, revealing patterns like skewness, multimodality, or normal distribution.

These findings provide a deep dive into the clinical and protein expression data, offering valuable insights into breast cancer diagnosis, treatment, and patient outcomes.
