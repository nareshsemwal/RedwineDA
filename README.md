Wine Quality Analysis & EDA
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Wine Quality dataset to uncover insights, patterns, and relationships that influence wine quality. The analysis includes data cleaning, visualization, statistical exploration, and correlation analysis.

The goal is to identify the key factors that impact wine quality ratings and present them with meaningful visualizations.

📂 Dataset

Source: UCI Machine Learning Repository (Wine Quality Dataset)

Data: Contains physicochemical properties of red and white wine samples.

Target Variable: quality (scores from 0–10 given by wine tasters).

🛠️ Technologies Used

Python

Jupyter Notebook

Libraries:

pandas → data manipulation

numpy → numerical computation

matplotlib & seaborn → data visualization

scipy & statsmodels (if used) → statistical analysis

🔍 Analysis Performed

Data Cleaning & Preprocessing

Handling missing values

Checking duplicates and data types

Exploratory Data Analysis (EDA)

Distribution of wine quality

Univariate & bivariate analysis

Correlation heatmaps

Insights & Key Findings

Factors that strongly affect wine quality

Relationships between acidity, alcohol, residual sugar, etc.

📊 Visualizations

Histograms and boxplots for feature distributions

Pairplots for multivariate relationships

Heatmaps for correlation analysis

Quality distribution plots

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>


Install dependencies:

pip install -r requirements.txt


Open the Jupyter Notebook:

jupyter notebook "1.0-WinequalityEDA.ipynb"

Results & Insights

Wines with higher alcohol content tend to receive higher quality ratings.

Volatile acidity negatively impacts wine quality.

Certain chemical properties show stronger correlations with quality than others.

📜 License

This project is licensed under the MIT License – feel free to use and modify for your own work.
