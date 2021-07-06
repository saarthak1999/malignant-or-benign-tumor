# Project Overview
This project focuses in investigating the probability of predicting the chances of breast cancer from the given characteristics of breast mass computed from dataset. This project will examine the data available and attempt to predict the possibility of a breast cancer. To achieve this goal, the following steps are identified: • Download the breast cancer data from Kaggle website(dataset available in my repository)• Familiarize with the data by looking at its shape, the relations between variables, their possible correlations, and other attributes of the dataset. • Preprocess data if needed • Split the data into testing and training samples • Employ various classifiers (KNN, Decision trees, Logistic Regression, Naive-Bayes, SVC and Random Forest classifier).
### Accuracy
Suppor vector Classifier - 92.98% <br/>
Logistic Regression - 96.48% <br/>
K-Nearest Neighbor Classifier - 92.98% <br/>
Naive Bayes Classifier - 94.73% <br/>
Decision Tree Classifier - 95.61% <br/>
Random Forest Classifier - 96.49% <br/>
## Result
Random Forest Classifier predicts with the best accuracy among all. So we save this model in a pickle file and deploys using flask with Heroku.

