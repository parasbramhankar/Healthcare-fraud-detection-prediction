# healthcare-provider-fraud-detection

## What is Healthcare Fraud?
Health care fraud is a type of white-collar crime that involves the filing of dishonest health care claims to turn a profit. Healthcare fraud can affect anyone from healthcare funds to fund members like us. It happens when someone like a healthcare provider or an individual provides false information or withholds the information to get a financial benefit.
Types of frauds by providers are:
a. Billing for services that were not provided.
b. Duplicate submission of a claim for the same service.
c. Misrepresenting the service provided.
d. Charging for a more complex or expensive service than was provided.
e. Billing for a covered service when the service provided was not covered.

## Business Problem
This case study aims to "predict the potentially fraudulent providers" based on the claims filed by them. Along with this, we will also discover important features helpful in detecting the behaviour of potentially fraudulent providers. Further, we will study fraudulent patterns in the provider's claims to understand the future behaviour of providers.
## Machine Learning problem
We can project the above problem to a binary classification problem to find whether the provider is fraud or non-fraud. Using the claim details submitted by that provider.
## Business Constraints
The cost of misclassification is very high. As false positives and false negatives can affect very much.
Model interpretability is more important as we want to know why a healthcare provider is particularly fraudulent or non-fraudulent.
We have no latency issue or time as we have 15–30 days to process the claim.

### For further reading please visit this blog:-

### Deployment of model on Heroku:
https://healthcare-fraud-api.herokuapp.com/index
```