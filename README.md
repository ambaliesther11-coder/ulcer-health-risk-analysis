# ulcer-health-risk-analysis

## 📊 Overview

The **Ulcer Health Risk Analysis Dashboard** is a healthcare data analytics project developed using Power BI to analyse patient data and identify patterns related to ulcer health.

The dashboard provides an interactive view of important patient characteristics, ulcer history, ulcer depth, medication patterns, pain patterns, BMI and haemoglobin levels.

The project demonstrates how healthcare data can be transformed into meaningful visual insights that are easier to understand and explore.

> **Note:** This dashboard is an analytics and portfolio project. It is not intended for clinical diagnosis or treatment decisions.

---

## 🎯 Business Problem

Healthcare datasets can contain a large amount of patient information, but raw data can be difficult to interpret and analyse efficiently.

For ulcer-related patient data, it is important to understand questions such as:

- How many patients are represented in the dataset?
- What is the average BMI of the patients?
- What is the average haemoglobin level?
- Which ulcer depth is most common?
- What is the distribution of ulcer history?
- What medications are most commonly recorded?
- What pain patterns are observed?
- How are patients distributed across different age groups?

This project addresses these challenges by transforming patient data into an interactive Power BI dashboard that makes important patterns easier to identify.

---

## 🎯 Objectives

The objectives of this project were to:

1. Analyse patient-level ulcer health data.
2. Determine the total number of patients represented in the dataset.
3. Analyse average BMI and haemoglobin levels.
4. Examine the distribution of ulcer depth levels.
5. Analyse patients based on ulcer history.
6. Examine patient distribution across age groups.
7. Analyse medication patterns.
8. Explore different patient pain patterns.
9. Create meaningful healthcare KPIs.
10. Develop an interactive dashboard for healthcare data storytelling.
11. Present complex healthcare information in a simple and understandable format.

---

## 📁 Dataset Information

The dataset contains information relating to **170 patients**.

### Key variables include:

- Patient ID
- Age
- Age Group
- BMI
- Haemoglobin Level
- Ulcer History
- Ulcer Depth
- Ulcer Size
- Pain Severity
- Pain Pattern
- Medication
- Diagnosis Date
- Ulcer Stage

The dataset was used to explore relationships and distributions across different patient and ulcer-related characteristics.

---

## 🛠️ Tools and Technologies Used

### Power BI
Used to create the interactive dashboard, visualizations and KPI cards.

### Power Query
Used for data cleaning, transformation and preparation.

### DAX
Used to create calculated measures and analytical KPIs.

### Data Visualization
Used to communicate healthcare patterns through charts, cards, slicers and other visual elements.

### GitHub
Used to document and showcase the project as part of my data analytics portfolio.

---

# 🧹 Data Cleaning & Preparation

Before developing the dashboard, the dataset was prepared for analysis.

The data preparation process included:

- Reviewing the dataset structure.
- Checking variable types.
- Preparing numerical variables for analysis.
- Organizing categorical variables.
- Preparing age groups.
- Preparing ulcer history categories.
- Preparing ulcer depth categories.
- Preparing medication categories.
- Preparing pain pattern categories.
- Preparing diagnosis date information.
- Creating calculated measures required for the dashboard.
- Ensuring the data was suitable for visualization in Power BI.

The goal of the preparation stage was to ensure that the data could be analysed consistently and represented accurately in the dashboard.

---

# 📌 Key Performance Indicators (KPIs)

The dashboard contains the following major KPIs:

| KPI | Value |
|---|---:|
| Total Patients | **170** |
| Average BMI | **27.45** |
| Average Haemoglobin Level | **11.59** |

The dashboard also provides comparative indicators for:

- Average Age
- Average Ulcer Size
- Average Pain Severity

These KPIs provide a quick summary of the patient population before exploring the detailed visualizations.

---

# 📊 Dashboard Features

## 1. Total Patients

The dashboard shows a total of:

**170 patients**

This provides an overview of the size of the patient population analysed.

---

## 2. Average BMI

The average BMI of the patients is:

**27.45**

The dashboard also provides a trend visualization for BMI.

---

## 3. Average Haemoglobin Level

The average haemoglobin level is:

**11.59 g/dL**

A trend visualization is also provided to help explore changes across diagnosis years.

---

## 4. Ulcer History Distribution

The dashboard uses a donut chart to show the distribution of ulcer history.

