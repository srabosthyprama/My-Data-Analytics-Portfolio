
# 🦟 Dengue Data Analysis Dashboard

An interactive Dengue Data Analysis Dashboard built to help users explore dengue test results by gender, age group, area type, house type, and local area in Dhaka, Bangladesh.

## 📸 Dashboard Preview

<img width="1855" height="725" alt="Dengue Dashboard" src="https://github.com/user-attachments/assets/96022bdb-4df1-409a-bc46-dc2c94b92509" />

The dashboard helps answer one main question:

**Which groups and areas have more positive dengue results in this dataset?**

> ⚠️ Note: This analysis covers only the records in this dataset. It does not represent all dengue cases in Dhaka or Bangladesh.

## 📊 Executive Overview: What Is Happening?

### 🔑 Key KPIs

| KPI | Value |
|---|---:|
| Total Records | 1,000 |
| Positive Results | 533 |
| Negative Results | 467 |
| Overall Positive Rate | 53.3% |
| Average Age | 35.9 years |
| Average Age of Positive Cases | 35.7 years |

The dataset contains 1,000 records, of which 533 have a positive outcome. This gives an overall positive rate of 53.3%.

### 💡 Key Insight

More than half of the records have a positive result. These figures describe the dataset only and should not be treated as the actual dengue rate for the whole city.

### 🎯 Recommendation

Review positive rates across different groups and areas. Use more data before making wider public health decisions.

## 👥 Positive Results by Gender

| Gender | Total Records | Positive Results | Positive Rate |
|---|---:|---:|---:|
| Female | 524 | 281 | 53.6% |
| Male | 476 | 252 | 52.9% |

### 💡 Insight

Female records have a slightly higher positive rate than male records. The difference is small, at about 0.7 percentage points.

### 🎯 Recommendation

Compare both positive counts and positive rates. Counts alone may be misleading when group sizes are different.

## 👶 Positive Results by Age Group

| Age Group | Total Records | Positive Results | Positive Rate |
|---|---:|---:|---:|
| Child (0-17) | 183 | 101 | 55.2% |
| Adult (18-59) | 725 | 386 | 53.2% |
| Senior (60+) | 92 | 46 | 50.0% |

### 💡 Insight

Adults account for the highest number of positive results, with 386 records. However, children have the highest positive rate among the three age groups, at 55.2%.

### 🎯 Recommendation

Consider both the number of positive results and the rate within each age group. More data is needed to understand why the rates differ.

## 🏘️ Positive Results by Area Type

| Area Type | Total Records | Positive Results | Positive Rate |
|---|---:|---:|---:|
| Developed | 501 | 257 | 51.3% |
| Undeveloped | 499 | 276 | 55.3% |

### 💡 Insight

Undeveloped areas have a positive rate of 55.3%, compared with 51.3% in developed areas. This is a difference of about 4 percentage points.

### 🎯 Recommendation

Review local conditions and collect more data before deciding where further checks or public health work may be needed.

**Chart note:** The original area type chart shows each area's share of all positive results, not the positive rate within each area type. The rates in this table are calculated using the total records in each group.

## 📍 Top 5 Areas by Positive Results

| Area | Total Records | Positive Results | Positive Rate |
|---|---:|---:|---:|
| Jatrabari | 38 | 31 | 81.6% |
| Demra | 38 | 26 | 68.4% |
| Bangshal | 34 | 24 | 70.6% |
| Tejgaon | 31 | 24 | 77.4% |
| Mohammadpur | 28 | 20 | 71.4% |

### 💡 Insight

Jatrabari has the highest number of positive results among these areas, with 31 positive results out of 38 records.

Tejgaon also has a high positive rate of 77.4%.

### 🎯 Recommendation

These areas may need closer review within this dataset. The record counts are limited, so more data is needed before drawing wider conclusions about local dengue risk.

## 🏠 Results by House Type

| House Type | Total Records | Positive Results | Positive Rate |
|---|---:|---:|---:|
| Tinshed | 317 | 173 | 54.6% |
| Building | 354 | 191 | 53.9% |
| Other | 329 | 169 | 51.4% |

### 💡 Insight

Positive rates are fairly close across the three house types. Tinshed records have the highest rate, at 54.6%.

### 🎯 Recommendation

Do not use house type alone to judge dengue risk. More information about local conditions and the people in the dataset is needed.

## 🧪 Test Result Analysis

The dataset includes three test fields: NS1, IgG, and IgM. Each field is coded as 0 or 1.

| Test Field | Records Coded 1 |
|---|---:|
| NS1 | 519 |
| IgG | 533 |
| IgM | 475 |

### 💡 Insight

The IgG field has 533 records coded as 1, which matches the number of positive Outcome records.

This match may be related to how the dataset was created or labeled. It should be checked before drawing medical conclusions from these fields.

### 🎯 Recommendation

Confirm the meaning of each test field and the rules used to set the final Outcome value with the data provider.

## 📈 Dashboard Charts and Filters

The workbook includes dashboard views for:

- 👥 Positive results by gender
- 👶 Positive results by age group
- 🏘️ Results by area type
- 📍 Top five areas by positive result count
- 📊 Overall KPIs and gender-level figures

The dataset also contains age, house type, local area, and test result fields for further analysis.

## 🧹 Data Quality Checks

- The dataset contains 1,000 records and 11 columns.
- No blank cells were found in the 11 data fields.
- All records belong to Dhaka, so district-level comparisons are not possible.
- The dataset has no date field, so monthly or yearly trends cannot be calculated.
- The original `Avg Age (Affected)` KPI shows 35.924, which matches the average age across all records. The average age among positive records is about 35.7 years.
- The original area type chart shows the share of all positive results by area type, not the positive rate within each group.
- A positive result in this dataset should not be treated as a medical diagnosis without knowing the test rules and data source.

## 🎯 Final Findings and Recommendations

### 1. 🦟 Overall Positive Results
There are 533 positive results among 1,000 records, giving a positive rate of 53.3%.

**Action:** Review the data source and test rules before using this figure for wider public health decisions.

### 2. 👥 Gender Comparison
Positive rates are similar for female and male records.

**Action:** Compare rates as well as counts when reviewing differences between groups.

### 3. 👶 Age Group Review
Adults have the highest number of positive results, while children have the highest positive rate.

**Action:** Review both age groups and rates when planning further analysis.

### 4. 🏘️ Area Type Review
Undeveloped areas have a higher positive rate than developed areas in this dataset.

**Action:** Collect more data to check whether this pattern remains across a wider group of records.

### 5. 📍 Local Area Review
Jatrabari has the highest count of positive results among the listed areas.

**Action:** Review the sample size and gather more local data before drawing wider conclusions.

### 6. 🧹 Improve Data Reporting
The original KPI and area type chart use labels that may be unclear.

**Action:** Define each KPI clearly and use the correct group total when calculating positive rates.

## 🛠️ Tools Used

- Microsoft Excel
- Pivot Tables
- Charts and Dashboard Views
- Data Cleaning and Summary Analysis

## ⚠️ Limitations

This dashboard describes the records in the provided dataset only. It does not prove that one group, house type, or area has a higher dengue risk in the wider population.

The dataset has no date field, so it cannot show changes over time. More records and verified test information are needed for broader conclusions.

