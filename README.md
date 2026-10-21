# 🏥 Healthcare Patient Analytics

A data analytics project focused on cleaning messy healthcare patient data, performing Exploratory Data Analysis (EDA), and visualizing meaningful patterns to support data-driven insights.

## 📌 Project Overview

Healthcare datasets often contain missing values, duplicate records, inconsistent formats, and invalid entries. These issues can affect the accuracy of analysis and decision-making.

This project focuses on transforming raw, messy patient data into a structured and analysis-ready dataset using Python data analysis libraries.

The project follows a complete data analytics workflow, from data cleaning and validation to exploratory analysis and visualization.

## 🎯 Objectives

- Clean and preprocess messy healthcare patient data.
- Identify and handle missing values and duplicate records.
- Standardize inconsistent data formats and categorical values.
- Detect invalid values and potential data quality issues.
- Perform Exploratory Data Analysis (EDA).
- Create visualizations to identify patterns and trends.
- Extract meaningful insights from the available patient data.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Jupyter Notebook | Interactive analysis and experimentation |
| Git & GitHub | Version control and project hosting |

## 📂 Project Structure

```text
Healthcare-Patient-Analytics/
│
├── data/
│   └── messy.csv
│
├── notebook/
│   ├── cleaning.ipynb
│   ├── analysis.ipynb
│   └── visualise.ipynb
│
├── README.md
└── requirements.txt
```

## 🔍 Project Workflow

### 1. Data Cleaning and Preprocessing

The raw dataset is inspected and cleaned to improve data quality.

Key tasks include:
- Inspecting dataset dimensions, column names, and data types.
- Identifying and handling missing values.
- Detecting duplicate records.
- Standardizing inconsistent text and numerical formats.
- Cleaning invalid or inconsistent age values.
- Validating data types and checking data consistency.

### 2. Exploratory Data Analysis (EDA)

EDA is used to understand the dataset and identify patterns before drawing conclusions.

Key activities include:
- Analyzing numerical and categorical variables.
- Examining distributions and summary statistics.
- Identifying unusual values and potential outliers.
- Exploring relationships between available variables.
- Investigating patient-related patterns based on the dataset's actual columns.

### 3. Data Visualization

Matplotlib is used to communicate findings through appropriate charts.

Depending on the available data, visualizations may include:
- Histograms for numerical distributions.
- Bar charts for categorical comparisons.
- Box plots for examining spread and potential outliers.
- Scatter plots for exploring relationships between numerical variables.
- Other suitable charts based on the analysis objectives.

### 4. Insights and Findings

The analysis aims to identify meaningful patterns, data quality issues, and relationships within the available healthcare data.

Findings should be interpreted in the context of the dataset and should not be treated as clinical conclusions or medical recommendations.

## 📊 Key Skills Demonstrated

- Data wrangling and preprocessing
- Missing-value handling
- Duplicate detection
- Data validation and standardization
- Exploratory Data Analysis
- Statistical summaries
- Data visualization
- Jupyter Notebook workflows
- Git and GitHub version control

## ⚙️ Installation and Setup

### Prerequisites

- Python 3.10 or a compatible Python version
- pip
- Jupyter Notebook

### Step 1: Clone the repository

```bash
git clone https://github.com/hey-rakesh/Healthcare-Patient-Analytics.git
```

### Step 2: Navigate to the project directory

```bash
cd Healthcare-Patient-Analytics
```

### Step 3: Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```powershell
.\venv\Scripts\Activate.ps1
```

### Step 4: Install dependencies

```bash
pip install pandas numpy matplotlib jupyter
```

If a `requirements.txt` file is available, you can instead run:

```bash
pip install -r requirements.txt
```

### Step 5: Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebooks in the `notebook/` directory and execute the cells in the appropriate order.

## 🚀 Future Improvements

- Add a before-and-after data quality report.
- Include automated data validation checks.
- Add more insightful visualizations based on the dataset.
- Create an interactive healthcare analytics dashboard.
- Add reproducible analysis instructions and documented findings.

## 👨‍💻 Author

**Rakesh**

AI & Machine Learning Engineering Student

- GitHub: [@hey-rakesh](https://github.com/hey-rakesh)

## 📄 Disclaimer

This project is intended for educational and data analytics practice. Any insights depend on the quality, completeness, and characteristics of the dataset. The analysis is not intended to replace professional medical judgment.

---

⭐ If you find this project useful, consider starring the repository.
