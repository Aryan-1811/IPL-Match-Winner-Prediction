# IPL-Match-Winner-Prediction
Machine learning models and interactive analysis to predict the winner of IPL matches and understand match state dynamics.

## Notebooks

### 1) Win Prediction Model
File: `Win Prediction Model .ipynb`  
What it does:
- Loads `ipl_ball_by_ball_updated.csv`
- Builds and evaluates classification models using scikit-learn and XGBoost
- Uses metrics like accuracy and confusion matrix
- Includes many visualizations for exploration and model checks

### 2) Interactive Model
File: `Interactive Model.ipynb`  
What it does:
- Match state tools for first and second innings
- Runs prediction functions for both innings
- Winner helper function from current match state
- Utilities to find required runs at a stage and wickets that can be lost
- Interactive style charts and multiple plots for intuition building

## Objectives
- Predict match winners using delivery level information
- Explore how runs and wickets across phases relate to the final result
- Provide quick interactive style tools that translate model insight into match intuition

## Tools and Libraries
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- scikit-learn and XGBoost
- Jupyter Notebook

## Dataset
- **ipl_ball_by_ball_updated.csv**  
  https://drive.google.com/file/d/1m2mEOvVDinwEEpXOGAdjDrrSPAzF2ulj/view?usp=sharing

Place the file in a local folder named `data` or update the path in the notebook if you prefer a different location.

## How to Use
1. Open the notebooks in Jupyter
2. Ensure the dataset path in the Win Prediction notebook points to your local CSV
3. Run all cells to generate the visualizations and predictions
4. Use the Interactive Model notebook to explore match state scenarios

## Outputs and Insight
- Winner predictions from trained models
- Confusion matrix and summary scores for evaluation
- Plots that show how match state metrics relate to outcomes
- Interactive style exploration for first and second innings scenarios
