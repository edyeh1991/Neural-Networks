# Neural-Networks
In this challenge, you’ll have to build your own machine learning model that will be able to predict the success of a venture paid by Alphabet soup. Your trained model will be used to determine the future decisions of the company—only those projects likely to be a success will receive any future funding from Alphabet Soup.

# Objectives
Import, analyze, clean, and preprocess a “real-world” classification dataset.
Select, design, and train a binary classification model of your choosing.
Optimize model training and input data to achieve desired model performance.

# Write up analysis
I ended up taking the 117 input features and using 2 layers, one with approximately half the amount of input featers in neurons (50) and the second with half that that (25).
I was barely able to achieve the target model performance of 75% accuracy. My accuracy of 76.8% was only achieved by cleaning up each company's ask amt by binning them into greater than or less than 5000. Most companies ask amount was $5000 with 25398 out of 34299 asking for that amount. The rest was considered unique ask amounts.
If I were to implement a different model I would look into the random forest model. Random forest models are robust and scalable. They can easily handle outliers and nonlinear data and work well to handle tabular data
