# Applied Data Analysis Final Project - Source Code

### Description of Files Included:

* MHEALTHDATASET.zip - original data files. Sourced from http://archive.ics.uci.edu/ml/datasets/mhealth+dataset
* mhealth_full.csv - combined csv file of experiment data. The data includes 21 attributes as well as subject and activity labels
* Data Sourcing.ipynb (36 lines) - jupyter notebook file used for concatenating individual subject files into single csv
* Data Exploration & Visualization.ipynb (198 lines) - jupyter notebook file used for exploratory data analysis and creating visualizations
* Modeling.ipynb (252 lines) - primary jupyter notebook used for data preprocessing, training/tuning models, validating, and evaluating classification performance
* CNNModeling.ipynb (203 lines) - google colab notebook used for building/validating CNN models for classification problem

### Other Notes:

* I ran the CNNModeling file in Google Colab GPU environment in order to obtain better performance training the CNNs. Mileage may vary for running locally
* Referenced articles / sources are included in code cell comments