# Social Network Analysis

Welcome to my **Social Network Analysis** project repository! The project is focused on the analysis of social network datasets, including an analysis of a real Facebook pages network and a Reddit data analysis with sentiment analysis.

## Table of Contents
- [Part 1: Dataset Analysis](#part-1-dataset-analysis)
- [Part 2: Real Data Analysis - Reddit Scraper and Sentiment Analysis](#part-2-real-data-analysis---reddit-scraper-and-sentiment-analysis)
- [Technologies Used](#technologies-used)

---

## Part 1: Dataset Analysis

In this part, I conducted a detailed analysis of the **Facebook Food Pages** dataset from the [Network Repository](https://networkrepository.com/fb-pages-food.php). The dataset contains 620 nodes representing Facebook pages and 2102 edges representing mutual likes between pages.

### Objectives:
1. Provide a detailed description of the network, including network properties such as average degree, diameter, clustering coefficient, and shortest paths.
2. Create two artificial networks using:
   - Erdos-Renyi (random) model
   - Barabasi-Albert (scale-free) model
3. Compare the properties of the real and artificial networks.
4. Visualize the networks and important nodes.
5. Identify the most important nodes in the network according to different centrality measures.

### Summary of the Analysis:
- **Real Network**: High clustering, a few highly connected hubs (scale-free behavior), diameter = 17, average degree = 6.78.
- **Erdos-Renyi Network**: Randomly connected, diameter = 7, lower clustering, average degree = 6.69.
- **Barabasi-Albert Network**: Scale-free behavior, diameter = 6, presence of hubs, average degree = 5.97.

---

## Part 2: Real Data Analysis - Reddit Scraper and Sentiment Analysis

For the second part, I developed a **Reddit Scraper** using the **Python PRAW** library to extract data from a subreddit. The analysis involved building a network where nodes are users, and edges represent replies between users. Additionally, I performed **sentiment analysis** on the comments using **Hugging Face’s DistilBERT model**.

### Objectives:
1. Collect data from Reddit using the PRAW API.
2. Represent the data as a network where nodes represent Reddit users and edges represent interactions (replies).
3. Compute sentiment scores for comments and analyze how negative sentiment propagates through the network.
4. Visualize the network and analyze its properties:
   - Degree distribution
   - Clustering coefficient
   - Shortest paths and centrality measures

### Summary of the Analysis:
- **Nodes**: 806 Reddit users
- **Edges**: 2082 interactions
- **Sentiment Analysis**: Sentiment scores assigned to interactions, with an emphasis on detecting central users with high negativity scores.
- **Network Properties**: Skewed degree distribution, presence of hubs, average shortest path length = 3.39, diameter = 10.

---

## Technologies Used
- **Python** (PRAW, NetworkX, Matplotlib)
- **Hugging Face DistilBERT** (for sentiment analysis)
- **Gephi** (for network visualizations)
- **Pandas** (for data manipulation)
