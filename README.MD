
# HR Data Analysis — MNC Dataset

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-%20-blue?logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-%20-lightgrey?logo=numpy&logoColor=black) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%20-blue?logo=matplotlib&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-%20-blueviolet?logo=seaborn&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-%20-orange?logo=jupyter&logoColor=white) ![VSCode](https://img.shields.io/badge/VS%20Code-%20-007ACC?logo=visual-studio-code&logoColor=white)

Professional summary
--------------------
This folder contains an end-to-end exploratory analysis of HR data from a multi-national company (MNC). The analysis demonstrates data ingestion, cleaning, aggregation, visualizations, and concise business insights focused on headcount, compensation, performance, turnover and location-level trends.

Repository structure
-------------------
- `HR_Data_MNC_Data.csv` — raw dataset used for analysis.
- `HR_Data_Analysis_Project.ipynb` — annotated Jupyter notebook with data-cleaning steps, charts and interpretation.

Key deliverables
-----------------
- Reproducible Jupyter notebook documenting EDA, grouped summaries, and visual diagnostics.
- Visual outputs include distribution charts, department-level salary summaries, resignation/termination comparisons, and performance-by-department plots.

Technical details
-----------------
- Language: Python 3.8+
- Primary libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `jupyter`
- Recommended tools: VS Code (Jupyter extension) or standard Jupyter Notebook

Developer quickstart
--------------------
1. Clone the repository and open the project folder:

```bash
git clone https://github.com/Priyanka571705/hr-data-analysis
cd Data-Science-project/HR_DATA_MNC
```

2. Create an isolated environment and install dependencies (Windows example):

```bash
python -m venv venv
venv\Scripts\activate
pip install --upgrade pip
pip install pandas numpy matplotlib seaborn jupyter
```

3. Launch and run the notebook:

```bash
jupyter notebook HR_Data_Analysis_Project.ipynb
```

Reproducibility & testing
-------------------------
- Execute cells sequentially; preprocessing is implemented inline for transparency.
- For production workflows, extract transformation functions into version-controlled modules and add unit tests for critical data-cleaning logic.

Recommended next steps
----------------------
- Add `requirements.txt` or `environment.yml` for pinned dependencies.
- Export key figures to a `reports/` directory and include a one-page executive summary for stakeholders.
- Modularize preprocessing into `src/` and add small unit tests (e.g., validating `Performance_Rating` aggregation, salary conversions, missing-value strategies).

Files of interest
-----------------
- Notebook: [HR_Data_Analysis_Project.ipynb](Data-Science-project/HR_DATA_MNC/HR_Data_Analysis_Project.ipynb)
- Dataset: [HR_Data_MNC_Data.csv](Data-Science-project/HR_DATA_MNC/HR_Data_MNC_Data.csv)

License
-------
Refer to the repository root for license information. This work is provided for learning and demonstration purposes.

Need help?
----------
I can generate a `requirements.txt`, export notebook charts to `reports/`, or extract preprocessing into a reusable module — which would you like next?

