
# Lab 2: Analysis Notebook

## Project Overview
This project analyzes the Mayo Clinic PBC trial dataset using Python and Jupyter Notebook. The goal is to compare baseline bilirubin levels between two randomized treatment groups.

## Research Question
How do baseline bilirubin levels compare between the D-penicillamine and placebo groups in the Mayo Clinic PBC trial?

## Dataset
The Mayo Clinic PBC dataset is publicly available through Rdatasets.

Dataset URL:
https://vincentarelbundock.github.io/Rdatasets/csv/survival/pbc.csv

The dataset is loaded directly from the online source using pandas.

## Analysis
The analysis includes:
- Loading the original dataset
- Exploring missing values
- Filtering randomized trial participants
- Grouping participants by treatment
- Calculating mean and median bilirubin levels
- Creating a bar graph comparing median bilirubin levels

## Results
The median baseline bilirubin level was 1.40 mg/dL for the D-penicillamine group and 1.30 mg/dL for the placebo group.

The difference between the two groups was 0.10 mg/dL. These baseline measurements do not establish the effects of treatment.

## Project Files
- `notebooks/lab2_analysis.ipynb`: Main Jupyter Notebook
- `notebooks/lab2_analysis.html`: Rendered HTML output
- `README.md`: Project documentation
- `AI_USAGE.md`: AI assistance documentation

## How to Run
1. Install Python and Jupyter Notebook.
2. Install pandas and matplotlib.
3. Open `notebooks/lab2_analysis.ipynb` in VS Code or Jupyter.
4. Select a Python kernel.
5. Click Restart and Run All.
6. The dataset will load automatically from its online source.

## AI Assistance
OpenAI ChatGPT (GPT-6) was used to help with Python code, troubleshooting, data analysis, and understanding the assignment requirements.

See `AI_USAGE.md` for more information.