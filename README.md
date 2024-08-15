# Health-Insurance-Cross-Sell-Prediction
End to End Machine Learning

# Vehicle Insurance Interest Prediction Model

## Overview

This repository contains a predictive model developed to forecast whether customers with existing health insurance will be interested in purchasing vehicle insurance from the same provider. The model leverages various customer attributes and historical insurance data to generate predictions that can help optimize the company's communication strategy and enhance business revenue.

**Business Context**

Our client, an insurance company, currently offers health insurance to its customers. They now seek assistance in developing a model to predict whether these policyholders from the past year might also be interested in purchasing vehicle insurance from the company.

To explain, an insurance policy is a financial arrangement where a company promises to compensate for certain types of loss, damage, illness, or death in exchange for a regular premium payment. For example, you might pay an annual premium of Rs. 5000 for health insurance coverage of Rs. 200,000. If you were to fall ill and require hospitalization within that year, the insurance provider would cover the costs up to Rs. 200,000. The reason a company can offer such high coverage despite the relatively low premium is based on probabilities: not every policyholder will require such extensive care, so the risk is shared among many.

Similarly, vehicle insurance works in the same way. Customers pay an annual premium to the insurance provider, who then offers compensation in case of an accident.

Developing a model to predict which customers might be interested in vehicle insurance is crucial for our client. It will enable them to tailor their communication strategy effectively, optimize their business model, and enhance revenue.

To build this predictive model, we will use information about customer demographics (e.g., gender, age, region), vehicle details (e.g., vehicle age, damage status), and policy information (e.g., premium amount, sales channel).

## Dataset Description

The dataset used for this project includes the following features:

- **id**: Unique ID for the customer
- **Gender**: Gender of the customer (Male/Female)
- **Age**: Age of the customer
- **Driving License**: Whether the customer has a driving license (Yes/No)
- **Region_Code**: Unique code representing the region of the customer
- **Previously_insured**: Whether the customer already has vehicle insurance (Yes/No)
- **Vehicle_age**: Age of the vehicle
- **Vehicle_damage**: Whether there are past damages present on the vehicle (Yes/No)
- **Annual_premium**: Amount the customer needs to pay as a premium
- **Policy SalesChannel**: Anonymized code for the channel used to outreach to the customer (e.g., Different Agents, Over Mail, Over Phone, In Person, etc.)
- **Vintage**: Number of days the customer has been associated with the company
- **Response**: Whether the customer is interested in vehicle insurance (Yes/No)

## Libraries and Tools

- **Pandas**: For data manipulation and aggregation
- **NumPy**: For computationally efficient operations
- **Matplotlib**: For data visualization
- **Seaborn**: For advanced data visualization and behavior analysis
- **Scikit Learn**: For model training, optimization, and metrics calculation


