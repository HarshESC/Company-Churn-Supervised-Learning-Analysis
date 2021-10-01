Summary:

A telecomm company would like to predict their churn rate in order to make decisions for the future growth of their company.  

Telecom companies can suffer from voluntary churn. They spend thousands of dollars just to acquire a new customer.  But, when that customer leaves, the company not only loses the future revenue from that customer, but also the resources spent to acquire that customer.  As a result, it causes a loss in profits.

The churn rate helps determine whether customers tend to stay with the company.  

For example if a company has 25% churn rate then the average customer lifetime is 4 years; similarly a company with a churn rate of 50%, has an average customer lifetime of 2 years. It is estimated that 75 percent of the 17 to 20 million subscribers signing up with a new wireless carrier every year are coming from another wireless provider, which means they are churners. 

In this analysis, we will be exploring the rate at which customers churn using a series of Machine Learning Algorithms.  I will be using two techniques, Select K Best and Principal Component Analysis (PCA) in order to pick the best features that help predict the churn rate.  

Results:
To predict whether or not a customer will churn from a company or not, I would use the Random Forest model with the Select K Best Features.  

However, the other models were not any less accurate than Random Forest as they were quite close when it came to the results.  

It makes sense that Random Forest would yield such high results as their ability to limit overfitting without substantially increasing error due to bias is why they are such powerful models.  The only shortcoming would be that it seems to favor Non-Churners over Churners just do to there being significantly more Non-Churners as a result.  

In order to improve the model, more data is needed.  Possibility more recent data with more of an even distribution of Churners and Non-Churners.  Perhaps more insight into the company itself and what service the customers sign up for would make it easier to reason why a customer would decide to churn.

To find more features, I would ask the company to provide any more client information they have. Some additional questions to ask about the client include "what services are you providing," or "what departments tend to have more churners" so we can see which faction of the companies seems to have significantly higher churners.
