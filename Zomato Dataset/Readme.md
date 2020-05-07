# Zomato Dataset Delivery Time estimation

We have Zomato's Dataset including variables like Location, Cuisines, Minimum order, Rating, etc.
Our objective is to predict Delivery Time. All the variables mentioned in the code are self explanatory.

Steps used - 
A lot pre-processing in the data was involved like 
  1. Some varibales like transaction amount had ₹ symbol which infact was a string had to be converted to numeric
  2. The address variables had to be simplified to one single location. We extracted city name from the entire address.
  3. Identifying the significant variables
  4. Treating the missing values
  5. Cuisines ordered had to be converted to count of cuisines ordered for simplification

Visualization - 
Visualizing which city had max no. of orders
Visualizing different delivery times estimates like within 30 mins or so and how many times were different orders delievered in that time 

Building various Regression and Classification and spontaneously applying various methods and changing our methods to predict based on what we observe and conclude while performing different algorithms

Algorithms used were - OLS, SVM, Decision Tree, Random Forest
