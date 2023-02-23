# Draft PROPOSAL
# Detection of breast cancer
# What is your issue of interest (provide sufficient background information)?
Cancer is a disease where cells grow out of control. From the variations of cancer, breast cancer is the second most vulnerable one, for which deaths in women are the most. The probability that a woman dies due to breast cancer is 1 in 39, which is around 2.5%. Among 264,000 being diagnosed, around 42,000 women in the U.S. die each year from breast cancer
# Why is this issue important to you and/or to others?
Women whose breast cancer is detected at an early stage have a 93% survival rate in the first five years. Even though Mammogram screening is used to detect the tumor, it is not perfect. These statistics direct us to a machine learning approach to detect breast cancer, as the traditional method is not that much trustworthy. Detection of breast cancer at an early stage is possible if we solve this problem with a machine learning approach.
# What questions do you have in mind and would like to answer?
•	How accurate these models are?

•	Can this be used as an extension to enhance the performance of traditional methods?
# Where do you get the data to analyze and help answer your questions?
I gathered the dataset from Kaggle 

https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

Total no of rows 569 and total no of columns is 32
Columns are as follows
ID

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


Ten real value features are computed for each nucleus
a) radius (mean of distances from center to points on the perimeter)

b) texture (standard deviation of gray-scale values)

c) perimeter

d) area

e) smoothness (local variation in radius lengths)

f) compactness (perimeter^2 / area - 1.0)

g) concavity (severity of concave portions of the contour)

h) concave points (number of concave portions of the contour)

i) symmetry

j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.
All feature values are recoded with four significant digits.
Missing attribute values: none
Class distribution: 357 benign, 212 malignant




# What kinds of techniques/models do you plan to use?
1. Logistic Regression
2. K Neighbours Classsifier
3. SVM
# What will be your unit of analysis and what variables/measures do you plan to use in your analysis?
Unit of analysis will be the cancer predicion and the variables are mean radius, mean texture, mean perimeter, mean area, mean smoothness
# How do you plan to develop/apply ML and how you evaluate/compare the performance of the models?
I'm using F1, recall, precision and jaccard index to evaluate the performance of the model.
# What outcomes do you intend to achieve?
I intend to observe and learn ML model creation process and comparing the model for finding out the efficiency.
