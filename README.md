# Mobile-Price-Range-Prediction
The following code is a completely functional Mobile-Price range predictor which helps estimate the price range between 4 categories of phone prices from low level price range to premium level price range with a standard dataset. Gives you the idea of using various ways to optimize the code and it's output by using number of methods at each step of training the model. Achieved an accuracy of 90.2%.

# RFE
Stands for Recursive Feature Extraction which extracts (in this case are 6) the best parameters to be considered while training our model and thus saving ample amount of time in the process and easier understanding. The code snippet has the RFE method in commented part at [10] in the notebook. The user needs to train the model upto cell [10] and then retrain it with RFE modified values which after their identification like I have done by exclusively mentioning the best 6 parameters.

# GridSearchCV
Training the model to loop through predefined hyperparameters and to fit your estimator (model) on your training set.
