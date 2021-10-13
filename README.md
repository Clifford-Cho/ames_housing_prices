# Analysis of Housing Prices in Ames, Iowa

## Problem Statement

Real estate is a stressful process for buyers due to the pressure of making the "right" choice. The most important factor in a sale is the bottom line, but properly pricing a house is difficult, especially for those unfamiliar with real estate. One way this can be done is by identifying what special factors best explain a house's value and seeing how these factors predict sale price. This can be useful for both sellers trying to price their property and buyers trying to make a knowledgeable investment.

This project will look at data regarding the Ames, Iowa housing market to give insight on what features heavily affect sale price. This will be achieved by creating a linear regression model on the given features.

---

## Background

The value of a house is difficult to calculate due to the sheer number of features inherent. This is made doubly complex by customer preferences and inquiries into specific details. The Ames housing training dataset contains over 80 columns of data for over 2000 houses. These columns are divided into numerical and categorical data. The indepth explanation and categories for each column can be found here.

With this is mind, the project will focus on identifying primary aspects of the house and features to explain them. These include:

    Area - Indoor and outdoor
    Quality - Materials and reported quality
    Location - Neighborhood and condition relative to markers
    Details - Time of construction/remodeling, house style, etc.

For features concerned with quality, multiple types of scales are present:

    1-10 scale - Very Poor to Very Excellent
    6 category scale - None, Poor, Fair, Average, Good, Excellent
    5+ category scale - Some features have unique categories similar to the above style but with different wording.

Each of these sections will then be pruned based on preliminary correlation data.

---

## Conclusions/Recommendations

This project was able to identify key factors in sale pricing. Overfitting was prominent along all numerical features. Location features predicted sale price surprisingly well. With the categorical features, the train and test scores were closer. Final predictive score was +80% and a RMSE score of ~31.5k was shown.

Based on the numerical data, the two main factors were house quality and house space. This is to be expected as the quantity and quality of a good is usually the most important in a sale. However, it is shown that the space outside of the house, such as lot area, were significantly less of a factor in determining the price. Another factor that was important were house factors such as the number of bathrooms, bedrooms, and fireplaces. 

In order to get the highest sale price in a house, quality should be highly focused on. Visuals highlighting the relationship between quality and sale price has shown that price can vary hundreds of thousands of dollars based on the quality of the house. For anyone looking to improve the value of their house, I would highly recommend raising the quality and condition of the house.