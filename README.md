# Fraud_Detection

# BUSINESS UNDERSTANDING
What is the company?

Blocker Fraud Company
What is its business model?

Blocker Fraud Company is a company specialized in the detection of fraud in financial transactions made through mobile devices. The company has a service called "Blocker Fraud" which guarantees the blocking of fraudulent transactions.
What is the business problem the company is facing?

Blocker Fraud Company is expanding in Brazil and, to find new customers more quickly, it has adopted a very aggressive strategy. The strategy works as follows:

    The company will receive 25% of each transaction value that was correctly detected as fraud.

    The company will receive 5% of each transaction value that was detected as a fraud despite being legitimate.

    The company will return 100% of each transaction value that was detected as legitimate despite being a fraud.

In other words, the company takes the risk of failing to detect fraud and earns money when correctly detecting fraud.

For the client, it is an excellent deal to hire Blocker Fraud Company. Although the fee charged is very high when fraud is correctly detected (25%), the hiring company reduces its costs of detecting fraudulent transactions and errors in the anti-fraud service are under the hired company responsibility.

For the Blocker Fraud company, it will attract many customers with the guaranteed return in the event of a failure to detect customer fraud. Besides, Blocker Fraud only depends on the precision and accuracy of its model: the more accurate the prediction, the higher the company's revenue. However, in the case of low accuracy, the company could have a high loss.
PROBLEM UNDERSTANDING
What is the business solution that this project has to deliver?

As a data science consultant, you have to create a highly precise and accurate model for detecting fraud in mobile transactions.

At the end of your consultancy, you need to provide the CEO of Blocker Fraud Company a model in production that will be accessed via API, meaning that clients will send their transactions via API for your model to classify as fraudulent or legitimate.

In addition, you will need to submit a report with the model's performance and results about the profit and loss that the company will make using the model you created. Your report should contain the answers to the following questions:

    What is the precision and accuracy of the model?
    What is the expected revenue for the cases where the model succeed in detecting fraud?
    What is the expected loss by the company for the cases where the model fails to detect fraud?
    What is the expected profit for the Blocker Fraud Company if it uses the model for all mobile transactions?

References:

https://sejaumdatascientist.com/crie-uma-solucao-para-fraudes-em-transacoes-financeiras-usando-machine-learning/

https://www.kaggle.com/ntnu-testimon/paysim1
BUSINESS ASSUMPTIONS

-> The currency of all transactions is in the Brazilian real (assumption needed for revenue, loss and profit estimations).

-> Revenue, loss and profit estimations were based on the difference between the origin balance before and after the transaction, that is, new_balance_orig - old_balance_orig.
