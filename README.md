# Zomato_Restaurant_Clustering_and_Sentiment_Analysis
## Project Summery:
Zomato is an Indian restaurant aggregator and food delivery start-up founded by Deepinder Goyal and Pankaj Chaddah in 2008. Zomato provides information, menus and user-reviews of restaurants, and also has food delivery options from partner restaurants in select cities.

India is quite famous for its diverse multi cuisine available in a large number of restaurants and hotel resorts, which is reminiscent of unity in diversity. Restaurant business in India is always evolving. More Indians are warming up to the idea of eating restaurant food whether by dining outside or getting food delivered. The growing number of restaurants in every state of India has been a motivation to inspect the data to get some insights, interesting facts and figures about the Indian food industry in each city. So, this project focuses on analysing the Zomato restaurant data for each city in India.

Steps to be Performed:-

1. Importing libraries
2. Loading the dataset
3. Shape of dataset
4. Dataset information
5. Handling the duplicate values
6. Handling missing values.
7. Undeerstanding the columns
8. Variable description
9. Data wrangling
10. Data visualization
11. Story telling and experimenting with charts.
12. Text preprocessing,
13. Latent Direchlet Allocation
14. Sentiment analysis
15. Challenges faced
16. Conclusion.

There are two separate files, while the columns are self explanatory. Below is a brief description:

Restaurant names and Metadata - This could help in clustering the restaurants into segments. Also the data has valuable information around cuisine and costing which can be used in cost vs. benefit analysis Restaurant reviews - Data could be used for sentiment analysis. Also the metadata of reviewers can be used for identifying the critics in the industry.

# Problem Statement:

The Project focuses on Customers and Company, you have to analyze the sentiments of the reviews given by the customer in the data and made some useful conclusion in the form of Visualizations. Also, cluster the zomato restaurants into different segments. The data is vizualized as it becomes easy to analyse data at instant. The Analysis also solve some of the business cases that can directly help the customers finding the Best restaurant in their locality and for the company to grow up and work on the fields they are currently lagging in.

This could help in clustering the restaurants into segments. Also the data has valuable information around cuisine and costing which can be used in cost vs. benefit analysis

Data could be used for sentiment analysis. Also the metadata of reviewers can be used for identifying the critics in the industry.

# Data Variable Information:

Zomato Restaurant names and Metadata
Use this dataset for clustering part

Name : Name of Restaurants

Links : URL Links of Restaurants

Cost : Per person estimated Cost of dining

Collection : Tagging of Restaurants w.r.t. Zomato categories

Cuisines : Cuisines served by Restaurants

Timings : Restaurant Timings

Zomato Restaurant reviews
Merge this dataset with Names and Matadata and then use for sentiment analysis part

Restaurant : Name of the Restaurant

Reviewer : Name of the Reviewer

Review : Review Text

Rating : Rating Provided by Reviewer

MetaData : Reviewer Metadata - No. of Reviews and followers

Time: Date and Time of Review

Pictures : No. of pictures posted with review


# Conclusion

This project successfully accomplished the objectives of clustering restaurants based on their features and conducting sentiment analysis on user reviews. Through clustering, we gained valuable insights into the grouping of restaurants, helping both users and businesses make informed decisions. The sentiment analysis allowed us to understand the sentiments expressed by users in their reviews, providing businesses with valuable feedback to enhance their services and improve the overall user experience.

The utilization of various data preprocessing techniques, such as text vectorization and feature normalization, played a crucial role in preparing the data for clustering and sentiment analysis. We employed popular machine learning algorithms, including K-Means and Agglomerative Clustering, to create meaningful clusters of restaurants based on their similarities.

For future enhancements, more advanced clustering algorithms and sentiment analysis techniques could be explored to further refine the results. Additionally, incorporating additional features such as images and menus of the restaurants might provide more comprehensive insights.

Overall, this project demonstrates the potential of leveraging data analytics to gain valuable insights into the restaurant industry, aiding both users in making informed choices and businesses in enhancing their services to meet customer expectations.
