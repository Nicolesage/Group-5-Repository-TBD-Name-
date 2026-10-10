Your coding work should follow this workflow:

Repository Structure
project-root/
├── data/            # AmesHousing.csv (provided dataset)
├── notebooks/       # Jupyter Notebooks
├── results/         # output files (charts, regression results, etc.)
├── README.md        # project description
└── requirements.txt # Python dependencies
Notebooks
Create at least two Jupyter Notebooks:

Data Exploration

Load AmesHousing.csv from the /data folder using relative paths.
Produce descriptive statistics.
Create at least two visualizations.
Regression Analysis

Run at least one multiple regression predicting SalePrice from two or more independent variables.
Example variables: GrLivArea, OverallQual, GarageCars, YearBuilt.
Reproducibility
Your project must run on every teammate’s computer (and mine). To ensure this:

Always use relative paths (e.g., ../data/AmesHousing.csv).
Create a requirements.txt listing Python dependencies:

pip freeze > requirements.txt
👉 This takes a “snapshot” of your Python environment and saves it. Teammates can then run:

pip install -r requirements.txt
to install the same versions.

Document any setup instructions in your README.md.

# Project Group 5 SCCT – Ames Housing Analysis
**DSA 8670 – Group 5:** Tristen Rigby, Abigail , Nicole Sage, Nicholas Knight, William Bartemes

## Description
We analyze the Ames Housing dataset to find which home features drive sale price, using exploratory analysis, visualizations, and regression models.

## Structure
```
data/        AmesHousing.csv
notebooks/   Jupyter notebooks (run in numbered order)
figures/     Saved plots
requirements.txt
```

## Setup
```bash
git clone https://github.com/Nicolesage/Group-5-Repository-TBD-Name-.git
cd Group-5-Repository-TBD-Name-
pip install -r requirements.txt
```
Requires Python 3.10+ with pandas, numpy, matplotlib, seaborn, scikit-learn, and jupyter.

## Running
Run `jupyter notebook`, open `notebooks/`, and run each notebook in order using **Kernel → Restart & Run All**.

## Data Source
De Cock, D. (2011). Ames, Iowa: Alternative to the Boston Housing Data. *Journal of Statistics Education*, 19(3).
