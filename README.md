# Assessing the Impact of ChatGPT on Various Fields Using Twitter Data

This repository contains the implementation and analysis of how ChatGPT influences various technological fields. The study uses network analysis of Twitter data to explore relationships between hashtags and mentions, focusing on their significance and connectivity.

## Overview

With the emergence of advanced AI technologies like ChatGPT, the research aims to analyze their impact across sectors by studying social media discussions. Twitter is used as the primary data source due to its wide adoption for opinion sharing, leveraging hashtags and mentions for analysis.

**Key Features:**
- Network analysis of Twitter data using hashtags and mentions.
- Graph-based analysis of relationships and connectivity.
- Identification of influential hashtags and user accounts using PageRank, degree distribution, and modularity.

## Methodology

The research methodology is divided into three key steps:

1. **Data Collection & Preprocessing:**
   - Tweets were collected using the Twitter API over 15 days, resulting in a dataset of 100,000 tweets containing attributes like hashtags, mentions, likes, and text.
   - The data was cleaned and structured to create a graph of hashtags and mentions.

2. **Graph Construction:**
   - A directed graph was created where edges represent hashtag-mention pairs with weights based on their frequency.
   - Graph algorithms like Connected Components were used to identify the largest connected subgraph for analysis.

3. **Node Analysis & Clustering:**
   - Centrality measures like PageRank and degree distribution were applied to identify significant nodes.
   - Modularity-based clustering was performed to group nodes into clusters and pinpoint the most influential ones.

## Results

### Key Findings:
- **Influential Nodes:**
  - Notable hashtags include `#ChatGPT`, `#GPT4`, and `#ArtificialIntelligence`.
  - User accounts such as `@OpenAI` and `@TrustWallet` were frequently mentioned.

- **Clusters:**
  - Identified clusters indicate ChatGPT's strong connections with domains like Artificial Intelligence, cryptocurrencies, and Web3 technologies.
  - Key clusters:
    - **Red Cluster:** Includes AI, GPT4, and Python.
    - **Green Cluster:** Includes Web3, Crypto, and MarketExchange.
    - **Purple Cluster:** Includes TrustWallet, TrustAI, and TokenAI.

- **Performance Metrics:**
  - PageRank and degree centrality scores highlighted the prominence of hashtags and user accounts in discussions.

### Visualizations:
The repository includes:
- Word clouds showing prominent hashtags and mentions.
- Graphs illustrating connected components, degree distribution, and modularity-based clusters.


## Acknowledgments

This project was developed as part of the **Neural Networks and Deep Learning** course at the **University of Padova**, during the **Master's program in ICT for Internet and Multimedia**.

Team Members:
- Mahsa Shahbazi
- Seyedali Hosseinishamoushaki
- MirMohammadreza Heidarzadnamin

Project Date: July-2023
