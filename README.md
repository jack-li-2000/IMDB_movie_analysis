🎬 IMDB Movie Analysis – Correlation Study

Summary

This project explores relationships between various movie attributes (e.g., budget, revenue, ratings, runtime) using an IMDB dataset. The goal is to identify which factors most strongly correlate with a movie’s financial and critical success. The analysis was conducted in Python using Jupyter Notebook, with a focus on data cleaning, exploratory data analysis (EDA), and correlation visualization.

<img width="897" height="226" alt="image" src="https://github.com/user-attachments/assets/5c12c46f-8d91-43f1-ab93-0b58e4db6ad9" />

Hypothesis

* Higher budgets are positively correlated with higher box office revenue.
* Higher IMDB ratings are associated with higher revenue and stronger audience reception.
* Longer runtimes may have a weak or negative correlation with revenue due to audience fatigue.

Methods

Data Source - IMDB dataset (CSV format) containing movie metadata, financials, and ratings.

Tools & Libraries:
pandas: for data cleaning and manipulation
numpy: for numerical operations
matplotlib & seaborn: for data visualization
scipy: for statistical correlation tests

Process

1. Data Cleaning – Removed null values, standardized column names, converted data types.
2. Feature Selection – Focused on budget, revenue, IMDB rating, runtime, and genre.
3. Exploratory Data Analysis – Generated descriptive statistics and visualized distributions.
4. Correlation Analysis – Used Pearson and Spearman correlation coefficients to measure relationships between variables.
5. Visualization – Created heatmaps, scatter plots, and regression lines to illustrate findings.

Conclusion

* Budget vs. Revenue: Strong positive correlation — higher budgets generally lead to higher box office returns.
* IMDB Rating vs. Revenue: Moderate positive correlation — critically acclaimed films tend to perform better financially, but outliers exist.
* Runtime vs. Revenue: Weak correlation — runtime alone is not a strong predictor of financial success.
* Genre Influence: Certain genres (e.g., action, adventure) tend to have higher budgets and revenues, while others (e.g., drama, indie) may achieve high ratings with lower budgets.

How to Run the Project

Clone the repository:

git clone https://github.com/jack-li-2000/IMDB_movie_analysis.git
cd IMDB_movie_analysis

Install dependencies:

pip install -r requirements.txt

Open the Jupyter Notebook:

jupyter notebook movies_correlation.ipynb

Future Improvements

* Incorporate inflation-adjusted revenue for historical accuracy.
* Add more advanced regression models to predict revenue.
* Explore interaction effects between multiple variables (e.g., budget × genre).
