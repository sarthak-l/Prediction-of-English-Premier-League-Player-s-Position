# English Premier League Player Analysis 2020-2021
This project analyzes the 2020–21 English Premier League (EPL) player statistics to explore patterns and predict player positions, specifically distinguishing between strikers/midfielders and other positions. Utilizing detailed player performance data, we employ clustering and logistic regression to understand how different statistical measures cluster players and predict their playing positions.

# Data Source
The dataset was obtained from Kaggle, featuring comprehensive statistics for every player in the English Premier League for the 2020–21 season. It includes metrics such as goals, assists, xG (expected goals), xA (expected assists), passes attempted, pass accuracy, and more. The original dataset can be found here: English Premier League 2020/2021 Dataset on Kaggle.

# Research Question
The primary question this project aims to answer is whether player statistics (goals scored, minutes played, matches played, and passes made) cluster in a way that can predict their striker or midfielder position.

# Variables of Interest
Mins: Minutes played by the player
Goals: Goals scored by the player
Assists: Assists made by the player
Matches: Matches played by the player
Position: The playing position of the player
str_or_no: A dummy variable indicating if the player is a striker/midfielder (1) or not (0)

# Methodology
Data Wrangling: The dataset was cleaned and prepared for analysis, including selecting variables of interest and dealing with missing values.
Visualization: Various plots were generated to understand the distribution and relationships between the variables.
Dimension Reduction: Used clustering techniques (K-means) to explore how players' statistics cluster and identify the optimal number of clusters.
Modeling: A logistic regression model was built to predict whether a player's statistics would classify them as a striker/midfielder or not.
Evaluation: The model's performance was evaluated using accuracy, sensitivity, specificity, and the Area Under the Curve (AUC) metrics.
Results
The analysis suggests that player statistics cluster into meaningful groups, with three clusters providing a slightly better differentiation than two. The logistic regression model indicated that these clusters could predict a player's position as a striker/midfielder with moderate accuracy. However, the overall model performance highlighted the challenges in using statistical performance alone to accurately predict player positions.

# Conclusions
This project demonstrates the potential of using machine learning techniques to cluster and predict player positions based on statistical performance in the English Premier League. Despite the moderate success, it underscores the complexity of soccer analytics and the need for more nuanced approaches or additional data to improve predictive accuracy.

# Acknowledgements
Thanks to Kaggle and the dataset provider for making the English Premier League 2020–21 player statistics available for analysis.

