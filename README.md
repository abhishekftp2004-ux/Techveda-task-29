# Task 29 — Seaborn Fundamentals (Expanded + Efficient)

## Objective
Create and interpret statistical visualizations using Python, Pandas, Seaborn, and Matplotlib.

## Deliverables
- `seaborn_fundamentals.py`: modular, reusable Python program
- `Task_29_Seaborn_Fundamentals.ipynb`: notebook with code and explanations
- `data/`: two local illustrative CSV datasets
- `visualizations/`: six chart images
- `Task_29_Seaborn_Fundamentals_Explanation.pdf`: expanded learning guide
- `requirements.txt`: project dependencies

## Data transparency
The bundled passenger-style and flower-style CSV files are illustrative teaching samples created for this project. They are not the original Kaggle Titanic dataset or canonical Iris dataset. Do not present the example results as official historical findings.

## Setup
1. Install Python 3.10+.
2. Open a terminal in this extracted folder.
3. (Recommended) create a virtual environment:
   - Windows: `python -m venv .venv`
   - PowerShell: `.\.venv\Scripts\Activate.ps1`
   - macOS/Linux: `source .venv/bin/activate`
4. Install dependencies: `python -m pip install -r requirements.txt`
5. Run the script: `python seaborn_fundamentals.py`
6. Or open the notebook: `jupyter notebook Task_29_Seaborn_Fundamentals.ipynb`

## Charts
1. Count plot — categorical counts split by a group
2. Box plot — distribution comparison by category
3. Histogram + KDE — numerical distribution shape
4. Scatter plot — relationship between two numerical variables
5. Heatmap — correlation matrix
6. Pair plot — pairwise feature exploration

## Efficiency and code quality
- Load each CSV once and reuse the resulting DataFrames.
- Keep each chart in a small function for easier testing and maintenance.
- Validate expected columns early to catch schema mistakes.
- Use a shared theme and save helper to avoid duplicated plotting boilerplate.
- Save figures and close them to release memory during batch runs.
- Compute the correlation matrix once before plotting it.
- Use readable names and comments rather than overly compressed code.

## Top 5 skills
Python, Seaborn, Data Visualization, Exploratory Data Analysis (EDA), Statistical Interpretation.
