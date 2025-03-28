# credit-risk-classification

In this module we were asked to create a supervised ML model to predict healthy and high-risk loan candidates.  

First, we read the provided data into our notebook (Google Collab) and then split the data into training and testing data using the Train-Test Split from SKLearn.  

Next, using the logistic regression function, we created a model using the training data.  After fitting the model to the data, we then predicted healthy and high-risk loan candidates.  

Using an Accuracy Score, Confusion Matrix and a Classification Report, we evaluated the model's performance. 

- With an accuracy score of 0.96 (96%)  the model is pretty accurate.  This means that 96% of the time the model is correctly predicting the binary output of loan data.

- According to the confusion Matrix,  there are a large number of true negatives, a moderate number of false positives, a small number of false negatives, and a moderate amount of true positives.  This tells us that our model is accurate at predicting the correct output, but does sometimes not get it right.

- The classification report tells us several things about the model's performance:
	- For the Precision, it tells us how many of the sample are in each class (0 or 1)
	- For the Recall, the report tells how many predictions the model got right for a certain class 
 	(0 or 1).  In this case, the Recall is good.  99% correct for the 0's and 94% for the 1's. 
	- The F1 Score Balances the mean of the precision and recall.  For predicting 0's (Healthy Loans), 	the model is good at 1.00.  For predicting high risk loans, the model is still fairly good at 89%.
	
On the whole, I would recommend this model to a company.  Using the data collected and read into the model provides a fairly good idea of what factors play into what would be a healthy loan v. a high risk loan.  No model is accurate and real life rarely comes without the unexpected, so no model is going to do this perfectly.  Having a model that does it well can be profitable for businesses.  As data grows and the model is retrained, its accuracy and recall will most likely improve.   

