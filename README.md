# Predicting Human Activity from Wearable Sensor Data - Source Code

### Project Description:

The aim of this project was to accurately classify sensor input data from the MHEALTH dataset into one of a number of physical activity classes. After performing exploratory data analysis, creating relevant visualizations, and preprocessing the data, I proceeded to train and tune a range of classification models on the data in order to achieve the best results. The models I utilized included Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Random Forest ensemble, and Convolutional Neural Network (CNN). I compare the performance of these models based on common classification metrics, especially cross-validated accuracy score. Most of the models were able to achieve my goal of over 90% accuracy, with the CNN achieving the best performance overall, followed by Random Forest and SVM. Further model validations and implementing proven strategies on time series data would likely benefit this analysis in the future.

### Description of Files Included:

* MHEALTHDATASET.zip - original data files. Sourced from http://archive.ics.uci.edu/ml/datasets/mhealth+dataset
* Data Sourcing.ipynb (36 lines) - jupyter notebook used for concatenating individual subject files into single csv
* Data Exploration & Visualization.ipynb (198 lines) - jupyter notebook used for exploratory data analysis and creating visualizations
* Modeling.ipynb (252 lines) - primary jupyter notebook used for data preprocessing, training/tuning models, validating, and evaluating classification performance
* CNNModeling.ipynb (203 lines) - google colab notebook used for building/validating CNN models for classification problem

### Notes:

* The CNNModeling file ran in Google Colab GPU environment in order to obtain better performance training the CNNs. Mileage may vary for running locally
* Referenced articles / sources are included in code cell comments
* Associated project paper available upon request!
