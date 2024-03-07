# Investigating Cancer Treatment Experiment: Insights through Data Analysis

## Introduction

Within this repository lies an investigation into a cancer treatment experiment conducted on laboratory mice. The primary objective was to evaluate different drug regimens' effectiveness in reducing tumor volume. This document offers a comprehensive overview of the project's structure and significant discoveries.

## Data Compilation

The investigation relies on two primary datasets:

1. **Mouse Metadata:** This dataset encompasses detailed information about the mice utilized in the experiment, including unique Mouse IDs, drug regimens, age, weight, and additional attributes. The corresponding file is denoted as `Mouse_metadata.csv`.

2. **Study Results:** This dataset provides in-depth insights into the experiment's outcomes, encompassing Mouse ID, timepoint, tumor volume, and metastatic site count. This data is stored in the file named `Study_results.csv`.

## Data Preprocessing

Before delving into the analysis, several data preprocessing steps were executed:

- Integration of the two datasets to create a cohesive DataFrame.
- Identification and resolution of duplicate data instances.
- Removal of data pertaining to mice with duplicate IDs.
- Computation of summary statistics for each drug regimen, including mean, median, variance, standard deviation, and SEM of tumor volume.

## Analysis Approach

The investigation comprises the following essential components:

1. **Statistical Insights:** Computation of summary statistics for each drug regimen to unravel insights into the efficacy of diverse treatments.

2. **Visual Representation:** Generation of various plots to visually represent the data, including bar plots, pie charts, box plots, and scatter plots.

3. **Correlation Analysis:** Estimation of the correlation coefficient and formulation of a linear regression model to explore the relationship between mouse weight and the average observed tumor volume under the Capomulin regimen.

## Key Observations

The investigation uncovers significant insights:

1. A discernible positive linear correlation is observed between mouse weight and tumor volume within the Capomulin regimen, suggesting a correlation where tumor volume tends to increase with mouse weight.

2. The Capomulin and Ramicane regimens showcase superior efficacy in reducing tumor volume compared to Infubinol and Ceftamin, as evidenced by lower mean and median tumor volumes and smaller variances.

3. No outliers are identified within the Capomulin regimen dataset, indicating a absence of extreme values or anomalous observations regarding tumor volume.

## Conclusion

This investigation furnishes valuable insights into the outcomes of the cancer treatment experiment and the relative effectiveness of various drug regimens. The findings hold the potential to guide further research initiatives and inform decision-making processes in the realm of cancer treatment.

For detailed insights and specific analysis outcomes, kindly refer to the Jupyter Notebook file enclosed within this repository.
