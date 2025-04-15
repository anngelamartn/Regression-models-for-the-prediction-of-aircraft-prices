# TFM - A MACHINE LEARNING APPROACH FOR THE PREDICTION OF AIRCRAFT VALUE DEPRECIATION

This repository includes the scripts and resources developed for the implementation of a regression machine learning capable of predicting aircraft prices. This work has been developed for the
composition of the final Master Thesis of the author, associated with Universidad Europea de Madrid.


## 📁 Find below the structure of the repository

- `RawData/` - Folder including the raw data that is used for the training of the models
          `aircraft_data.csv` - File containing a series of historical aircraft records, including both their cost and a series of features describing them. 
- `Data-Preprocessing/` - Folder including all the scripts developed for the processing of raw data, and its adjustment to models.
          `DataCleaning.ipynb/` - General data cleaning and structurization of raw data
          `CleanedData.csv/` - Data version resulting from previous script
          `OutliersTreatment.ipynb/` - Treatment of data outliers
          `OutliersTreated.csv/` - Data version resulting from previous script
          `MissingDataTreatment.ipynb/` - Treatment of missing data
          `MissingDataTreated.csv/` - Data version resulting from previous script
          `EDA.ipynb/` - Univariate and bivariate exploratory data analysis
          `CorrelationMatrix.ipynb/` - Generation of correlation matrix
          `FeatureSelected.csv/` - Data after its preprocessing, used for the training of the models
- `Models/` - Folder including the development of different regression algorithms, evaluating their performance and checking their validation
          `FeatureSelected.csv/` - Data after its preprocessing, used for the training of the models
          `LinearRegression.ipynb/` - Linear regression models (standard, Lasso, Ridge, Elastic Net)
          `Tree-Based.ipynb/` - Tree-Based models (Decision Tree, Random Forest and Gradient Boosting)
          `KNN.ipynb/` - KNN model
          `SVR.ipynb/` - SVR model
          `ANN.ipynb/` - ANN model
