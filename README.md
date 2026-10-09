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
