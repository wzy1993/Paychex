
# Paychex capstone project
# Background and Goals：



Paychex has over 600,000 clients to which it provides HR software. During usage of Paychex systems and services, some clients will report having issues. To provide better service and prevent issues, Paychex is looking for the underlying causes. Paychex has gathered a sample containing one month of client transactions, and marked whether or not each client has indicated an issue.

Objective 1: Predict whether or not a client will have an issue 

Objective 2: Through the prediction, identify root causes and problematic events, and provide insight into what can be improved



As requested by Paychex, the data for this project is not allowed to be posted online.
The Powerpoint file(FinalPresentation1127.pptx) contains the slides we used for final presentation. Key findings and models are summarized.

# files:

FinalPresentation1127.pptx ---- Final presentation slides

Load original data and create features.ipynb ---- Load data, process and create behavior features

paychex_Profile related features.ipynb ---- Load datam process and create profile related features

Cluster.ipynb ---- Apply KNN to behavior features

using model for feature selection.ipynb	 ---- Get feature importance using XGBoost to select useful features

xgboost.ipynb ---- Try out XGBoost model

xgboost modeling with proper upsampling.ipynb ---- To avoid information leaks, we first split the dataset into a training dataset and test dataset, then upsample in the training set and keep the test set at the original size

