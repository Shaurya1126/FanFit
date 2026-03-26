# FanFinder
## Link for live demo: https://slikhi.pythonanywhere.com/
Want to get into soccer but don't know what team and player to support? Or just want to feel like you're scouting for different talent from the UCL? I made FanFinder just for that!

## Tech stack
-Flask
-Pandas
-NumPy
-Matplotlib
-SciKitLearn (for KNN & K-means clustering)
-HTML/CSS/JS

## Model Development

### 1. Data Processing
Cleaned and preprocessed player statistics using pandas and NumPy
Handled missing values using group-based imputation
Normalized features for machine learning models

### 2. Feature Engineering

Created meaningful football metrics such as:

avg_goals_per_game
team_index (team playstyle)
showman_index (flair / dribbling)
aggression_index
runner_index
Goalkeeper-specific stats (e.g. saves per 90)

### 3. Archetype Creation

Used K-means clustering to group players into playstyle-based archetypes:

Examples:

Speedster
Playmaker
Defensive Enforcer
Explosive Attacker
Shot Stopper (Goalkeepers)

### 4. Player Recommendation

Used K-Nearest Neighbors to:

Take user input (playstyle, physical traits, stats)
Find the most similar players in the dataset
Return top matches with explanations

### 5. Match Scoring
Computes similarity using feature-wise comparison
Outputs a match percentage (0–100%)
Explains why each player was recommended

## Features
✅ Separate pipelines for:
Goalkeepers
Outfield players
✅ Interactive user input
✅ Interpretable recommendations
✅ Archetype-based analysis
✅ Real-world football data

## Why This Project Matters

Unlike basic ML projects, this system:

Uses real-world domain knowledge
Produces interpretable results
Simulates a real recommendation engine

## Key Takeaways
Built a full ML pipeline from data cleaning → modeling → deployment
Combined unsupervised learning (KMeans) with similarity search (KNN)
Designed domain-specific features for football analytics
Focused on interpretability and user experience

# Author
## Shaurya Likhi - CS @ UWaterloo
## slikhi@uwaterloo.ca
