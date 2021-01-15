# Credit-Card-Default-Prediction-KNN-and-Tree-based-classifier-
Data :https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients

Goals:
Our dataset is from the UCI machine learning repository consisting of 24 attributes and 30,000 different rows. We will likely use each attribute in our model.
All values are already integers. The class label is One-hotted already but we will likely have to one-hot other labels even though they are already integers. 
For example, gender is 1 for male and 2 for female. The data overview states there is no missing data but we will have to check that there are no mistakes still. 
The data is already pre-processed.

Motivation:
If we can come up with an accurate model, then we would be able to apply this model to real world statistics. If we were given completely new statistics on a 
client not in this model we should still be able to know whether or not the new client is likely to default. If we were working for a credit card company we 
could easily figure out if it is smart to give certain clients credit cards with the model we will use.

Goals:
For our project we will be predicting credit card default using tree based and K Nearest Neighbors classifiers. Our dataset has information about many different 
clients. The information about the clients include  Gender, Education, Marital Status, Age, Amount of given credit, History of past payment, Amount of bill 
statement, Amount of Previous payment, and default payment. The default payment is our class label. It states whether or not the client defaulted on their credit 
card statement. We can use the rest of the data to predict if a client will default.

Model:
We are using Tree based classifiers and k nearest neighbors to try and predict Credit Card Defaults. We will use both so we can see which one is more accurate. 
The K Nearest Neighbors accuracy was 81%. The Tree Decision Classifier accuracy was 82%. 

Conclusion:
Overall, both models had very similar accuracy. They were both around 82%. You could use whichever model you prefer to predict accuracy. You could use both models 
as well and if they came up with the same prediction for a client there would be greater accuracy. This model would definitely help someone know whether or not a 
client will default. They would also  need to use some other information to help them predict default or not. They could not only rely on the two models we used.


