# MachineLearningNanodegree-CapstoneProject
The repository contains the final Capstone Project for the [Machine Learning Engineer Nanodegree](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009t) by Udacity

# Introduction - Description of the task
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

Not all users receive the same offer, and that is the challenge to solve with this data set.

Your task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products.

Every offer has a validity period before the offer expires. As an example, a BOGO offer might be valid for only 5 days. You'll see in the data set that informational offers have a validity period even though these ads are merely providing information about a product; for example, if an informational offer has 7 days of validity, you can assume the customer is feeling the influence of the offer for 7 days after receiving the advertisement.

You'll be given transactional data showing user purchases made on the app including the timestamp of purchase and the amount of money spent on a purchase. This transactional data also has a record for each offer that a user receives as well as a record for when a user actually views the offer. There are also records for when a user completes an offer.

Keep in mind as well that someone using the app might make a purchase through the app without having received an offer or seen an offer.

# Included in this repository
- capstone_project.ipynb - Jupyter Notebook with the project
- portfolio.json - data: details of offers sent during 30-day test period
- profile.json - data: customers
- transcript.json - data: event log
- joined_data.csv - cached data

# Libraries
- This project is developed in Python 3.7.
- Non-system libraries can be installed running the second cell of `capstone_project.ipynb`
- numpy = "*"
- pandas = "*"
- arrow = "^0.15"
- matplotlib = "*"
- scikit-learn = "^0.23"
- [yellowbrick](https://www.scikit-yb.org/en/latest/index.html) = "==1.2" 
