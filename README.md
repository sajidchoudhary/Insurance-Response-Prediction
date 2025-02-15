# Machine Learning Based Classification Problem

## Problem Statement:

![Vehicle-Insurance](https://user-images.githubusercontent.com/66259814/103484701-e8634900-4e16-11eb-8549-adbd2c70609d.png)

client is an Insurance company that has provided Health Insurance to its customers now they need help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company. An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee.
Just like medical insurance, there is vehicle insurance where every year customer needs to pay a premium of certain amount to insurance provider company so that in case of unfortunate accident by the vehicle, the insurance provider company will provide a compensation (called ‘sum assured’) to the customer. Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.
Now, in order to predict, whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.


## Data Description:

1-id(Unique ID for the customer) ,2-Gender(Gender of the customer),3-Age(Age of the customer), 4-Driving_License(0 : Customer does not have DL, 1 : Customer already has DL),5-
Region_Code(Unique code for the region of the customer),6-Previously_Insured(1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance),7-Vehicle_Age(Age of the Vehicle),8-Vehicle_Damage(1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past.),9-Annual_Premium(The amount customer needs to pay as premium in the year),10-PolicySalesChannel(Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.), 11-Vintage(Number of Days, Customer has been associated with the company), 12-Response(Target Feature 1 : Customer is interested, 0 : Customer is not interested)
