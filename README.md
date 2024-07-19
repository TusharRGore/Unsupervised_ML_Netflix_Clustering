# Unsupervised_ML_Netflix_Clustering
![BrandAssets_Logos_02-NSymbol](https://github.com/user-attachments/assets/d3d2029b-54e4-462a-9d09-ce442f50246a)

Netflix, founded in 1997 by Reed Hastings and Marc Randolph, is a leading global streaming service offering a vast library of television shows, movies, documentaries, and original programming. Initially launched as a DVD rental service, Netflix pivoted to online streaming in 2007, revolutionizing the entertainment industry. With a presence in over 190 countries, it provides content in a variety of languages and genres, catering to diverse audiences. Known for its data-driven approach, Netflix leverages advanced algorithms to recommend personalized content to its users, maintaining its position as a pioneer in the streaming market.
A movie recommendation system is designed to enhance user experience by suggesting films tailored to individual preferences, based on data such as past behavior, ratings, and viewing history. These systems play a crucial role in retaining users by consistently providing relevant and engaging content, which helps keep them subscribed and active on the platform. They also facilitate content discovery, introducing users to movies they might not have found otherwise, thus broadening their viewing options. By quickly narrowing down a vast library to a personalized set of recommendations, these systems save users time and effort. Moreover, they provide a competitive advantage to streaming services by offering a superior, customized user experience. Additionally, recommendation systems can promote new or underwatched content, driving viewership across a broader range of movies. These systems typically use algorithms such as collaborative filtering, content-based filtering, and hybrid methods to improve accuracy and relevance.
Clustering algorithms have a wide range of real-life applications across various domains due to their ability to group similar items together. Here are some examples of how clustering algorithms are used in practice:

1. **Customer Segmentation**: Businesses use clustering to group customers based on purchasing behavior, demographics, or preferences. This helps in targeted marketing, personalized recommendations, and improving customer service.

2. **Market Research**: Clustering helps in identifying distinct market segments, understanding competitive positioning, and analyzing consumer needs. This information is crucial for developing new products and strategies.

3. **Image Segmentation**: In computer vision, clustering algorithms are used to partition an image into meaningful segments, such as distinguishing between different objects in a photo.

4. **Document Classification**: Clustering helps in organizing large sets of documents or articles into topics or categories, which is useful in information retrieval, search engines, and content management systems.

5. **Anomaly Detection**: In cybersecurity and fraud detection, clustering algorithms can identify unusual patterns or outliers in data, such as fraudulent transactions or network intrusions.

6. **Social Network Analysis**: Clustering is used to detect communities or groups within social networks, helping to understand social structures, influence patterns, and relationships.

7. **Genomics**: In bioinformatics, clustering algorithms group genes or proteins with similar expressions or functions, aiding in the understanding of genetic structures and disease mechanisms.

8. **Healthcare**: Clustering is applied to group patients with similar symptoms or medical histories, which can enhance diagnosis, treatment plans, and personalized medicine.

9. **Recommender Systems**: Beyond movies, clustering is used in various recommendation systems to group similar items or users, improving the accuracy of recommendations for books, music, products, etc.

10. **Urban Planning**: Clustering algorithms analyze and segment areas based on various factors such as population density, economic activity, and infrastructure, aiding in efficient urban development and resource allocation.

11. **E-commerce**: Online retailers use clustering to categorize products based on user behavior, product features, or sales data, optimizing inventory management, and enhancing the shopping experience.

**Project Summary**:
This dataset consists of tv shows and movies available on Netflix as of 2020. The dataset is collected from Flixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset. Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

**Project Workflow**:
Here's a workflow for a project:

- **Define Objectives**:
  - Clearly outline the purpose and goals of the clustering project.
  - Identify the key questions you want to answer with clustering.

- **Data Collection**:
  - Gather relevant data from various sources.
  - Ensure data is accurate, complete, and representative.

- **Data Preparation**:
  - Clean the data to handle missing values, outliers, and inconsistencies.
  - Transform and normalize data to ensure all features are on a comparable scale.
  - Select relevant features for clustering.

- **Exploratory Data Analysis (EDA)**:
  - Perform EDA to understand data distributions and relationships.
  - Visualize data using plots and charts to identify patterns and anomalies.

- **Feature Engineering**:
  - Create new features or transform existing ones to enhance the clustering process.
  - Reduce dimensionality using techniques like PCA if needed.

- **Select Clustering Algorithm**:
  - Choose an appropriate clustering algorithm (e.g., K-Means, DBSCAN, Hierarchical).
  - Consider the nature of the data and the specific requirements of the project.

- **Determine Number of Clusters**:
  - Use methods like the Elbow Method, Silhouette Score, or Dendrograms to decide the optimal number of clusters.
  - Experiment with different numbers of clusters to find the best fit.

- **Model Training**:
  - Train the clustering model on the prepared dataset.
  - Fine-tune parameters to improve clustering performance.

- **Evaluate Clusters**:
  - Assess the quality and validity of the clusters using metrics such as Silhouette Score
  - Interpret the results to ensure they make sense in the context of the project objectives.

# Conclusion:

Director and cast contain a large number of null values so we will drop these 2 columns.
In this data set, there are two types of content where 30.86% includes TV shows and the remaining 69.14% carries Movies.
We have concluded from our analysis of the content added over the years that Netflix is focusing on movies and TV shows (From 2016 data we get to know that Movies have increased by 80% and TV shows is increased by 73% compared)
From the data-set insights we can conclude that the most number of TV Shows released in 2017 and for Movies it is 2020
On Netflix USA has the largest number of contents. And most of the countries preferred to produce movies more than TV shows.
Most of the movies are belonging to 3 categories
The TOP 3 content categories are International movies, dramas, and comedies.
In text analysis (NLP) I used stop words, removed punctuation, stemming & TF-IDF vectorizer and other functions of NLP.
Applied different clustering models like K-means, hierarchical, Agglomerative clustering, DBSCAN on data we got the best cluster arrangements.
By applying different clustering algorithms to our data-set .we get the optimal number of cluster is equal to 3
From this clustering analysis, we can create Netflix movies and tv shows recommendation systems & also we can use topic modelling.




