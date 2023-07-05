# Predicting-Bank-Term-Deposit-Subscription


Introduction
Marketing to potential clients has always been a crucial challenge in achieving success for banking institutions. It’s not a surprise that banks usually deploy mediums such as social media, customer service, digital media, and strategic partnerships to reach out to customers. But how can banks market to a specific location, demographic, and society with increased accuracy? With the inception of machine learning, reaching out to specific groups of people has been revolutionized by using data and analytics to provide detailed strategies to inform banks which customers are more likely to subscribe to a financial product. In this project on bank marketing with machine learning, I will explain how a particular Portuguese bank can use predictive analytics from data science to help prioritize customers who would subscribe to a bank deposit.

The data set is based on the direct marketing campaigns of a Portuguese banking institution. These marketing campaigns were based on phone calls. More than one contact with a client was required in order to know if the product (a bank term deposit) was subscribed by a client or not. The classification goal is to predict if a client will subscribe to the bank’s term deposit (yes or no).

The dataset contains 21 columns, including the output (y). I am going to discard the output column and use the remaining columns to find the most relatable independent variables (x) that will be able to predict if a customer will subscribe to a bank deposit or not.

Here are some informations about the features:

- age: client’s age
- job : type of job
- marital : marital status
- education: client’s last education
- default: does the client have credit in default?
- balance: average yearly balance, in euros
- housing: has housing loan?
- loan: does he client have personal loan?
- contact: contact communication type
- day: last contact day of the month
- month: last contact month of year
- duration: last contact duration, in seconds
- campaign: number of contacts performed during this campaign and for this client
- pdays: number of days that passed by after the client was last contacted from a previous campaign (-1 means client was not previously contacted)
- previous: number of contacts performed before this campaign and for this client
- poutcome: outcome of the previous marketing campaign
- y: has the client subscribed a term deposit?
