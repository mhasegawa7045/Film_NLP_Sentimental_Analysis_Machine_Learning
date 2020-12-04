# Data Mining and Text Mining 

> Marie Hasegawa `mhasegawa7045@floridapoly.edu`


## Final Project

The purpose of this project is to see if text mining techniques can ease better analysis for categorizing movies with just the `Descriptions` while ignoring the `Genre`from the dataset, `IMDB_movies.csv`, which is stored under the dataframe variable, `movies_desc`. 

- Tokenization (TF-DF) was used to increase efficiency to analyze term frequencies in movie `Descriptions`, so that the conceptual theme of a movie franchise would be determined even if a person has never watched any of the films. 
- Create mixtures of terms that are correlated to every topic and the mixture of topics that distinguishes each document through Topic Modeling in the dataset, `IMDB_movies.csv`.
- Sentimental Analysis focused on Movies with Sentimetal Clusters that were using `bing` and `nrc` lexicons to see how `Sentiment` affects `Rating` and `Revenue`. 
- The network of bigrams for the Movies dataset help summarize how frequented Movie `Description` word-terms create term reklationships and how they connect to other movies.

## References
(n.d.). Retrieved from http://saifmohammad.com/WebPages/NRC-Emotion-Lexicon.htm

Robinson, J. S. A. D. (2020). 2 Sentiment analysis with tidy data | Text Mining with R. Titdy Text Mining. https://www.tidytextmining.com/sentiment.html