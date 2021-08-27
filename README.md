# CovidSocial2020
Analyzing Social Media Response to Covid pandemic via Machine Learning using telegram data of public channels.
This repo contains notebook for different analysis done regarding this matter and are organized as follows:
- EDA: 
  - Explore.ipynb: explore data and extract some statistical measures and some visualization to gain insight from the data (e.g. frequent items, number of unique values and histograms,...)
  - CharacterWordManipulation.ipynb: text preprocessing like character normalization and tokenize words 
  - WorldLevelAnalysis.ipynb: test different features for modeling words in order to find appropariate features for clustering
- Feature Extaction and Modeling:
  - FeatureExtraction.ipynb: extract features from message texts to be used for clustering later on
  - Clustering.ipynb: cluster text messages on the hypothesis that covid related messages will end up on the same cluster
- Final:
  - AllTogether.ipynb: full model pipeline from preprocessing to clustering and visualization   
