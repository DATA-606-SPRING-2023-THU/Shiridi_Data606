# Title:Detection of breast cancer

Name : Shiridinath Konduru

Campus ID : RS71814

## Introduction:

Cancer is a condition when cells proliferate uncontrollably. A woman's chance of dying from breast cancer is 1 in 39, or roughly 2.5%. In the United States, about 42,000 women die from breast cancer each year, out of the 264,000 who are diagnosed. One of the most prevalent malignancies in women worldwide is breast cancer. According to estimates, 30% of newly diagnosed malignancies in women in the United States in 2020 will be breast cancer. A higher survival percentage and more effective treatment choices are both possible with early identification of breast cancer. We will talk about different machine learning models and how well they perform when determining if a tumor is benign or malignant in this session.

## Aim:

93% of women with breast cancer who are diagnosed early will survive for the first five years. Mammogram screening is used to find the tumor, but it is not completely accurate. These statistics suggest using machine learning to diagnose breast cancer as the conventional method is not very reliable. 

Our goal in this project is to examine the widely available Wisconsin Breast Cancer dataset and assess how well various machine learning models perform at identifying tumor malignancy. We can evaluate how well these models perform at correctly classifying tumors as benign or malignant by studying the dataset and using a variety of classification algorithms. This data can help medical personnel make educated decisions about patient care and lead to the creation of more precise diagnostic tools.


## Data Collection:
I gathered the dataset from Kaggle
https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data
Total no of rows 569 and total no of columns is 32 Columns are as follows ID
Diagnosis

Radius_mean

Texture_mean

Perimeter_mean

Area_mean

Smoothness_mean

Compactness_mean

Concavity_mean

Concave points_mean

Symmetry_mean

Fractal_dimension_mean

Radius_se

Perimeter_se

Area_se

Smoothness_se

Compactness_se

Concavity_se

Concave points_se

Symmetry_se

Fractal dimension_se

Radius_worst

Texture_worst

Perimeter_worst

Area_worst

Smoothness_worst

Compactness_worst

Concavity_worst

Concave points_worst

Symmetry_worst

Fractal dimension_worst

Ten real value features are computed for each nucleus a) radius (mean of distances from center to points on the perimeter)

b) texture (standard deviation of gray-scale values)

c) perimeter

d) area

e) smoothness (local variation in radius lengths)

f) compactness (perimeter^2 / area - 1.0)

g) concavity (severity of concave portions of the contour)

h) concave points (number of concave portions of the contour)

i) symmetry

j) fractal dimension ("coastline approximation" - 1)


There are 569 breast cancer patients represented in this dataset. The digital photographs of the breast tissue for each patient have been used to extract 30 characteristics. The radius, texture, perimeter, area, smoothness, compactness, concavity, symmetry, and fractal dimension of the image's cells are only a few examples of these attributes.
The diagnosis of the patient, which can either be "M" (for malignant) or "B" (for benign), is the target variable in this dataset. 212 patients had malignant cancer diagnoses in this sample, while 357 patients had benign diagnoses.

## Data set:


