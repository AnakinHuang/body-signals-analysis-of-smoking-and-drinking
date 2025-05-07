
日志： 2023/12/4 12:08 am Yuyang Boyang

### Data Preprocessing
1. add Visualization for Drinkers in Different Sex Categories
2. Check the P value for the T-test, it is 0.0, which means the difference is significant.
3. Error emitted when running the code: `plt.pie(counts, labels=cholesterol_categories, autopct='%1.1f%%')`


日志： 2023/12/3 1:24 am Harry

### Data Preprocessing
1. **Loading the Dataset:** The dataset was loaded into a DataFrame for analysis.
2. **Handling Missing Data:** You checked for and handled missing data in your dataset. If there were any missing values, they were filled with appropriate statistics (median for numerical columns and mode for categorical columns).
3. **Feature Engineering:**
   - **BMI Calculation:** Added a new column for Body Mass Index (BMI) calculated from height and weight.
   - **Age Groups:** Categorized 'age' into different age groups for demographic analysis.
   - **Blood Pressure Categories:** Classified blood pressure readings into categories like normal, elevated, and different hypertension stages.
   - **Cholesterol Ratio:** Calculated the ratio of total cholesterol to HDL cholesterol.
   - **Vision Impairment Flag:** Created a binary flag indicating vision impairment based on eyesight measurements.

### Statistical Analysis
1. **Correlation Analysis:**
   - Analyzed correlations between continuous variables like BMI, blood pressure, and cholesterol levels using Pearson correlation.
   - Visualized the correlation matrix using a heatmap.

2. **Hypothesis Testing:**这里做的感觉有问题需要验证
   - **T-tests:** Performed t-tests to compare means of continuous variables (like blood pressure) between two groups (e.g., smokers vs. non-smokers). Visualized the distributions using boxplots.
   - **Chi-squared Tests:** Conducted chi-squared tests to compare proportions in categorical data (e.g., the proportion of drinkers across different sexes). Visualized the data using count plots.
