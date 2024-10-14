
# BRCA Clinical and Protein Data

## Description
This dataset contains clinical and protein expression data for patients diagnosed with BRCA (Breast Cancer). The dataset combines various clinical attributes, including patient demographics, tumor characteristics, hormone receptor status, and surgical details, with protein expression data. It is intended for research purposes, particularly for analyzing the relationships between clinical features and molecular data to understand disease progression and treatment outcomes.

## Data Overview
The dataset consists of the following columns:

1. **Patient_ID**: Unique identifier assigned to each patient.
2. **Age**: Patient's age at the time of diagnosis.
3. **Gender**: Patient's gender (e.g., FEMALE).
4. **Protein1, Protein2, Protein3, Protein4**: Measured levels of various proteins related to the patient’s condition. These proteins may be biomarkers that help in understanding the biological processes of the cancer.
5. **Tumour_Stage**: The clinical stage of the tumor, which provides insight into how advanced the cancer is (e.g., Stage I, II, III). This is based on criteria such as tumor size and the spread of the disease.
6. **Histology**: The type of tissue abnormality (e.g., Infiltrating Ductal Carcinoma, Mucinous Carcinoma), which helps in classifying the nature of the breast cancer.
7. **ER status (Estrogen Receptor)**: Whether the cancer cells have estrogen receptors (Positive or Negative). This status is crucial for determining whether hormone therapy is suitable.
8. **PR status (Progesterone Receptor)**: Whether the cancer cells have progesterone receptors (Positive or Negative). Like ER status, this helps guide treatment decisions.
9. **HER2 status**: The status of HER2 protein receptors, which can be either Positive or Negative. HER2-positive breast cancers tend to grow more aggressively, and specific therapies target this receptor.
10. **Surgery_type**: The type of surgery the patient underwent (e.g., Lumpectomy, Modified Radical Mastectomy). This indicates the surgical approach taken to remove the tumor.
11. **Date_of_Surgery**: The exact date when the surgical procedure was performed.
12. **Date_of_Last_Visit**: The date of the patient's most recent follow-up visit, which is used to track the patient's post-surgery progress and overall health.
13. **Patient_Status**: The current health status of the patient (Alive or Dead) at the time of the last visit. This helps in analyzing survival outcomes.
14. **Tumor_Stage_Numeric**: A numerical representation of the tumor stage (e.g., 1, 2, 3), used for more granular analysis.
15. **Year_of_Surgery**: The year in which the surgery was performed, which can help in time-based analysis, especially for longitudinal studies.

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

##  Visualization on the Data

Data visualization is more than just presenting numbers in a graphical format—it’s the key to unlocking the hidden meanings within complex datasets. By transforming raw data into visual insights, we can bridge the gap between information and understanding. It enables us to quickly identify patterns, spot trends, and make data-driven decisions that are both informed and impactful. Visualization makes the invisible, visible—guiding us from raw information to actionable insights.

Through visual analysis of the dataset, we seek to answer the following crucial questions:

1. What is the most common type of surgery performed among patients?
2. Which type of surgery has the highest success rate in treating breast cancer?
3. Which age group benefits the most from each type of surgery?
4. What is the most common age group among males and females diagnosed with cancer?
5. What is the most common tumor stage at the time of diagnosis?
6. How do tumor stages differ across different age groups and genders?
7. What is the survival rate based on the tumor stage at the time of surgery?
8. How does the type of surgery affect long-term patient outcomes?
9. What is the distribution of surgery types across different tumor stages?
10. Are there differences in tumor stages and outcomes between patients based on the year of surgery?
11. What patterns or trends can be identified in the dataset over time?
12. What percentage of patients diagnosed with Infiltrating Lobular Carcinoma survived after treatment?
13. What was the most common type of surgery performed on patients with Infiltrating Lobular Carcinoma, and how did it impact survival?
