# Cricket-Run-Predictor
Predicting cricket match runs using data analysis.
In this file I have the code notebook to predict the expected runs
Expected Runs Prediction Model
Overview
This project, created by Zain, uses a machine learning model to predict the expected runs for each ball faced in T20 cricket matches. The model is built using ball-by-ball data from all T20 matches played since January 1, 2015. By analyzing key factors from the ongoing match, it aims to estimate how many runs are likely to be scored on a given delivery and then compares the prediction with the actual runs scored.

Key Factors Considered:
Innings Run Rate (before the ball): The run rate at the point just before the ball is bowled, reflecting the momentum of the innings.
Number of Wickets Down (before the ball): The number of wickets that have fallen before the ball is bowled, indicating how much pressure the batting team is under.
Innings Balls Remaining (before the ball): The number of balls left in the innings, giving context to the stage of the game.
Calculation of Expected Runs
For each ball faced by the batter, the model calculates a value representing the expected runs based on the above factors. This expected value is then compared with the actual runs scored on that ball to determine the Runs Above Average Replacement (RAAR). RAAR helps evaluate the batter's performance compared to what would typically be expected in similar situations.


