# stolen-cycle-prediction
<span style="font-size: 30px;">Overview</span>

This project aims to predict the likelihood of a bicycle getting stolen on the IIT Jodhpur campus. We use a machine learning classification algorithm, specifically logistic regression, to make these predictions. The dataset includes various features related to the bicycles, such as whether they are gear or non-gear, mountain or road cycles, the cycle company, and the price.

Dataset
The dataset used for this project is collected from the IIT Jodhpur campus and contains the following features:

Gear/Non-Gear(e.g., multiple-speed options) or is non-gear (single-speed), Mountain/Road Cycle, Cycle Company, Price: The price of the bicycle. Cycle Stolen (Target Variable)

Methodology
Data Collection: The data was collected from the IIT Jodhpur campus, including information about the different bicycles available.
Data Preprocessing: The collected data was cleaned and preprocessed to handle missing values, outliers, and format the data for machine learning.
Feature Engineering: We extracted relevant features from the dataset, such as gear type, cycle type, and company, to use in our prediction model.
Model Training: We used logistic regression, a popular classification algorithm, to train our prediction model. This algorithm is suitable for binary classification tasks like predicting whether a bicycle will be stolen or not.
Model Evaluation: The model's performance was evaluated using various metrics such as accuracy, precision, recall, and F1-score to assess its predictive capabilities.
Prediction: Once the model was trained and evaluated, it was used to make predictions on new or unseen data.

Conclusion
This project demonstrates the application of machine learning, specifically logistic regression, to predict the likelihood of a bicycle getting stolen on the IIT Jodhpur campus. By considering various bicycle features, we can provide valuable insights and warnings to help reduce bicycle theft incidents.
