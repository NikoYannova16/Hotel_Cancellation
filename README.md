# Hotel Cancellation
## Problem Framing

The business objective to be achieved is to get a prediction system that can be used to find out which customers will cancel orders and the factors that occur.

The output to be generated is a prediction of the booking status of a customer. If you can predict which customer will cancel the room, you can help the marketing team to prepare a marketing strategy in an effort to avoid income loss that can harm the hotel.

The machine learning approach that will be used is supervised learning in the form of classification problems. The system that you want to work on will predict customers who have the possibility of canceling room orders.

The performance measure that will be used to help determine the quality of the final result is accuracy to determine the percentage of prediction success. Recall and precision will also be used to find out where the prediction error is.

The risk that most likely will occur when this system is used is the occurrence of income loss for hotels because there is a possibility for this system to make prediction errors in predicting customers and not precisely determining the factors that influence this so it will be difficult to determine the right marketing strategy for such cases like this.

## Modeling

I used supervised learning, namely logistic regression as the model with the best results after doing several experiments using other models. Apart from having better results than other models, it is also relatively inexpensive in terms of computing power. At this stage I did two stages, first trying to train on the training set which was then applied to the test set.

## Evaluation

I use an important feature to find out the factors or causes of customers canceling their room bookings. Business users can use the prediction results to better understand customers, and to carry out better services or promotions to customers so as to reduce room cancellations made by customers which of course causes losses to the hotel in terms of revenue and reputation.
