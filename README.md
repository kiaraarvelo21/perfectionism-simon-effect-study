# Perfectionism and the Simon Effect

This project examines whether perfectionism is related to performance on a cognitive task measuring the speed–accuracy trade-off, known as the Simon effect. The analysis was conducted as part of an academic project in the Information Science program at the University of Amsterdam.

## Research Question
Is there a relationship between perfectionism and the size of the Simon effect in a sample of university students?

## Data
The dataset consists of anonymized responses from students who completed:
- The Simon Task, measuring reaction time differences between compatible and incompatible trials
- The Short Revised Almost Perfect Scale (SAPS), measuring perfectionism

The final dataset was cleaned and preprocessed prior to analysis.

## Methodology
- Data preprocessing and cleaning using Python and Pandas  
- Calculation of the Simon effect based on reaction time differences  
- Normality testing using the Shapiro–Wilk test  
- Correlation analysis using Spearman’s rho due to non-normal data distributions  

## Analysis
The analysis was performed in a Jupyter Notebook and includes:
- Descriptive statistics
- Statistical testing
- Data visualizations such as histograms and scatterplots

## Results
No statistically significant relationship was found between perfectionism (SAPS scores) and the size of the Simon effect in this sample. The results suggest that perfectionism does not directly influence performance on this cognitive task, though limitations such as sample size should be considered.

## Tools
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Files
- `analysis/simon_effect_analysis.ipynb` – Main analysis notebook  
- `data/simon_effect_clean.csv` – Cleaned dataset used in the analysis  

## Notes
This project reports non-significant findings, which are presented transparently and discussed in the context of methodological limitations and directions for future research.
