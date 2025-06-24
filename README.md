## Task 2: Exploratory Data Analysis (EDA)

### Objective

To perform detailed Exploratory Data Analysis on the 2026 QS World University Rankings dataset and derive meaningful insights using statistical and visual methods.

---

### Dataset

**Name**: QS World University Rankings 2026  
**Source**: [Kaggle - QS Rankings Dataset](https://www.kaggle.com/datasets/akashbommidi/2026-qs-world-university-rankings)  
**File Used**: `2026 QS World University Rankings.csv`

---

### Tools & Libraries

- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Seaborn & Matplotlib** – data visualization
- **Plotly** – interactive visualizations
- **Missingo** – interactive visualizations

---

### Steps Performed

1. **Loading & Exploring the Dataset**
   - Checked shape, datatypes, and basic stats
   - Identified missing values

2. **Handling Missing Data**
   - Numerical columns filled using mean
   - Categorical columns filled using mode
   - Verified no missing values remain

3. **Statistical Summary**
   - Generated mean, median, std, and percentiles for key metrics

4. **Univariate Analysis**
   - Histograms for `Overall Score`
   - Violin and box plots for key metrics

5. **Multivariate Analysis**
   - Correlation heatmap
   - Pairplots for relationships between key indicators
   - Grouped barplots comparing `India vs World`

6. **India vs. Global Comparison**
   - Scatter plots showing:
     - Academic vs Employer Reputation
     - Academic Reputation vs Citations per Faculty
   - India was highlighted to assess its global standing

7. **Top Universities Overview**
   - Bar plot of top 10 universities by `Overall Score`

---

### Key Insights

- India's universities generally score lower in research-related metrics like `Citations per Faculty`.
- A strong positive correlation exists between `Academic Reputation` and `Employer Reputation`.
- Global leaders in the QS ranking show very tight clustering in the high score range (94+).
- India lags in top-tier clusters but shows mid-level strength in select institutions.

---

### How to Run

1. Open the Colab notebook: `Task2_EDA.ipynb`
2. Upload the dataset: `2026 QS World University Rankings.csv`
3. Run all cells in sequence to view the analysis and visualizations

---

### Output

- Cleaned dataset with no missing values
- Multiple visualizations comparing global and Indian universities
- Analytical insights extracted using EDA

---

### Submission

Repository submitted via the official internship portal submission link.
