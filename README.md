# Breast-Cancer-Detector
Breast Cancer Classification: A Comprehensive Analysis with Outlier Investigation
🎯 Objective
This project presents a comprehensive analysis of the Wisconsin Diagnostic Breast Cancer dataset, focusing on:

Thorough exploratory data analysis
Detailed outlier detection and analysis
Machine learning model comparison
Clinical insights and interpretations
📊 Dataset Overview
The Wisconsin Diagnostic Breast Cancer (WDBC) dataset contains features computed from digitized images of fine needle aspirate (FNA) of breast masses. For each cell nucleus, 10 real-valued features are computed with three statistical measures each:

Mean - average value
SE (Standard Error) - standard error
Worst - mean of the three largest values
Feature Categories
🔍 Identification & Target

id: Unique identifier
diagnosis: Target variable (M = Malignant, B = Benign)
📏 Size/Shape Features

radius_*: Distance from center to perimeter points
perimeter_*: Cell nucleus perimeter
area_*: Cell nucleus area
🔍 Texture & Regularity

texture_*: Standard deviation of gray-scale values
smoothness_*: Local variation in radius lengths
compactness_*: (perimeter² / area - 1.0)
symmetry_*: Bilateral symmetry measure
🌊 Concavity Features

concavity_*: Severity of concave contour portions
concave_points_*: Number of concave contour portions
🔬 Complexity

fractal_dimension_*: Coastline approximation - 1
