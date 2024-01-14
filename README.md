# Proximity-Analysis

**Overview**

This project involves preprocessing a stroke dataset and analyzing it using distance metrics. The analysis is focused on understanding the similarities and differences among patients based on various attributes. We use both Euclidean and Hamming distances to analyze numerical and categorical data, respectively.

**Dataset**

The dataset (Stroke_data.csv) contains various attributes related to stroke patients. These attributes are both numeric (e.g., age, BMI) and categorical (e.g., gender, smoking status).

**Features**

The dataset includes the following features:

Numeric: Age, BMI, etc.
Categorical: Gender, Smoking Status, etc.
Preprocessing

The preprocessing steps include:

Handling missing values.
Scaling numeric features.
Encoding categorical features.
Preprocessing Pipeline
The pipeline consists of:

SimpleImputer for imputation.
StandardScaler for scaling numeric features.
OneHotEncoder for encoding categorical features.
Distance Matrix Analysis

After preprocessing, we compute distance matrices for the first 50 samples:

Euclidean distance for numeric data.
Hamming distance for categorical data.

**Distance Calculations**
Euclidean Distance: Measures the straight-line distance between two points in Euclidean space.
Hamming Distance: Measures the number of positions with different symbols for categorical data.
Similarity and Dissimilarity Indices
Euclidean Dissimilarity: Normalized Euclidean distances.
Euclidean Similarity: Inverse of Euclidean dissimilarity.
Hamming Dissimilarity: Direct Hamming distances.
Hamming Similarity: Inverse of Hamming dissimilarity.

**Analysis Results**

Heatmaps to visualize distance matrices.
Average Euclidean and Hamming dissimilarity and similarity indices.
