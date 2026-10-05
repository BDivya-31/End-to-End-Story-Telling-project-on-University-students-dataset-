# End-to-End-Story-Telling-project-on-University-students-dataset-
# 🎓 University Students Performance - Exploratory Data Analysis & Storytelling

An end-to-end data analysis and storytelling project analyzing university student performance across academic subjects (`math score`, `reading score`, and `writing score`). This project explores demographic factors, test preparation, lunch status, and parental education levels to derive actionable educational insights.

---

## 📌 Executive Summary & Key Findings

### 1. Gender Differences in Academic Performance
- **Math Domain:** Male students, on average, outperform female students in mathematics.
- **Verbal & Writing Domains:** Female students show significantly higher average performance in reading and writing tasks compared to male students.

### 2. Impact of Test Preparation Course
- Completing a test preparation course yields a **consistent positive uplift across all three subjects**.
- The highest incremental gain from test preparation is observed in **writing scores**, followed by reading and math scores.

### 3. High Inter-Subject Correlation
- Strong positive correlation exists among all three exam scores.
- **Reading and Writing scores share the strongest correlation** ($r > 0.90$), indicating that literacy skills are tightly coupled. Math scores also positively correlate with both verbal domains, though at a slightly lower magnitude.

### 4. Influence of Parental Education Level
- A clear positive trend exists between higher parental educational attainment (e.g., Bachelor’s or Master’s degrees) and higher overall student test scores.
- Students whose parents hold advanced degrees demonstrate higher baseline performance and less variance in test scores.

### 5. Outliers & Socioeconomic Factors
- **Socioeconomic Impact:** Students receiving standard lunch consistently score higher than those on free/reduced lunch, pointing to economic security as a key performance indicator.
- **Outliers:** Low-end score outliers were detected primarily in math scores, representing a targeted cohort of students requiring early academic intervention.

---

## 🛠️ Project Structure

```text
├── data/
│   └── StudentsPerformance.csv     # Raw dataset
├── notebooks/
│   └── student_performance_eda.ipynb # Complete EDA workflow
├── reports/
│   └── figures/                    # Saved EDA visualizations
├── requirements.txt                # Python dependencies
└── README.md                       # Project documentation
