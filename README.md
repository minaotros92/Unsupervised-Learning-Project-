# machine_learning_project-unsupervised-learning

Project Summary:

Objective:

- Explore grocery store data to gain insights using unsupervised learning algorithms.


Process:

- Conducted exploratory data analysis (EDA) and preprocessing, including visualizations, outlier handling, standardization, normalization, and feature engineering.
- Applied clustering techniques such as K-Means and Hierarchical Clustering to group products.
- Utilized principal component analysis (PCA) for dimensionality reduction and to understand customer purchasing patterns.

Results:
EDA and Pre-processing:

- Identified no missing or duplicate values; handled outliers contextually, recognizing their significance based on annual spending.
- Applied one-hot encoding to categorical variables 'Channel' and 'Region' due to the absence of an ordinal relationship.
- Analyzed variable relationships through a correlation matrix, finding high correlation between 'Grocery_log' and 'Detergents_Paper_log'.


Clustering:

- Determined the optimal number of clusters (k=4) for K-Means using the elbow method and observed convergence in 8 iterations.
- Performed Hierarchical Clustering and determined the number of clusters (also 4) for comparison with K-Means.
- Found inconsistencies between K-Means and Hierarchical Clustering in the preliminary comparison.


PCA:

- Skipped during EDA and pre-processing to avoid redundancy.
- Used a Scree plot and cumulative explained variance to decide on reducing dimensions to the three most significant principal components, capturing 72% of total variance.
- Identified 'Fresh_log', 'Delicassen_log', and 'Frozen_log' as the most influential features.


Challenges:
- Time constraints affected the depth of analysis.
- Decisions on handling categorical variables and assumptions regarding clustering and PCA.


Future Considerations:
- Experiment with additional clustering techniques and visual representations of clusters.
- Incorporate random forest regression for feature selection in the EDA phase.
- Further investigate variable relationships and integrate additional business insights.
