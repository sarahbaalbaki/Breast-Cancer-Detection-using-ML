# Breast-Cancer-Detection-using-ML
Breast Cancer Detection using Machine Learning Methods

Authors: Sarah Baalbaki, Ethan Gaskin, William Hsu, Madison Stulir

Breast cancer is the most common cancer in women in the United States, after skin cancer. It constitutes about 30% of all new female cancers each year. Cancer pathologists commonly use Fine Needle Aspiration Biopsies to investigate suspicious masses in patients. This procedure is a preferred initial method for identifying cancer due to its minimally invasive nature and low cost. But, due to the small sample of cells it collects, sometimes misdiagnoses can happen, either from misinterpreting the images or not puncturing the mass properly.

Our goal is to use machine learning to help pathologists interpret digitized images of fine needle aspirates to help improve diagnostic accuracy, which we obtain from the Diagnostic Wisconsin Breast Cancer Database.
This dataset is composed of labeled cancerous and non-cancerous cell nuclei features, which we will use as input parameters to train our binary classification models.

Using the provided dataset, we train three different machine learning models to classify breast cancer tumors as malignant or benign. Given the non-linear, mostly gaussian distributions of the data across features, we chose to implement a Naive Bayes Classifier, a Random Forest Classifier, and linear and kernel Support Vector Machine to perform binary classification of malignant versus benign samples.


