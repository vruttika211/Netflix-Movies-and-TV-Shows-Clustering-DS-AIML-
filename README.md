The project is divided into two main parts:
1)Exploratory Data Analysis (EDA): The first phase focuses on understanding the dataset's characteristics,
identifying trends, and answering key business questions. 
I performed data cleaning and created various visualizations to explore content distribution by type (movies vs. TV shows), top countries for content, and the growth of Netflix's library over time.

2)Unsupervised Machine Learning (Clustering): The second phase involves building a machine learning model to cluster Netflix content. 
Using text-based features from the listed_in (genres) and description columns, I applied the K-Means clustering algorithm to group similar movies and TV shows together. 
This process can be used to inform content organization and improve recommendation systems.

Conclusion and Future Work
This project demonstrates how data analysis and machine learning can be used to organize and understand a large content library.
The insights from the EDA can inform content acquisition strategies, while the clustering model lays the groundwork for a more sophisticated recommendation engine.
Future work could involve:
Using more advanced text embedding techniques Comparing K-Means with other clustering algorithms, Building a content-based recommendation system based on the generated clusters.
