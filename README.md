Housing Prices Analysis in Boston
Project Overview
This project involves analysing housing prices in Boston, Massachusetts, using a dataset derived from the U.S. Census Bureau. The goal is to generate insights and answer specific business questions for the housing agency's upper management. The analysis covers statistical summaries, visualisations, and hypothesis testing to assist in informed decision-making.

Dataset Description
The dataset consists of the following variables:
- CRIM: Per capita crime rate by town.
- ZN: Proportion of residential land zoned for lots over 25,000 sq.ft.
- INDUS: Proportion of non-retail business acres per town.
- CHAS: Charles River dummy variable (1 if tract bounds the river; 0 otherwise).
- NOX: Nitric oxide concentrations (parts per 10 million).
- RM: Average number of rooms per dwelling.
- AGE: Proportion of owner-occupied units built before 1940.
- DIS: Weighted distances to five Boston employment centres.
- RAD: Index of accessibility to radial highways.
- TAX: Full-value property tax rate per $10,000.
- PTRATIO: Pupil-teacher ratio by town.
- LSTAT: Percentage of lower-status population.
- MEDV: Median value of owner-occupied homes (in $1000's).


Project Objectives
- Statistical Summaries:- Generate basic statistics for key variables.
- Create meaningful visualisations such as box plots, bar plots, histograms, and scatter plots.

- Answering Business Questions:- Charles River Impact: Is there a significant difference in median house values between homes near the Charles River and those not near it?
- Age of Properties: Does the age of properties affect their median values?
- NOX and INDUS Relationship: Can we conclude there is no relationship between nitric oxide concentrations and non-retail business acres?
- Distance and Home Values: How does distance to employment centres impact home values?

- Statistical Analysis:- Conduct hypothesis tests using:- T-tests.
- One-way ANOVA.
- Pearson correlation.
- Linear regression.


- Deliverables:- Detailed Jupyter Notebook.
- Insights and recommendations for upper management.



Getting Started
Prerequisites
To run this project, ensure you have the following installed:
- Python 3.x
- Libraries:- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Jupyter Notebook


Instructions
- Clone this repository:git clone <repository-url>

- Open the Jupyter Notebook:jupyter notebook

- Run the cells in the notebook sequentially to perform the analysis.


Visualizations
The project includes the following visualizations:
- Boxplot: Distribution of MEDV (Median value of homes).
- Bar Plot: Frequency of homes near the Charles River (CHAS variable).
- Boxplot: Relationship between discretised AGE and MEDV.
- Scatter Plot: Relationship between NOX and INDUS.
- Histogram: Distribution of PTRATIO.

Each visualisation includes titles, axis labels, and brief explanations.

Statistical Tests
- T-Test: Evaluate differences in house values near the Charles River.
- ANOVA: Determine if AGE impacts MEDV.
- Pearson Correlation: Assess the relationship between NOX and INDUS.
- Linear Regression: Analyse how DIS impacts MEDV.


Results and Insights
The findings from the analysis include:
- Median house values differ significantly based on proximity to the Charles River.
- The proportion of older properties affects housing prices.
- A significant correlation exists between nitric oxide concentrations and industrial areas.
- Increased distance to employment centres impacts housing prices predictably.


Contributing
Feel free to submit issues or feature requests. So that you know, contributions are welcome via pull requests.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Let me know if you'd like help refining this further! 😊


