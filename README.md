# Project_4_Group_4

## Credit Card Eligibility Prediction Modelling

## Overview and Purpose
 This project aims to generate a well-performing predicting tool to predict the eligibility for a credit card given the historical assessment data. More specifically, we used machine learning (ML) modelling tools, such as random forest modelling and neural network modelling, along with other modules such as Python Pandas in an attempt to generate a model to assess the eligibility for a credit card more accurately. The model generated may be of valuable to people who apply for a credit card to prepare in advance, for financial institutions who has not got their own modelling to assist with assessing the eligibility, and/or for other like-minded people who would like to exchange knowledge. 

### Group Members
-    Olivia Yu
-    Oliver James Uy
-    Liwei Jiang

## Repository Contents
-   `Project4Group4_colab.ipynb`: Jupyter Notebook containing the codings and providing the visualisations.
-   `Images`: Folder containing screenshots of:
    -   `retrieving the data from Spark`: retrieving the data from S3 bucket.
    -   `data cleaning`: data cleaning process such as checking outliers if any.
    -   `data normalising and standardisation`: the coding for the process.
    -   `model initialisation and training`: the coding for initialising and training the model.
    -   `model evaluation`: the coding and results for the model evaluation.
    -   `model optimisation 1`: the coding including interative changes.
    -   `model optimisation 2`: the coding and the displayed results for model performance from model optimisation.

## How to Use
To use Credit Card Eligibility Prediction Modelling, follow these steps:
1. Copy and clone the respository or download the `Project4Group4_colab.ipynb` file.
2. Sign up or log in to Google Colab: https://colab.research.google.com/notebooks/welcome.ipynb
3. Run the codes.

### Important Note

While the data used in this analysis presents promising results, it's important to note that the values within the DataFrame do not reflect current market conditions. Although the dataset has been cleaned up, with preprocessing steps applied to ensure data integrity, the exact origin or collection method of the dataset remains uncertain. This analysis serves the purpose of demonstrating the application of various models and evaluating their performance using available data. By providing transparency about the dataset's limitations and the purpose of the analysis, we aim to offer readers a clear understanding of the context and scope of this project.


## References

## Data Source
  - **Source**: Retrieved from https://www.kaggle.com/datasets/rohit265/credit-card-eligibility-data-determining-factors
  - **Storage**: The data is stored in an AWS S3 Bucket for ease of use.


-- Note: please respect the data licensing agreements by crediting the Kaggle as the data source when using this model. While the data is publicly available and no permission is needed when using the data, the citation for using this data is suggested as above.


### References
- -   University of Adelaide. (2023). The Modules 19-22 contents in particular.
[https://bootcampspot.instructure.com/courses/4781/pages/19-unsupervised-machine-learning?module_item_id=1163457]
[https://bootcampspot.instructure.com/courses/4781/pages/20-supervised-machine-learning?module_item_id=1163509]
[https://bootcampspot.instructure.com/courses/4781/pages/21-deep-learning?module_item_id=1163546]
[https://bootcampspot.instructure.com/courses/4781/pages/22-big-data?module_item_id=1163587]

-- How to make an S3 Bucket Public. Retrieved from: https://saturncloud.io/blog/how-to-make-an-s3-bucket-public/

