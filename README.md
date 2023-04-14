# cancer_classifier

## Introduction

Cancer is a disease in which some of the body's cells grow uncontrollably and destory your body. There are two type of cancer: benign cancer and malignant cancer. Malignant cancer grow quickly and generally metastasize to other areas of body. Benign cancer don't spread to other body part and patient may not need treatment. In general, malignant cancer is more threatening to a person's health.

Since malignant cancer speard faster, the patient have to recieve the treatment before the cancer spread to the full body. It is critical for doctor to know which cancer do the patients have and arrange appropriate treatment for patients. I am going to use Machine learning techique to create cancer classifer base on the cancer cell's features. This will provide a support reference and guideline for doctor to determine which cancer do the patients have and the priority of patients need the treatments.

---

## About the Dataset

569 cancer cells and 30 features to determine whether the cancer cells in our data are benign or malignant.

Our cancer data contains 2 types of cancers: 1. benign cancer (B) and 2. malignant cancer (M).

Data Sources:
https://www.kaggle.com/datasets/erdemtaha/cancer-data

---

## Data Analyze/ feature engineering

The dataset is not balanced.

There are some corrlation between the features.

Since the target value is not binary, I will apply label encoder to trun the value to binary.

More detail Analytze is in analyze.ipynb.

---

## Models

The model that I am going to use:

- Logistic Regression
- SVM
- Random Forest

##
