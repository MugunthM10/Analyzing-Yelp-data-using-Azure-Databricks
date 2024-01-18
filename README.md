# Analyzing Yelp Data using Azure Databricks

Yelp is an application to provide the platform for customers to write reviews and provide a star-rating. Yelp published a dataset containing business information, reviews, user information, and check-in information and has continuously been updating the dataset till today. The project aims to examine this dataset which has been made open-source by Yelp to provide sentiment and descriptive analytics to understand local business performance, geo-spatial distribution of businesses, reviewer’s rating, and other characteristics in business premises in America.

𝗔𝗽𝗽𝗿𝗼𝗮𝗰𝗵  
- Download the dataset from Yelp official website.
- upload the data to azure blob storage (or any other stroage service) by creating containers.
- Read yelp datasets in Azure Databricks notebook and convert JSON to parquet using pyspark for better performance.  
- Convert JSON to Delta Format using pyspark.  
- Total records in each dataset.  
- Partition tip dataset tip by a date column.  
- repartition() vs coalesce()  
- Find the top 3 users based on their total number of reviews.  
- Find the top 10 users with the most fans  
- Analyse the top 10 categories by a number of reviews.  
- Analyse top businesses which have over 1000 reviews.  
- Analyse Business Data: Number of restaurants per state.  
- Analyze the top 3 restaurants in each state.  
- List the top restaurants in a state by the number of reviews.  
- Numbers of restaurants in Arizona state per city.  
- Broadcast Join: restaurants as per review ratings in Pheonix city.  
- Most rated Italian restaurant in Pheonix.
- perform sentiment analysis on reviews using the best of various machine learning algorithms such as Multilayer Perceptron, Multinomial Naive Bayes, Gradient Boosting Classifier, XGBoost Classifier, Random Forest Classifier, Decision Tree, K Neighbor Classifier, Support Vector Machine.
- perform data visualization of the results of data analysis.  

𝗧𝗲𝗰𝗵 𝗦𝘁𝗮𝗰𝗸    
➔ Language: Python3, R, SQL 

➔ Services: Azure Blob Storage, Azure Databricks, Spark
