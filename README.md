# NBA Player Progress Analysis

This project analyzes NBA player performance across multiple seasons to identify improvement trends and prepare the dataset for future machine learning models. The notebook includes data cleaning, feature engineering, exploratory data analysis (EDA), and building a long-term structure suitable for tracking player development.

## Project Overview

The goal of this project is to transform raw NBA season statistics into meaningful insights about player progress. The workflow includes:

* Cleaning and preprocessing the dataset
* Handling missing values
* Renaming and organizing columns
* Creating a long-term dataset to track seasonal changes
* Calculating progress metrics (e.g., changes in MP, PTS, AST, etc.)
* Visualizing distributions and trends
* Preparing the dataset for future ML modeling

This analysis serves as a foundation for predicting future performance and identifying players with consistent improvement.

## Features

* Complete data preprocessing pipeline
* Exploratory data analysis of NBA player stats
* Long-term player tracking across seasons
* Visualizations using Matplotlib and Seaborn
* A clean and reproducible Jupyter Notebook

## File Structure

```
.
├── NBA_Basketball.ipynb     # Main analysis notebook
├── data/                    # Optional folder for dataset
└── README.md
```

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## How to Run

1. Clone the repository:

   ```
   git clone https://github.com/<your-username>/nba-player-progress-analysis
   ```
2. Open the notebook using Jupyter Notebook or VS Code.
3. Install the required libraries:

   ```
   pip install -r requirements.txt
   ```
4. Run all notebook cells.

## Future Work

* Building machine learning models to predict long-term player performance
* Algorithms such as XGBoost, RandomForest, and Linear Regression
* Feature importance analysis and evaluation metrics
* Deployment using FastAPI for serving predictions

## License

MIT License
