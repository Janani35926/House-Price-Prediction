# House Price Prediction Using Linear Regression
## Project Overview
This project demonstrates a machine learning approach to predicting house prices using a Linear Regression model. The project involves performing Exploratory Data Analysis (EDA), encoding categorical features, and implementing cross-validation to ensure model consistency and prevent overfitting.

The project was implemented using Jupyter Notebook, which facilitated interactive coding and data visualization.
## Importing libraries
![im_1](https://github.com/user-attachments/assets/efdefefd-07c8-4cac-8bf1-12d5e52a0dc5)
## EDA- exploratory data analysis
The **KDE plot** gives a smoothed curve representing the underlying distribution of data, making it easier to identify trends, peaks, and valleys.
It provides a clearer sense of where data points are concentrated compared to histograms.
![im_4](https://github.com/user-attachments/assets/5461a1e1-14ef-4f82-882c-7e1d946959c4)
![im_5](https://github.com/user-attachments/assets/13b95830-2698-469e-bcd4-b68343a211d4)
Analyzing the columns which influences the target value through bar plot.
Encoding catagorical values to numerical by **MEstimator.**
![im_6](https://github.com/user-attachments/assets/03937600-2cb4-469f-94ea-e0edfa020e26)
![im_7](https://github.com/user-attachments/assets/990a91d4-3c5c-490d-a4bf-4d1f7587d636)
![im_8](https://github.com/user-attachments/assets/1873dd4b-4716-483a-9cfe-67330f5ecbf5)
## Model fitting
After preprocessing the data, the linear regression model is fitted to the training set, and the target values are predicted. To prevent overfitting and ensure model consistency, **cross_val_score** is applied to evaluate the performance of the model across different data folds.
![im_9](https://github.com/user-attachments/assets/e1910237-b63b-46f5-9191-d1336258c4cb)
![im_10](https://github.com/user-attachments/assets/c4e2ebd2-6cec-4b08-b60c-03c32ae766ac)


