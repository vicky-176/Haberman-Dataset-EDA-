# EDA on Haberman’s Survival Dataset  

This project focuses on performing Exploratory Data Analysis (EDA) on the Haberman’s Survival dataset, which contains information on breast cancer patients who underwent surgery. The aim is to understand survival patterns and analyze how different features influence survival outcomes.  

# Project Files  
- `eda_on_haberman.ipynb` – Jupyter notebook with the complete EDA  
- `README.md` – Project documentation  

# Dataset Information  
**Source:** UCI Machine Learning Repository  

**Features:**  
- **Age:** Age of patient at the time of surgery  
- **Year:** Year of surgery (year - 1900)  
- **Nodes:** Number of positive axillary lymph nodes detected  
- **Survival_Status:**  
  - 1 → survived 5 years or longer  
  - 2 → died within 5 years  

# Objectives of EDA  
- Analyze the distribution of features (age, year, nodes)  
- Examine skewness and kurtosis to check data normality  
- Visualize survival trends and patterns  
- Detect correlations and potential outliers  
- Study relationships between features and survival status  

# Key Analyses Performed  
- Univariate Analysis (Histograms, Boxplots)  
- Bivariate Analysis (Pairplots, Violin plots)  
- Multivariate Analysis  
- Skewness and Kurtosis interpretation  
- Heatmap of correlation matrix  
- Class balance and survival trend analysis  

# Technologies Used  
- Python (Jupyter Notebook)  
- Pandas, NumPy – data manipulation  
- Matplotlib, Seaborn – visualization  
- SciPy – statistical computations  

# Summary of Findings  
- Age and year of operation show near-symmetric distributions (low skew).  
- Number of nodes is right-skewed with outliers.  
- Survivors generally have fewer positive nodes.  
- The dataset is imbalanced (more survivors than non-survivors).  
- Features are mostly independent, with no strong correlations.  
git clone https://github.com/adarshunknown/EDA-on-Haberman-Dataset.git
cd haberman-eda
