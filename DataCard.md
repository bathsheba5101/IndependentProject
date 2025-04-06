---
name: NHANES 2023 - Breast Cancer Survivors Dataset
version: 1.0
description: >
  This dataset contains data from the NHANES 2023 study on breast cancer survivors, with a focus on race, ethnicity, social determinants of health (SDOH), and stress biomarkers such as C-reactive protein (CRP).
  The dataset includes information on CRP levels, cortisol levels, and other stress-related biomarkers for breast cancer survivors. 
  It is specifically focused on Black, Latina/Hispanic women and their health outcomes in relation to stress and inflammation.
url: https://www.cdc.gov/nchs/nhanes/index.html
---

## Dataset Overview

### Purpose
This dataset is part of an analysis to study the relationship between stress, biological aging, and health outcomes in women with history of breast cancer, with an emphasis on race and ethnicity. This data will be used to explore the disparities in health outcomes for women of color, specifically those who have history of breast cancer.

### Size
The dataset contains data from ~100 participants, all of whom are female, focusing on women with history of breast cancer.

### Data Collection
The data was collected as part of the National Health and Nutrition Examination Survey (NHANES) 2023 cohort, which includes health and demographic information from participants. 

### Variables
- **SEQN**: Respondent sequence number.
- **RIAGENDR**: Respondent gender. (1=Male, 2=Female).
- **RIDAGEYR**: Respondent age year of survey.
- **RIDRETH1**: Respondent race/ethnicity. (1 = Mexican American,	2 = Other Hispanic, 3 =	Non-Hispanic White,	4 =	Non-Hispanic Black, 5	= Other Race - Including Multi-Racial, . =	Missing)
- **DMDMARTZ**: Respondent martial status. (1 = Married/Living with partner,	2 = Widowed/Divorced/Separated,	3 = Never married, 77 = Refused, 	99 = Don't know,	. = Missing)
- **DMDEDUC2**: Respondent education level Adults 20+. (1 = Less than 9th grade, 2 = 9-11th grade (Includes 12th grade with no diploma),	3 = High school graduate/GED or equivalent, 	4 = Some college or AA degree,	5 = College graduate or above, 7 =	Refused,	9	= Don't know,	.	= Missing)
- **INDFMMPI**: Family monthly poverty level index.
- **MCQ230A**: Type of first cancer (specifically breast cancer = 14 for this dataset).
- **LBXHSCRP**: High-Sensitivity C-Reactive Protein (CRP) levels.

### Data Access
This dataset can be accessed through the NHANES website at [https://www.cdc.gov/nchs/nhanes/index.htm](https://www.cdc.gov/nchs/nhanes/index.htm). The data files used in this analysis include:
- `DEMO_L.xpt` (Demographics)
- `MCQ_L.xpt` (Medical Conditions)
- `INQ_L.xpt` (Income and Assets)
- `HSCRP_L.xpt` (C-Reactive Protein)


### Citation

 National Health and Nutrition Examination Survey (NHANES) 2023. Available at [https://www.cdc.gov/nchs/nhanes/index.htm](https://www.cdc.gov/nchs/nhanes/index.htm).

## Data Usage

### Purpose and Limitations
This dataset is being used to analyze disparities in health outcomes among women of color with history of breast cancer, with a focus on how social determinants of health and biological markers such as CRP influence these outcomes. The analysis specifically focuses on CRP and stress levels among these populations.

### Potential Biases
Since this dataset focuses on women with history of breast cancer, generalizability to other populations could be limited.

### Data Quality
Data quality checks have been conducted, and rows with missing values for key variables (e.g., CRP, cortisol levels) have been excluded from analysis.

## License

NHANES Data Use Agreement: https://www.cdc.gov/nchs/policy/data-user-agreement.html
