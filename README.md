# Acea-Water-Challenge

In this project I used the dataset by Acea about the Doganella Aquifer in Italy and predicted the depth to groundwater by using a Random Forest. The notebook contains my analysis and implementation of my Random Forest model. It is divided into sections for data exploration, data cleaning, statistical tests, feature engineering, and modeling.

# Packages Used

- seaborn==0.10.1
- numpy==1.18.5
- pandas==1.0.5
- matplotlib==3.2.2
- statsmodels==0.11.1
- scikit_learn==0.24.1

# Approach

1) Explored the data to find any patterns or points of interest.
2) Cleaned the data using interpolation and selecting a time range which would yield the most accurate entries. 
3) Tested for stationarity and trend by using the ADF and KPSS statistical tests.
4) Implemented walk-forward validation with the Random Forest.

# Results

![depth_forecast](https://user-images.githubusercontent.com/51835357/115314181-90342680-a129-11eb-8a80-7c9455062076.png)
