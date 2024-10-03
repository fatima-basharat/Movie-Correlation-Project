# Movie Correlation Project

## Description
This project focuses on analyzing correlations between various movie attributes, such as budget, gross earnings, votes, and more, to identify factors that contribute most to a movie's financial success. The data is cleaned, analyzed, and visualized using Python, with a focus on uncovering significant relationships between key variables.

## Analysis Process
The following steps were implemented using Python, Pandas, and Seaborn:

1. **Data Cleaning**
   - Dropped rows with missing values and corrected data types for numerical columns (e.g., `budget` and `gross`).

2. **Exploratory Data Analysis (EDA)**
   - Visualized relationships between key features like `budget` and `gross earnings` using scatter plots.
   - Created a new column for the release year to aid analysis.

3. **Correlation Analysis**
   - Calculated the correlation matrix to examine relationships between numerical features.
   - Used heatmaps to visualize correlations between movie features, focusing on identifying strong positive or negative correlations.
   - Converted categorical columns (e.g., `company`) into numerical values to include them in the correlation analysis.

## Key Findings
The analysis revealed important correlations between:
- **Budget and Gross Earnings**: A strong positive correlation, suggesting higher-budget films tend to generate higher gross revenue.
- **Votes and Gross Earnings**: Votes also had a significant positive correlation with gross earnings.
- **Company**: Contrary to the initial hypothesis, company correlation with gross earnings was low.

## Sample Output
The analysis focused on key relationships between movie features. Here is a sample of the insights:

| Movie Feature | Correlation with Gross Earnings |
| ------------- | ------------------------------- |
| Budget        | 0.73                            |
| Votes         | 0.64                            |
| Company       | 0.02                            |

## Libraries Used
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations.
- **Seaborn**: For generating plots and visualizations (scatter plots and heatmaps).
- **Matplotlib**: For creating visual representations of data.
