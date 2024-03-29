# Bike Sharing Demand Prediction
<h3 align="center"> AlmaBetter Verified Project - <a href="https://www.almabetter.com/"> AlmaBetter <img width="664" alt="image_19400_1_5042248765" src="https://user-images.githubusercontent.com/121742479/229417541-62236170-e834-4584-a0f6-d810f287772e.png"></a> </h3>
Currently rental bikes are introduced in many urban cities for the enhancement of mobility comfort. The purpose of this movement is to modernize cities and encourage people to head to a green world. Let's take the examples of Paris in 2007, where "velibs" were introduced and Amsterdam, where there are more bikes than cars. The goal is to facilitate the commute in the Seoul and reduce the amount of cars and the pollution. Indeed, the development of the way to commute reduced the use of cars to go to work and visit the city.

It is important to make the rental bike available and accessible to the public, as it provides many alternatives to commuters in metropolises. There are a lot of advantages to bike rents, it is convenient because it permits people not to keep the bike all day long, whether it is at work or at school. Furthermore it is the healthiest way to travel and it has many environmental benefits.

The studied dataset contains weather information which are the features (Temperature, Humidity, Wind speed, Visibility, Dew point, Solar radiation, Snowfall, Rainfall), the target is the number of bikes rented per hour and date information. The dataset presents the company's data between December the 1st of 2017 and finishes one year later.

# How many bikes are rented per hour in function of weather conditions ???
The goal of the company Seoul Bike is providing the city with a stable supply of rental bikes. It becomes a major concern to keep user satisfied. The crucial part is the prediction of bike count rents at each hour for a stable supply of rental bikes. We can suppose that this study could be reported to the company 'Seoul Bikes'. We think it could help them knowing if yes or not they have to supply bikes stations in the city, in order to keep a good satisfaction of the customers.

You can find the dataset necessary for the analysis on following link : https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand#

# Conclusion
• The Rented Bike Count has been increased from 2017 to 2018.

• No overfitting is seen.

• XGBoost Regressor gives the highest R2 score of 96.6% for Train Set and 89.4% for Test set.

• Feature Importance value for Random Forest, Gradient Boost, and XGBoost are different.
