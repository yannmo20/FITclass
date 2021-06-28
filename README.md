## FITclass &mdash; Classifying Fitness Time Series Data

In this notebook, we will explore a dataset with over **160000 tracked fitness workouts** and will try to use them to perform a **multiclass classification into sports types**. The main features will be time series logs of heart rate and speed (calculated e.g. via GPS logs). The notebook consists of all crucial parts for the project steps (dataset exploration/analysis, classification training and evaluation).

Adiitionally, some functionalities are provided in a separate `FITclass_utils.ipynb` notebook, which contains a DataExplorer for time series visualization and plotting correlation plots of the given fitness samples. The notebook `FITclass_CreateMeanSpeedData.ipynb` contains a script to create an additional mean_speed data column using the GPS coordinate time series -- this was neccessary as the original dataset had lots of missing values for the speed time series column.

This notebook was created using the Databricks Community Edition. Therefore, the plots underneath were directly visualized by the databricks functionalities of PySpark dataframes.

This project was created as part of the lecture _Big Data Computing_, summer term 2020/2021 at Sapienza University of Rome. 
Yannick Moell, 2021