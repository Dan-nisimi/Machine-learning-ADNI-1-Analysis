# Machine-learning-ADNI-1-Analysis

# ADNI Data Analysis

This project analyzes data from the Alzheimer's Disease Neuroimaging Initiative (ADNI) to explore the relationship between biomarkers and cognitive decline.

## Data

The primary dataset used is 'adni1_bl_cleaned.xlsx' (and later 'adni1_bl_cleaned_2.xlsx'), which contains baseline and follow-up measurements for various biomarkers and cognitive assessments.

## Analysis

The analysis includes:

- **Linear Regression:**  Predicting cognitive decline (CDRSB_bl and CDRSB_delta) using biomarkers like ABETA_bl, TAU_bl, PTAU_bl, and inflammatory markers.
- **Multiple Regression:**  Modeling house prices based on features like square footage, number of bedrooms, and bathrooms.
- **Pairwise Correlation:**  Calculating correlation coefficients between variables like height and weight.
- **Delta Change Analysis:**  Calculating and visualizing changes in CDRSB scores and biomarkers over time to assess disease progression.

## Libraries

The project utilizes libraries such as:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels

## Usage

To run the analysis:

1. Upload the dataset(s) to Google Colab.
2. Execute the code cells in the provided notebook.
3. Interpret the results based on the generated plots and metrics.

## Insights

The analysis aims to identify biomarkers that are significantly associated with cognitive decline in Alzheimer's disease. The findings can potentially inform early detection and treatment strategies.
