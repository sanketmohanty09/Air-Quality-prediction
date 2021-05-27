# Air-Quality-prediction
1-Data Collection: (execute main-aqi.py)
For this step, I have written a web scrapper that scraps en.tutiempo.net for climate data from 2013 to 2015 and creates a HTML file for each month.

2-Data Cleaning: (execute main-aqi.py)
The CSV file created in step 1 was cleaned to remove null values and improper data. A new resultant CSV file was created.

3-Feature Engineering and Model Creation: (execute individual jupyter notebooks)
Tried various algorithms, like Linear Regression, Lasso and Ridge Regression, Decision Tree Regressor, ANN Regressor, Random Forest Regressor, XGBoost Regressor.
Random Forest and ANN gave best performance. 
