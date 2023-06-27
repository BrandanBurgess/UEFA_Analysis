# UEFA_Analysis
Analysis of the best midfielders in Europe's top 5 football leagues.

UEFA Midfielder Analysis (2021-22 season) ⚽

Purpose ❓

The purpose of this project is to learn about machine learning with Python and its libraries. The task is to perform explorative data analysis and find the top-performing midfield players via key metrics.

Information about the dataset 📊

This dataset contains 2021-2022 football player stats per 90 minutes.
Only players from the Premier League, Ligue 1, Bundesliga, Serie A, and La Liga are listed.
Here is the link to the dataset: https://www.kaggle.com/datasets/vivovinco/20212022-football-player-stats

Report Process 📊

1. Data Loading and Cleaning:

The UEFA Players statistics dataset is loaded into a pandas DataFrame.
The information about the dataset is displayed, showing the columns and their data types.
Rows with missing values are dropped.

2. Data Exploration and Visualization:

Train-test split is performed on the cleaned dataset using a test size of 20%.
Histograms are plotted to visualize the distribution of players' attributes prior to analysis
Finally, a correlation matrix heatmap is created using sns.heatmap() to examine the relationships between key metrics for midfielders.

3. Linear Regression Model:

The dataset is prepared for training a linear regression model.



Summary 📝

The UEFA Midfielder Analysis project aims to conduct an in-depth exploration and develop predictive models using machine learning techniques in Python. The initial steps involve gathering and cleaning the dataset specifically focused on midfielders in Europe's top 5 leagues. The data is then explored and visualized to gain insights into player characteristics and performance metrics. Feature engineering techniques such as identifying the best progressive passers, ball carriers, and pace dictators are employed to extract meaningful information from the dataset. Additionally, linear regression is utilized to investigate the relationship between a midfielder's age and their pass success rate, providing insights into how age influences passing accuracy. The project encompasses data preprocessing, model training, and evaluation, showcasing the use of machine learning algorithms to gain a comprehensive understanding of midfielders' performance in the top 5 European leagues. Such analysis can help teams identity player archetypes when looking to revamp their squads. The evaluation results, including the coefficient of determination (R-squared), demonstrate the predictive performance of the models and their ability to explain the variance in pass success rate based on a midfielder's age. By leveraging linear regression and other analytical techniques, the project sheds light on the key factors influencing midfielders' performance and provides valuable insights for player evaluation and team strategies.

Technologies Used

Python Jupyter Notebook Pandas NumPy Matplotlib
