# winedata
The following notebook contains the steps enumerated below for analyzing characteristics of red and white variants of the Portuguese "Vinho Verde" wine. Quality is based on sensory scores (median of at least 3 evaluations made by wine experts). Each expert graded the wine quality between 0 (very bad) and 10 (very excellent).
Data is available at: https://archive.ics.uci.edu/ml/datasets/Wine+Quality

    Import Data & Python Packages

    Assess Data Quality & Missing Values

    Exploratory Data Analysis - ggplot for python
        3.1 Red vs. White wines
        3.2 Facetplot

    Correlation Heatmaps - seaborn
        4.1 Heat Map - Red Wine
        4.2 Heat Map - White Wine
        4.3 Biggest Differences between White and Red Correlations

    Predicting Quality: Linear Regression
        5.1 80-20 Split of Training and Hold-Out Data
        5.2 60-40 Split of Training and Hold-Out Data
        5.3 Segmented LinReg (White & Red Separate Models)
