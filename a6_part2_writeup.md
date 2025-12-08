# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Most Important: Square Feet
2. Bedrooms
3. Bathrooms
4. Least Important:Age 

**Explanation:**
Square Feet is the most linear while every other factor doesn't seem linear at all therefore ranking them 2,3,4 although the positions can be interchangable for these 3 factors other than sqft



---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:**Square Feet 
Each additional square feet increases the price by 121.11 dollars

**Feature 2:**Bedrooms
Each additional bedroom increases the price by 6648.97 dollars

---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**
The models R^2 score was 99.36% and it tells us that our model has a 99.36% variance coefficient, meaning that this perecntage is how well our model depicts the acctual data. However higher or lower variance doesn't mean the graph is perfect, meaning there is still somewhere we can improve our model in predicting better data.



---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**Quality of the surrounding neighborhood


**Why it would help:**
The quality of the surrounding people you live with determines housing prices because houses in shadier places tend to be cheaper than a house in a nicer area as people associate safety and better living conditions with nicer areas and vice versa.

**Feature 2:**Population of the city


**Why it would help:**
The population of a city contributes to the demand for housing as more people in a city means more people requiring a place to live meaning that the more people living in a city the higher the demand meaning there is a rise in price because of supply and demand.

---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**
No because all of these variables are way out of our training data range meaning that the model wouldn't be able to accurately predict the actual data of these variables.

