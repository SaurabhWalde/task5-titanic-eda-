# Exploratory Data Analysis (EDA) - Titanic Dataset

## Objective:
To extract meaningful insights using statistical and visual exploration tools.

## Tools Used:
- Python Libraries: Pandas, NumPy, Matplotlib, Seaborn
- Jupyter Notebook

## Deliverables:
- Jupyter Notebook (`eda_titanic.ipynb`)
- PDF Report (`eda_report.pdf`)
- Dataset (`Titanic.csv`)

## Folder Structure:
```
task5-titanic-eda/
├── eda_titanic.ipynb      # Jupyter Notebook with the analysis
├── eda_report.pdf         # PDF report summarizing findings
├── Titanic.csv            # Dataset used for the EDA
└── README.md              # Project overview and findings
```

## Key Steps:
### 1. Data Loading and Initial Checks:
- Checked dataset structure (`.info()`).
- Generated basic statistics (`.describe()`).
- Explored categorical values (`.value_counts()`).

### 2. Visualizations:
- **Univariate Analysis**:
  - Histograms for age and fare distributions.
  - Boxplots to examine fare spread.
- **Bivariate Analysis**:
  - Scatter plots (Age vs. Fare, survival coloring).
  - Bar plots (Survival rate by gender).
- **Multivariate Analysis**:
  - Pair plots to identify relationships between numerical features.
  - Heatmap to assess feature correlations.

### 3. Observations:
- Younger passengers showed slightly higher survival rates.
- Higher fares and lower Pclass correlated with better survival chances.
- No missing values, and the dataset is well-structured.

## Summary Findings:
The Titanic dataset reveals interesting patterns:
- **Survival Insights**: Passengers paying higher fares had better survival rates.
- **Feature Correlations**: Survival depends more on fare and class than age.
- Gender distribution in survival is balanced.

## How to Use:
Clone this repository and explore the Jupyter Notebook for step-by-step analysis. The PDF contains all major insights and findings.

## Author:
[Saurabh](https://github.com/Saurabh)