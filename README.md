# Fantasy-Football
Wanted to analyze fantasy football metrics and predict top players for next year
This project analyzes historical fantasy football performance data to predict which players have the potential to exceed a certain performance threshold in the upcoming fantasy season. Using machine learning algorithms and statistical modeling, the model identifies high-performing players for each position.
 Project Overview

In this project, I 
-Collected and prepared fantasy football data to ensure data quality requirements and 
researched and plotted player performance trends.
-Built a classification model that identifies which players have the potential to surpass a PPR (points-per-reception) benchmark.
-Utilized statistical techniques to identify high-scoring players based on position.
-Evaluated the performance of the model using accuracy and other relevant metrics.

Tools I used were:
-Python Libraries: Pandas, NumPy, Seaborn, Scikit-Learn
-Data Visualization: Matplotlib, Seaborn
-Modeling: XGBoost Classifier 

How the Model Works
-Data Preparation: Historical player data were cleaned and prepared to be model-train-ready.
-Feature Engineering: Helpful features like PPR and position were used to train the model.
-Model Training: A classification model was trained to predict whether a player will exceed the defined PPR threshold.
-Predictions: For the upcoming season, the model identifies the top 3 players per position most likely to exceed expectations.
