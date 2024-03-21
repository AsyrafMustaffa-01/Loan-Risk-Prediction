# Loan Risk Prediction

The objective for this project is to build a Exploratory Data Analysis for the load data, find out some trends and insight.
Then later on will do 2 class clustering based on the features. This is to assume that there are "Bad Loan" and "Good Loan".

then test the clustering if it meaningful and distinguisable, using K-Proto Cluster. To test either the cluster can be classified, 
I used LightGBM classifier to see if it can easily predict the cluster. 

For the sake of experimenting, I would assume that the loan that been approved is a good loan. after doing clustering, the percentage 
where the clustering class is the same as the loan approval is about 60%. Let's say my KPI is must be more than 50% if i want my hypothesis to be accepted,
with 60% of the result is the same as the approvals status, I would say my hypothesis stands correct. 

now that we have seen the bad and good loans, nwo we try to do prediction of those good and bad loan for the loaner, using the same algorithm, LightGBM. 
This is because LightGBM can use categorical features for its model training. The Trained model get accuracy scores of 98%, which shows that the model can easily predict the cluster class. 
