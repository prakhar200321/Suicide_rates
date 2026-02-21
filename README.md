
# Mental Health and Suicide Rates Analysis

## Project Overview

This project performs an Exploratory Data Analysis (EDA) on global mental health infrastructure and suicide rate datasets. The objective is to understand patterns, distributions, correlations, and potential relationships between mental health facilities and suicide rates across countries, genders, age groups, and years.

The analysis focuses on:

* Age‑standardized suicide rates
* Crude suicide rates by age group
* Mental health facility availability
* Correlation between infrastructure and suicide statistics

---

## How to Run This Project (Simple Steps)

Follow these steps even if you are new to Python:

### Step 1 — Install Python

1. Go to [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. Download Python (version 3.9 or newer)
3. While installing, **tick the box: Add Python to PATH**

### Step 2 — Download the Project

* Download the project folder from GitHub/Kaggle
* Keep all CSV files in the same folder as the notebook/script

### Step 3 — Install Required Libraries

Open **Command Prompt / Terminal** inside the project folder and run:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Step 4 — Run the Code

#### Option A: Jupyter Notebook (Recommended)

```bash
jupyter notebook
```

* A browser will open
* Click the `.ipynb` file
* Press **Run → Run All Cells**

#### Option B: Python Script

If you have a `.py` file:

```bash
python analysis.py
```

### Step 5 — Important Folder Rule

All CSV files must be in the **same folder** as the code, otherwise you will get *file not found error*.

---

## Datasets Used

The project uses four CSV datasets:

1. **Age-standardized suicide rates.csv**
   Contains suicide rates per country by sex across multiple years (2000, 2010, 2015, 2016).

2. **Crude suicide rates.csv**
   Contains suicide rates categorized by age groups (10–19 to 80+) and sex.

3. **Facilities.csv**
   Contains availability of mental health services per country including:

   * Mental hospitals
   * Health units
   * Outpatient facilities
   * Day treatment centers
   * Residential facilities


---

## Technologies & Libraries

* Python 3
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit‑learn (StandardScaler)

---

## Project Structure

```
Mental-Health-Suicide-Analysis/
│── Age-standardized suicide rates.csv
│── Crude suicide rates.csv
│── Facilities.csv
│── analysis.ipynb (or .py)
│── README.md
```

---

## Setup Instructions

1. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

2. Place datasets inside project directory or Kaggle `/input` folder.

3. Run the notebook or Python script:

```bash
python analysis.py
```

OR open the notebook in Jupyter/Kaggle.

---

## Analysis Workflow

### 1. Data Loading

* Read CSV files using `pandas.read_csv()`
* Preview data using `.head()` and `.shape`

### 2. Data Visualization Functions

Custom plotting functions include:

* `plotPerColumnDistribution()` → Histograms & bar charts
* `plotCorrelationMatrix()` → Correlation heatmaps
* `plotScatterMatrix()` → Scatter & density plots

### 3. Exploratory Data Analysis

Performed analysis:

* Distribution plots of suicide rates
* Gender comparison
* Age‑group risk comparison
* Correlation between variables

### 4. Data Cleaning

* Dropping constant columns
* Handling missing values
* Outlier treatment using median replacement

### 5. Facility Infrastructure Analysis

* Boxplots to detect outliers
* Histogram distribution of hospitals
* Heatmap correlations between facility types
* Scatter plots for relationships

---

## Key Observations (Example Insights)

* Male suicide rates are significantly higher than female rates in most countries.
* Elderly age groups (70+) tend to show higher crude suicide rates.
* Some positive correlation exists between types of mental health facilities.
* Infrastructure availability varies drastically between countries.

---

## Future Improvements

* Apply machine learning models for prediction
* Time‑series trend analysis
* Country clustering based on risk factors
* Combine economic indicators (GDP, unemployment)

---

## Disclaimer

This project is intended for educational and research purposes only. The data represents reported statistics and may not capture real‑world underreporting or sociocultural factors influencing mental health.

---

## Author

Data Analysis Project – Mental Health & Suicide Rates Study
