# Pandas EDA Notebook — Day 7 📓

A Jupyter Notebook demonstrating exploratory data analysis (EDA) on a student dataset using **Pandas**. Covers comprehensive DataFrame inspection, data quality checks, and categorical analysis.

## Topics Covered

- Loading CSV into DataFrame
- Inspecting first/last rows, random samples
- Shape, columns, index, data types
- Full `info()` and `describe()` (numeric & all columns)
- Missing value detection per column
- Categorical feature summaries (Course, City distributions)
- Key observations and findings documented

## Dataset

- **File**: `Day7_Student_Dataset.csv`
- **Rows**: 25 students
- **Columns**: Student_ID, Name, Age, Course, City, Marks, Grade
- **Courses**: B.Tech, B.Sc, B.Com, B.A, BBA
- **Cities**: Multiple Indian cities
- **Grades**: A, B, C, D, F

## Tech Stack

- **Language**: Python 3.x
- **Environment**: Jupyter Notebook / Google Colab
- **Libraries**: `pandas`, `numpy`

## Installation

```bash
git clone https://github.com/sarathirajanhere/idra_7.git
cd idra_7
```

## Usage

### Option 1: Jupyter Notebook (Local)
```bash
pip install jupyter pandas numpy
jupyter notebook Day7_Dataset_Summary_Report.ipynb
```

### Option 2: Google Colab (Recommended)
1. Open [colab.research.google.com](https://colab.research.google.com)
2. Upload both files:
   - `Day7_Dataset_Summary_Report.ipynb`
   - `Day7_Student_Dataset.csv`
3. Run all cells

## File Structure

```
idra_7/
├── Day7_Dataset_Summary_Report.ipynb    # Main notebook
├── Day7_Student_Dataset.csv             # Sample dataset
└── README.md                            # This file
```

## Key Learning Outcomes

- DataFrame inspection methods (`head`, `tail`, `sample`, `info`, `describe`)
- Data quality assessment (missing values, dtypes)
- Categorical analysis with `value_counts()`
- Generating actionable insights from raw data

## Sample Findings

- Course distribution across students
- City-wise student counts
- Marks statistics (mean, median, std, min, max)
- Grade distribution analysis

---

*Part of the IDRA learning series — progressive data science curriculum (Day 7 of 11).*