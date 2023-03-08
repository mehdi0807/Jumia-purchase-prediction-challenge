# Jumia-purchase-prediction-challenge
The presented Github repository offers a comprehensive solution to the challenge posed by Jumia in the Haick 2023 Datathon, which was hosted by the `School of AI Algiers`.<br>
The primary objective of the task was to predict the purchasing behavior of Jumia's customer base for the next four months, using a dataset that only covered three months' worth of information.<br><br>

One of the main challenges was that the train data was not labeled. Instead, orders from customers in the previous seven months were available. Therefore, the data had to be redesigned to frame it as a binary classification problem.<br><br>

To tackle this issue, my solution adopted a strategy of treating the purchase history data for the months of (7, 8, and 9) as the training set and the subsequent months of (10, 11, 12, and 1) as the target for modeling.<br>
The approach enabled the development of an effective machine learning model to predict future purchasing patterns.
