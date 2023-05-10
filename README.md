# Abstract-Clustering-for-Scientific-Paper-Insights
Abstract Clustering for Scientific Paper Insights

<h2><center><font color=#D40004><u> Unsupervised Clustering and Visualization of Scientific Papers Based on Abstracts </u></font></center></h2>
<h3><center> NECHBA Mohammed, and MOUHAJIR Mohamed </center></h3>
<center> 2st year Artificial Intelligence Engineering student at ENSIAS Rabat (Morocco) </center>
<br> 
# Goal of this Project
The primary objective of this project is to apply unsupervised machine learning techniques to cluster scientific papers based on their abstracts.

By leveraging clustering algorithms for labeling and employing dimensionality reduction methods for visual representation, we aim to create a scatter plot that captures the relationships between papers with similar topics. Papers sharing common themes will be grouped together and plotted in close proximity. Additionally, if the clustering process yields satisfactory results, we will explore the clusters further using topic modeling to extract the most relevant keywords associated with each cluster. This analysis will help identify publications with similar research backgrounds and facilitate comparisons between similar studies and articles.

To ensure the data is suitable for clustering, we will preprocess it using Natural Language Processing (NLP) techniques. Throughout the project, we will also investigate the impact of various preprocessing steps on cluster quality. This includes exploring approaches such as stop word removal, handling multilingual data, and employing diverse vectorization strategies to optimize the clustering results.

# <font color='green'><u> Table of Contents:</u></font> <br>

<font color = 'blue'>
    
1. [Introduction.](#1)

1. [Importing/Loading & checking the data.](#2)

1. [ Data Cleaning.](#3)

1. [NLP data preprocessing.](#4)
 
1. [Model Training: BERTopic.](#5)

    1. [Topic Representation.](#6)

    1. [Topic Relationships.](#7)
    
    1. [Topics over Time.](#8)
    
1. [Clustering using scikit-learn: Uncovering Patterns in Data.](#9)
    
    1. [Vectorization of the abstracts and dimensionality reduction with PCA.](#10)
    
    1. [Hierarchical clustering.](#11)
    
    1. [Spectral clustering.](#12)
    
    1. [Self-organizing maps (SOM).](#13)
  
  <a id = "1"></a><br>
# <font color="green"><u> I. Introduction:</u></font>
  
  The vast amount of scientific literature available today presents both a challenge and an opportunity for researchers to extract meaningful insights from the wealth of information. Clustering and visualizing scientific papers based on their abstracts has emerged as a valuable technique to uncover hidden patterns, identify research trends, and facilitate literature exploration. This project aims to leverage unsupervised machine learning methods to cluster scientific papers and provide visual representations that aid in understanding and navigating the research landscape.

The objective of this project is to apply clustering algorithms to group scientific papers with similar topics together. By analyzing the abstracts, which serve as concise summaries of the papers' contents, we can uncover underlying thematic relationships and identify clusters of papers that share common research themes or domains. Additionally, we aim to employ dimensionality reduction techniques to visualize the clustered papers in a scatter plot, enabling researchers to gain insights at a glance and identify clusters of interest.

Moreover, this project extends beyond clustering and visualization. We seek to explore the interpretability of the clusters by using topic modeling techniques to extract keywords and themes associated with each cluster. This additional layer of analysis provides further context and understanding of the research areas represented by the clusters. It enables researchers to discover publications with similar research backgrounds, compare findings, and gain valuable insights into the broader research landscape.

To ensure optimal clustering results, various preprocessing steps will be applied to the data. Natural Language Processing (NLP) techniques will be employed to clean and prepare the abstracts for analysis. This includes tasks such as stop word removal, handling different languages, and employing different vectorization strategies to represent the text data accurately.

By conducting this project, we aim to contribute to the field of scientific literature analysis by providing a valuable tool for researchers to explore and navigate the vast amount of available knowledge. The clustering and visualization techniques, coupled with topic modeling, will enable researchers to gain a comprehensive understanding of research trends, discover related publications, and make informed decisions about areas of study and collaboration.
  
  
