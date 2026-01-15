# My colab link : [Google Colab](https://colab.research.google.com/drive/1vWu62ncZXTBpqUe6XG0QSNrVAl09pn11?usp=sharing)
# Task 1: Understanding Dataset & Data Types

## Overview
Exploratory Data Analysis of Student Performance dataset with 5,000 records and 15 features.

## Dataset Info
- **Size:** 5,000 rows × 15 columns
- **Missing Values:** None ✅
- **Target:** GradeClass (multi-class:  0, 1, 2, 3)

## Columns
**Identifiers:** StudentID

**Demographics:** Age, Gender, Ethnicity

**Academic:** GPA, StudyTimeWeekly, Absences, ParentalEducation

**Engagement:** Tutoring, ParentalSupport, Extracurricular, Sports, Music, Volunteering

## Data Types
- **int64:** 14 columns
- **float64:** 1 column (GPA)

## Key Statistics
| Metric | Value |
|--------|-------|
| Mean Age | 16.49 years |
| Mean GPA | 3.29/4.0 |
| Avg Study Time | 10.03 hrs/week |
| Avg Absences | 15.07 days |

## Class Distribution
- Grade 0: 43.5% (2,175)
- Grade 1: 23.0% (1,152)
- Grade 2: 20.5% (1,023)
- Grade 3: 13.0% (650)

## Quality
✅ No missing values
✅ Complete dataset
⚠️ Class imbalance (Grade 0 dominant)

## Next Steps
1. Remove StudentID (identifier only)
2. Handle class imbalance
3. Feature scaling & engineering
4. Model training
