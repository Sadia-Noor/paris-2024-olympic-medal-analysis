# Paris 2024: Olympic Medal Insights and Prediction

This repository contains a comprehensive analysis and predictive modeling of Olympic medals awarded during the Paris 2024 Olympics. The project explores medal distribution across countries, compares top-performing nations, and uses a linear regression model to predict total medal counts based on gold, silver, and bronze medals.

## Project Overview

### 1. Load the Dataset and Initial Exploration
- **Install Required Libraries:** Loaded essential Python libraries such as Pandas, Matplotlib, and Seaborn.
- **Load the Dataset:** Imported the dataset containing 91 records and 7 features.
- **Summary Statistics:** Provided insights into the distribution of medals (Gold, Silver, Bronze) and ranks.
- **Dataset Information:** Verified that the dataset is complete with no missing values and correct data types.
- **Visualize Medal Distribution:** Created histograms and density plots to analyze the distribution of gold, silver, and bronze medals among countries.

### 2. Define the Project Scope
- **Medal Distribution Analysis:** Analyzed the distribution of Olympic medals across participating countries.
- **Country Comparison:** Compared the performance of countries based on their total medal counts.
- **Predictive Modeling with Linear Regression:** Developed a linear regression model to predict total medal counts.
- **Interactive Medal Analysis:** Created an interactive tool for exploring medal distribution by country.

### 3. Data Preparation
- **Check for Duplicates:** Verified and removed any duplicate entries in the dataset.
- **Validation of Total Medals Column:** Ensured that the total medals column accurately reflects the sum of gold, silver, and bronze medals.

### 4. Exploratory Data Analysis (EDA) & Country Comparison
- **Medal Count by Country:** Visualized the total number of medals won by each country, focusing on the top 20 countries.
- **Comparison of Medal Types:** Created stacked bar plots to compare gold, silver, and bronze medals among top-performing countries.
- **Medal Composition per Country:** Used donut charts to visualize the medal composition of the top 5 countries.
- **Correlation Analysis:** Produced a heatmap to visualize the correlation between different medal types.
- **Country-wise Medal Dominance:** Identified the dominant medal type for each country.

### 5. Predictive Modeling with Linear Regression
- **Feature Selection:** Selected gold, silver, and bronze medals as features to predict total medals.
- **Model Training:** Trained a linear regression model to predict total medals.
- **Model Evaluation:** Evaluated the model using RMSE and R-squared metrics, confirming a perfect fit due to the linear nature of the relationship.
- **Visualizing Performance:** Visualized the actual vs. predicted values to assess model performance.

## Technologies Used
- **Python:** Core programming language for analysis and modeling.
- **Pandas:** For data manipulation and processing.
- **Matplotlib & Seaborn:** For creating visualizations and plots.
- **Scikit-learn:** For implementing the linear regression model.

## How to Use
1. Clone the repository.
2. Install the required libraries: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`.
3. Run the provided Jupyter notebook to explore the analysis and predictive modeling.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
This project was inspired by the analysis of Olympic data and the exploration of predictive modeling techniques using Python.
