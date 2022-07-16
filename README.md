# Bike-Sharing-Demand-Prediction-
As a convenient, economical, and eco-friendly travel mode, bike-sharing greatly improved urban
mobility. However, it is often very difficult to achieve a balanced utilization of shared bikes due to the
asymmetric user demand distribution and the insufficient numbers of shared bikes, docks, or parking
areas. If we can predict the short-run bike-sharing demand, it will help operating agencies rebalance

bike-sharing systems in a timely and efficient way.
We have performed following steps while building the model:

   Exploratory data analysis
  
   Feature Engineering
  
   Training the model and Hyperparameter tuning
  
   Evaluating the ML model performance
  
   Conclusions

Exploratory data analysis:
In this step performed data preparation after that we have cleaned the data. We have
performed Univariate, Bivariate, and multivariate analysis and we drove some conclusions

Featuring Engineering:
In Feature engineering we have checked for multicollinearity are removed the features with
high correlation. Some of the features are skewed so we performed LOG and Square root
transformations. To convert categorical feature into numerical we performed one hot encoding on
categorical feature.

Training the model and Hyperparameter tuning:
In this step, we applied different machine learning algorithms to train the model and predict
the bike sharing demand at a given hour for a given set of environmental conditions. Also, we
performed hyperparameter tuning, to find out the best set parameters for the given algorithm.

Evaluating the ML model performance:
After training the different models with the data it is important to evaluate the model
performance using different metrics so that we can choose the best model for predicting the
bike sharing demand. So, we evaluated the model based on metrics like Mean Squared Error
(MSE) and R2 score to compare the models.

Conclusions:
After trying different models and with hyperparameter tuning we say that XG Boost
has highest R2 score, so we can you XG boost for predictions.
