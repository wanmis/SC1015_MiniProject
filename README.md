# SC1015_MiniProject
## About
This is SC1015 Mini Project done by B135,Group 8.
<br>Our project is on predicting rental price of a AirBnb listing in Singapore based on its attributes.
<br><img width="720" alt="Image" src="https://user-images.githubusercontent.com/128026488/233777968-d10055f9-a304-4d1a-bf8d-0a483ffd899f.png">

Order of codes/files:
1. [Cleaning](https://github.com/wanmis/SC1015_MiniProject/blob/main/Cleaning.ipynb)
3. [EDA](https://github.com/wanmis/SC1015_MiniProject/blob/main/EDA.ipynb)
4. [Linear Regression](https://github.com/wanmis/SC1015_MiniProject/blob/main/Linear%20Regression.ipynb)
5. [K-Nearest Neighbours](https://github.com/wanmis/SC1015_MiniProject/blob/main/KNN.ipynb)
6. [Random Forest Regression](https://github.com/wanmis/SC1015_MiniProject/blob/main/Random%20forest%20Regression.ipynb)
7. [XGBoost](https://github.com/wanmis/SC1015_MiniProject/blob/main/XGBoost.ipynb)
8. [Slides](https://github.com/wanmis/SC1015_MiniProject/blob/main/SC1015%20ProjectSlides.pdf)

## Background Info:
Airbnb has become an increasingly popular choice for travelers around the world.
It can be challenging to determine the optimal price for a listing, especially given the many variables at play.
Price of a listing is determined by a number of factors, such as the property's location, the amenities provided, and even the time of year. 
Moreover, these factors interact with each other in complex ways, making it difficult to predict the best price for a listing.

## Data Source: 
- [Singapore AirBnb 2019](https://www.kaggle.com/datasets/jojoker/singapore-airbnb)

## Problem Definition:
- Can we predict the rental price of a listing with its attributes?
- Which model among the ones we selected would be the best to predict it?

## Model Used:
- Multi Variate Linear Regression
- K-Nearest Neighbours
- Random Forest Regression
- XGBoost

## Conclusion
- Random Forest Regression is the best amongst the other from the errors
- Application of new cleaning and regression tools as well as hypertuning
- Able to predict price from regression techinques used in this project

## Data Insights
- Explore other regression means such as Support Vector Machine
- Tap in to other relevant data attributes in context of Singapore's housing to strengthen prediction accuracy 

## Contributors
- Tong Shao Wen (Data Cleaning, Data Exploring & Visualization, Random Forest, KNN)
- Wan Muhammad Ismail (Data Cleaning, Data Exploring & Visualization, Linear Regression, XGBoost)

## References
- https://www.analyticsvidhya.com/blog/2022/11/hyperparameter-tuning-using-randomized-search/
- https://www.analyticsvidhya.com/blog/2021/06/tune-hyperparameters-with-gridsearchcv/
- https://www.analyticsvidhya.com/blog/2020/03/one-hot-encoding-vs-label-encoding-using-scikit-learn/
- https://www.analyticsvidhya.com/blog/2016/03/complete-guide-parameter-tuning-xgboost-with-codes-python/
- https://www.analyticsvidhya.com/blog/2021/06/understanding-random-forest/
