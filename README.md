# COVID-19 Data Analysis

This project analyzes COVID-19 data using datasets from the `../archive` folder. The analysis is broken down into structured notebooks.

## Setup

1.  Create a virtual environment (optional but recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Run the notebooks in the following order using Jupyter:
```bash
jupyter notebook
```

### Notebooks Overview

1.  **`01_data_cleaning.ipynb`**:
    -   Loads all datasets.
    -   Inspects data quality (missing values, formats).
    -   Prepares data for further analysis.

2.  **`02_global_analysis.ipynb`**:
    -   Visualizes worldwide trends over time.
    -   Analyzes daily new cases and global correlations.

3.  **`03_country_analysis.ipynb`**:
    -   Compares statistics across top-affected countries.
    -   Visualizes case trajectories and mortality rates.

4.  **`04_usa_analysis.ipynb`**:
    -   Focuses on the COVID-19 situation in the United States.
    -   Analyzes state-level and county-level data.
