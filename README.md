Iris Dataset – EDA & One Hot Encoding

This notebook contains a complete Exploratory Data Analysis (EDA) of the Iris dataset (150 rows, 4 numerical columns and 1 categorical column,
species). The data was first loaded and checked using .info(), .describe(), missing values, and duplicates, and duplicate rows were removed. 
Univariate analysis used histograms and boxplots to study the distribution,
revealing 4 outliers in sepal_width that turned out to be natural variation rather than errors. Bivariate analysis, 
through scatter plots and correlation, showed a strong positive correlation (~0.96) between petal_length and petal_width.
Species-wise comparisons were also made using bar charts and boxplots. Multivariate analysis included a pairplot and a 3D scatter plot,
and species was mapped to numeric codes (specie_num, species_num). 
Finally, the conclusions were written down, and a One Hot Encoding section was started to convert species into proper 0/1 columns.