The categories include:

- Previous
- None
- Recurrent

The distribution shown in the dashboard is:

- **Previous – 25.29%**
- **None – 33.53%**
- **Recurrent – 41.18%**

---

## 5. Patient Age Distribution

The dashboard shows patient distribution across different age groups.

This makes it possible to observe how the patient population is distributed across different stages of adulthood.

---

## 6. Prevalence of Ulcer Depth Levels

The dashboard examines three major ulcer depth categories:

- Erosion
- Superficial
- Deep

The visualization shows that **erosion** has the highest distribution among the displayed ulcer depth categories.

---

## 7. Patient Distribution Across Medications

The medication visualization shows the distribution of patients across different medication categories.

The dashboard includes:

- NSAIDs
- None
- Aspirin

This allows medication patterns within the dataset to be explored visually.

---

## 8. Distribution of Patient Pain Patterns

The dashboard analyses different pain patterns reported by patients.

The categories include:

- Postprandial
- Fasting
- Nocturnal
- Mixed

The dashboard shows **postprandial pain** as the most prominent pain pattern among the displayed categories.

---

## 9. Ulcer Stage Navigation

The dashboard contains image-based navigation for different ulcer stages.

This makes the dashboard more interactive and allows users to explore the analysis through the different stages.

---

## 10. Ulcer Image Visualization

An ulcer-related anatomical image is included in the dashboard to provide visual context for the analysis.

---

# 🔎 Key Insights

Based on the dashboard analysis, several observations were identified.

### 1. Patient Population

The dataset contains **170 patients**, providing the population used for the dashboard analysis.

### 2. BMI

The average BMI is **27.45**.

This provides a useful summary of the general BMI profile of the patients included in the dataset.

### 3. Haemoglobin

The average haemoglobin level is **11.59 g/dL**.

### 4. Ulcer History

The largest ulcer-history category displayed is **recurrent ulcers at 41.18%**.

This is followed by:

- None – 33.53%
- Previous – 25.29%

### 5. Ulcer Depth

**Erosion** represents the largest displayed ulcer-depth category, followed by superficial and deep ulcers.

### 6. Medication

The medication visualization shows that **NSAIDs** represent the largest visible medication category, followed by patients with no medication recorded and aspirin.

### 7. Pain Pattern

**Postprandial pain** is the most prominent pain pattern displayed on the dashboard.

Other observed patterns include:

- Fasting
- Nocturnal
- Mixed

### 8. Age

The dashboard shows that patients are distributed across several age groups, allowing age-related patterns to be explored.

---

# 💡 Recommendations

Based on the patterns observed in the dashboard:

1. **Further investigate recurrent ulcer cases**, since recurrent ulcers represent the largest ulcer-history category.

2. **Explore medication patterns alongside ulcer history** to understand whether particular medication categories appear more frequently among specific patient groups.

3. **Analyse pain patterns together with ulcer characteristics** to identify possible relationships between pain presentation and ulcer depth or history.

4. **Examine BMI and haemoglobin alongside other patient variables** rather than considering these indicators individually.

5. **Expand the dataset in future analysis** by including additional clinical and demographic variables where available.

6. **Develop additional dashboard pages** for deeper analysis of medication, ulcer depth, age and pain relationships.

7. **Use the dashboard as an analytical support tool**, while ensuring that clinical decisions are based on appropriate medical assessment and evidence.

---

# 🏁 Conclusion

The **Ulcer Health Risk Analysis Dashboard** demonstrates how healthcare data can be transformed into meaningful and interactive visual insights.

Using data from **170 patients**, the project explored important indicators including:

- BMI
- Haemoglobin level
- Ulcer history
- Ulcer depth
- Medication
- Age distribution
- Pain patterns
- Pain severity
- Ulcer size

The project helped strengthen my practical skills in:

**Data Cleaning → Data Transformation → Data Analysis → KPI Development → Data Visualization → Dashboard Design → Healthcare Data Storytelling**

This project also represents part of my journey of combining my **background in Pharmacology with my growing skills in Data Analytics**.

---

# 👩‍💻 Author

### Esther Ambali

**Pharmacology Graduate | Aspiring Data Analyst | Healthcare Data Analytics**

I am interested in using data analytics to solve problems and communicate insights, particularly at the intersection of **healthcare, pharmacology and data**.

    └── project-notes.md
