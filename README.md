# Jupyter Notebook Analysis: "A Deep Dive into the RYM Top 5000 Albums"
#### Mirror from Kaggle: [A Deep Dive into the RYM Top 5000 Albums](https://www.kaggle.com/code/jbfriedli/a-deep-dive-into-the-rym-top-5000-albums)
#### Focus: Analysis of Top 5000 Albums on Sonemic (formerly RateYourMusic)

## Overview

This Jupyter Notebook provides a comprehensive analysis of the top 5000 albums on Sonemic, leveraging data visualization and statistical analysis techniques. 

### Import Section
- Libraries: `os`, `calendar`, `warnings`, `collections.Counter`, `math`, `pandas`, `numpy`, `matplotlib.pyplot`, `seaborn`, `plotly.graph_objs`.
- Purposes: Data manipulation, visualization, and statistical analysis.

### Load Data
- Dataset: Top 5000 Albums on Sonemic.
- Files: `rym_raw1.csv`, `rym_clean1.csv`.
- Dataframe: `df`.

### Data Exploration
- Initial examination of the dataset structure, types, and basic statistics.
- Visualization of distributions for average rating, rating count, and review count.

### Feature Engineering
- Splitting release dates into year, month, and day.
- Processing of genres and descriptors.
- Creation of combined genres and full name columns.

### Data Visualization and Analysis
- Visualization of top-rated, most-rated, and most-reviewed albums and artists.
- Analysis of best-rated albums per year and popularity of genres and descriptors over time.
- Examination of rarest genres and descriptors, as well as top-rated genres and descriptors.

### Key Insights
- Identification of trends in album ratings, popularity, and genre/descriptor preferences.
- Observations on the evolution of musical trends and preferences over the years.
- Insights into the popularity and critical acclaim of various genres and artists.
