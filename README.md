# Quantitative Assessment of Sleep Quality: A Statistical Framework for Sleep Recovery Scoring

This repository presents a statistical framework for developing a **Sleep Recovery Score** derived from movement data collected during sleep. The project applies advanced data analysis, clustering algorithms, and statistical modeling to investigate sleep patterns and quantify sleep quality.

## Project Overview:
- **Data Exploration**: Conducted exploratory data analysis to visualize temporal sleep movement trends and compute descriptive statistics, including mean, median, and standard deviation.
- **Deep Sleep Detection**: Operationalized deep sleep identification by isolating zero-movement periods and quantifying their duration in minutes.
- **Sleep State Classification**: Employed K-means clustering (K=3) to categorize non-deep sleep data into three distinct states: light sleep, paradoxical (REM) sleep, and awake states.
- **Multinight Analysis**: Applied the classification methodology to 138 datasets, each representing nightly sleep movement, to compute state-wise sleep durations and derive aggregate metrics.
- **Outlier Detection**: Implemented multivariate outlier detection techniques to identify anomalous sleep patterns across the dataset.
- **Ideal Pattern Comparison**: Calculated deviations from an ideal sleep distribution (20% deep sleep, 60% light sleep, and 20% REM sleep) using Euclidean distance measures.
- **Sleep Recovery Score**:
  - Developed a normalized scoring mechanism based on standardized Euclidean distance metrics.
  - Compared scores derived from K-means and hierarchical clustering (Ward linkage) methods to evaluate consistency.
  - Computed a composite score by averaging results from both methods.

## Statistical Insights:
This analysis provides a quantitative approach to sleep quality assessment, offering a robust measure of recovery potential based on statistical comparisons and clustering techniques. The methods employed here are foundational for advancing health monitoring applications in wearable technologies.

