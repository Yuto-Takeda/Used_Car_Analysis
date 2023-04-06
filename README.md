# Overview

Here, I build a model to predict the prices of used cars in California state. I extracted and analyzed only the data from Kaggle that pertains to used cars in California state.

https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data


### Purpose
I am currently considering purchasing a used car, and to determine whether the displayed price is reasonable, I want to create a used car pricing model to reveal the factors that affect the price.

### Result
I used Random Forest for predicting the price. The MAPE was 0.33, R^2 was 0.73, and RMSE was 5268.12. 
The result of the feature importance is as follows. We can describe that "odometer" was the most important variable to predict the used car price, followed by "year", which the car was manufactured, and "cylinders". The impact strength of "manufacturer", which is the brand of the car was smaller than those variables.

<img src="https://user-images.githubusercontent.com/79394001/230261532-d68d6755-79fa-4f7c-a207-bc9ec60e2dc9.png" width="500">
