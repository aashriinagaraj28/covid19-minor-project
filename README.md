# COVID-19 Minor Project

## Files

- `Project_Report.docx` - written project report.
- `analysis.ipynb` - Python notebook that reproduces the analysis and charts.
- `patient.csv` - patient-level data file linked in the assignment brief.
- `figures/` - report figures generated from the notebook analysis.

## Run the notebook

1. Install Python 3 and Jupyter Notebook or JupyterLab.
2. In this folder, run `pip install -r requirements.txt`.
3. Open `analysis.ipynb` and run all cells from top to bottom.

The notebook reads `patient.csv` from the same folder and writes figures to `figures/`. It does not download data from the internet.

## What to present

- The project describes an early South Korea COVID-19 patient file covering 20 January to 1 March 2020.
- The file includes 4,212 patient records; confirmations cluster at the end of February.
- Among recorded infection reasons, contact with a patient and visits to Daegu are most frequent.
- Among 28 records with release dates, the median time from confirmation to release is 16 days.
- The file has substantial missing data, so these are summaries of recorded values and not complete population estimates. No reliable recovery prediction model is supported by this snapshot.

## Source

Patient-level case dataset linked in the project brief: https://drive.google.com/file/d/1TXoqikmE0S3LGem8Ig-GktaJJyZPGMgN/view?usp=sharing
