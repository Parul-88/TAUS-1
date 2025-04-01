Overview
TAUS-M is a project focused on developing a classification model for multi-class tweets classification. The project utilizes BERT (Bidirectional Encoder Representations from Transformers) embeddings to represent the tweets and employs Graph Attention Networks (GATs) for classification. By leveraging relational data through GATs, TAUS aims to enhance the performance of tweet classification, particularly in processing social media interactions.

The dataset used in this project consists of three classes:

Informative tweets: These are tweets that contain useful and relevant information, labeled as 1.
Emotional tweets: These are tweets that contain emotions, labeled as 2.
Neutral tweets: These are tweets that do not contain any significant information or emotion, labeled as 3.

Introduction
This research aims to develop a classification model to distinguish tweets using BERT embeddings to represent the tweet. BERT is used to extract contextual word representations, capturing the fine semantic nuances of the text. These embeddings are utilized to create a graph for the classification of tweets.

We have employed Graph Neural Networks, specifically the Graph Attention Network (GAT), which performs well in classifying tweets, especially when evaluated on limited sample datasets. GNNs have demonstrated their efficacy in leveraging relational data, which augments the performance of the classifier in processing social media interactions. The proposed model integrates these two state-of-the-art approaches to achieve superior performance in tweet classification related to the context and content of information.

Major Contributions
Curating a Publicly Available Tweet Dataset: Based on a significant event, we have curated a publicly available dataset of tweets.
Creating Tweet Graphs with Varying Degrees of Density: We experimented with different levels of graph density to observe its impact on classification performance.
Extensive Experiments on Graph Attention Networks: Conducted thorough experiments using GATs to classify tweets.
Dataset Statistics:
The file "tweets_with_finbert_sentiments.csv" contains the tweets along with their metadata.
