# Project_4_Group_4

## RealEstatePred Modelling

## Purpose / Aim

Build a regression model to predict real estate sale amount (United States)

## Overview and Purpose
 This project aims to generate a well-performing predicting tool to predict selling prices of real estates given the historical real estate sales data. More specifically, we use the machine learning (ML), such as random forest modelling and neural network modelling, along with other techbologies such as Python Pandas in an attempt to generate a model to better predict the future selling prices of real estates. The model generated may be of valuable to people who purchase or sell real estates, for financial institutions who provide finance for purchases, and/or for other like-minded people who would like to exchange knowledge. The data used to generate the model, however, is from the real estate sales in the State of Connecticut in the United States, adjustments are therefore warranted when using the model to predict the selling prices using the data elsewhere. 

### Group Members
-    Olivia Yu
-    Oliver James Uy
-    Liwei Jiang

## Repository Contents
-   `Project4Group4_colab.ipynb`: Jupyter Notebook containing the codings and providing the visualisations.
-   `Images`: Folder containing screenshots of:
    -   `retrieving the data from Spark`: retrieving the data from S3 bucket.
    -   `data cleaning`: data cleaning process such as dropping null data points and unused columns.
    -   `data normalising and standardisation`: the coding for the process.
    -   `model initialisation and training`: the coding for initialising and training the model.
    -   `model evaluation`: the coding and results for the model evaluation.
    -   `model optimisation 1`: the coding including interative changes.
    -   `model optimisation 2`: the coding and the displayed results for model performance from model optimisation.

## How to Use
To use RealEstatePred Modelling, follow these steps:
1. Copy and clone the respository or download the `Project4Group4_colab.ipynb` file.
2. Sign up or log in to Google Colab: https://colab.research.google.com/notebooks/welcome.ipynb
3. Run the codes. 

## References

## Data Source

* Real Estate Saels 2001-2021 GL. Retrieved from ["https://catalog.data.gov/dataset/real-estate-sales-2001-2018>"]

-- Note: please respect the data licensing agreements by crediting the DATA.GOV as the data source when using this model. While the data is publicly available and no permission is needed when using the data, proper attribution is requested. The suggested citation for using this data is as above.


### References
- -   University of Adelaide. (2023). The Modules 19-22 contents in particular.
[https://bootcampspot.instructure.com/courses/4781/pages/19-unsupervised-machine-learning?module_item_id=1163457]
[https://bootcampspot.instructure.com/courses/4781/pages/20-supervised-machine-learning?module_item_id=1163509]
[https://bootcampspot.instructure.com/courses/4781/pages/21-deep-learning?module_item_id=1163546]
[https://bootcampspot.instructure.com/courses/4781/pages/22-big-data?module_item_id=1163587]

-- How to make an S3 Bucket Public. Retrieved from: https://saturncloud.io/blog/how-to-make-an-s3-bucket-public/

