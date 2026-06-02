# Healthcare Data Analysis

![Python](https://img.shields.io/badge/Python-3.11%2B-blue?logo=python&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.3-150458?logo=pandas&logoColor=white)
![Repo Size](https://img.shields.io/github/repo-size/Santhosh-Manoharan/healthcare_data_analysis)

Exploratory data analysis and symptom-based disease classification using a synthetic healthcare dataset of **25,000 patient records**.

---

## Project Overview

This project performs end-to-end data analysis on a Healthcare Symptoms-Disease Classification Dataset sourced from Kaggle. The Jupyter notebook walks through loading the data, exploratory analysis, and visualisation to uncover patterns between reported symptoms and diagnosed diseases.

**Dataset:** [Healthcare Symptoms-Disease Classification Dataset](https://www.kaggle.com/datasets/kundanbedmutha/healthcare-symptomsdisease-classification-dataset)

### Dataset Schema

| Column          | Type   | Description                           |
|-----------------|--------|---------------------------------------|
| `Patient_ID`    | int64  | Unique identifier for each patient    |
| `Age`           | int64  | Patient age in years                  |
| `Gender`        | str    | Patient gender (Male / Female / Other)|
| `Symptoms`      | str    | Comma-separated list of symptoms      |
| `Symptom_Count` | int64  | Number of symptoms per patient        |
| `Disease`       | str    | Diagnosed disease / condition         |

---

## Tech Stack

- **Language:** Python 3.11
- **Notebook:** Jupyter
- **Data Manipulation:** pandas, numpy

---

## Quick Start

### 1. Clone the Repository

\`\`\`bash
git clone https://github.com/Santhosh-Manoharan/healthcare_data_analysis.git
cd healthcare_data_analysis
\`\`\`

### 2. Set Up the Environment

\`\`\`bash
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
\`\`\`

### 3. Run the Notebook

\`\`\`bash
jupyter notebook analysis.ipynb
\`\`\`

### 4. Get the Dataset

The dataset (\`Healthcare.csv\`) is expected in the project root. You can download it via Kaggle:

\`\`\`python
import kagglehub
path = kagglehub.dataset_download("kundanbedmutha/healthcare-symptomsdisease-classification-dataset")
\`\`\`

---

## Project Structure

\`\`\`
healthcare_data_analysis/
├── .github/workflows/ci.yml    # CI pipeline
├── .gitignore                   # Python / ML / Jupyter ignores
├── analysis.ipynb               # Main analysis notebook
├── Healthcare.csv               # Dataset (25 000 records)
├── LICENSE                      # MIT License
├── README.md                    # Project documentation
└── requirements.txt             # Pinned Python dependencies
\`\`\`

---

## License

This project is licensed under the [MIT License](LICENSE).
