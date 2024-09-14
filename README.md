# Social Network Analysis Project 📊

Welcome to my **Social Network Analysis** project repository! This project is part of the coursework for the **Social Network Analysis** class, where I analyzed social networks from different perspectives: 

1. **Facebook Pages Food Dataset** - Analysis of a pre-existing dataset.
2. **Reddit Scraper and Sentiment Analysis** - Data extraction from Reddit using Python's `praw` library.
3. **Individual Presentation Report** - Social Network Analysis in Natural Disaster Response and Recovery
   
## 📁 Project Components

### Part 1: Dataset Analysis (Facebook Pages Food Dataset)
In this part, I analyzed the **Facebook Pages Food** dataset which can be found [here](https://networkrepository.com/fb-pages-food.php). The analysis was focused on:
- Full network analysis of the dataset.
- Creation of two artificial networks:
  - A **Random Network** (Erdos-Renyi model)
  - A **Scale-Free Network** (Barabasi-Albert model)
- Comparison between the real dataset and the artificial networks.

#### Analysis:
- **Detailed Description:** Network size, type, and significance.
- **Network Properties:** Average degree, diameter, connected components, shortest paths, and clustering coefficient.
- **Distribution Plots:** Degree, clustering coefficient, betweenness centrality, and connected component size.
- **Most Important Nodes:** Identification based on various measures.
- **Visualization:** Provided visual representations of the network structure.

### Part 2: Real Data Analysis (Reddit Scraper)
For the second part of the project, I developed a **Reddit Scraper** using Python's `praw` library to collect real-time data. This data was then analyzed and represented as a network. Key aspects of this project include:
- **Data Acquisition:** Extracted data from Reddit using a scraper.
- **Network Representation:** Nodes represent users or posts, and links are based on interactions (comments, upvotes, etc.).
- **Network Analysis:** Applied centrality measures, degree distribution, and clustering coefficients.
- **Sentiment Analysis:** Performed sentiment analysis on the scraped posts to determine general user sentiment in discussions.

## 📑 Individual Presentation Report

I also conducted a **research study** on the application of **Social Network Analysis** in the context of **Natural Disaster Response and Recovery**. This paper examines real-world disaster events and analyzes the evolution of social networks in aiding disaster response.

### [Read the Full Report](https://github.com/BiancaM30/Social-Network-Analysis/blob/main/Individual%20presentation/Report%20-%20Social%20Network%20Analysis%20.pdf)
- **Case Studies**: Louisiana Flood (2016), Hurricane Harvey (2017), Aila Cyclone (2009), Sri Lanka Floods (2017)
- **Key Sections**:
  1. Importance of Social Network Analysis in Disasters
  2. Multi-level Network Dynamics in Disaster Response
  3. Network Properties: Centralization, Connectivity, Resilience
  4. Literature Review of Disaster-related Social Networks
  5. Recommendations for Future Research in Social Network Resilience

## 📊 Tools & Libraries
- **Python**
  - `networkx`
  - `matplotlib`
  - `pandas`
  - `praw` (for Reddit scraping)
  - `nltk` (for sentiment analysis)
- **Gephi** for network visualization.
- **Jupyter Notebooks** for data processing and visualization.


